# Installation Guide — Poco X6 Pro (duchamp)

> [!WARNING]
> - Your warranty is void.
> - If you decide to experiment, mess something up, corrupt your storage, turn your phone into a fancy paperweight, or brick it beyond recovery — **don’t blame us**.
> - You are doing this at **your own risk** and take full responsibility for anything that may happen.

> [!NOTE]
> - The device must have an **unlocked bootloader**.
> - Google SDK platform tools **must be installed**.
> - Make a **full data backup** before flashing.
> - Ensure your device has at least **30% battery**.
> - Flash **only** files meant for **Poco X6 Pro (duchamp)**.
> - First boot may take 5–10 minutes. Do **not** interrupt or force reboot unless it exceeds 10 minutes.

---

## Clean Installation

1. Download the latest **aosp_rom.zip** from the [channel](https://t.me/akrapogluhell).
2. Connect your phone to PC and reboot to **fastboot** by holding both power button and volume down keys.
3. Flash the following partitions **one by one** through powershell/terminal using:

```
fastboot flash boot <drag-&-drop-boot.img>
```
```
fastboot flash vendor_boot <drag-&-drop-vendor_boot.img>
```
```
fastboot flash init_boot <drag-&-drop-init_boot.img>
```
4. Reboot to **recovery** using:

```
fastboot reboot recovery
```
5. Select **Factory reset → Format data/factory reset**.
6. Select **Apply update → Apply from ADB**, then sideload the rom using:

```
adb sideload <drag-&-drop-rom.zip>
```
7. After sideload completes, select **YES** to reboot if you have extra packages (i.e., GApps) to install and **NO** if you have none.
8. Select **Factory reset → Format data/factory reset**.
9. Select **Reboot system now**.
---

## Update (Dirty Flash)

> [!NOTE]
> Dirty flashing **will not work** for major Android version upgrades  
> (example: **15.x → 16.x**).


### Recovery Flash

1. Reboot to **Recovery**.
2. Select **Apply update → Apply from ADB**, then sideload the rom using:

```
adb sideload <drag-&-drop-rom.zip>
```
3. After sideload completes, select **YES** to reboot if you have extra packages (i.e., GApps) to install and **NO** if you have none.
4. Select **Reboot system now**.

---

> [!IMPORTANT]
> For **vanilla builds**, **GApps must be reflashed after every update**,  
> including **OTA** and **recovery-based dirty flashes**.

---

## Support / Bug Reports

📢 **[Telegram Group](http://t.me/akrapchat)** 
