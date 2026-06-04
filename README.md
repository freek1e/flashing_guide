> 🌍 This document includes both **English 🇬🇧** and **Turkish 🇹🇷** sections.

# English 🇬🇧

## Installation Guide — Poco X6 Pro (duchamp)

> [!WARNING]
> - Your warranty is void.
> - If you decide to experiment, mess something up, **don’t blame me**.
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

1. Download the latest **custom_rom_duchamp.zip** from the [update channel](https://t.me/akrapogluhell).
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
8. Select **Reboot system now**.
---

## Update (Dirty Flash)

> [!NOTE]
> Dirty flashing **will not work** for major Android version upgrades  
> (example: **15.x → 16.x**).

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


## Support / Bug Reports

📢 **[Telegram Group](https://t.me/akrapchat)** 

---

# Türkçe 🇹🇷

## Kurulum Kılavuzu — Poco X6 Pro (Duchamp)

> [!WARNING]
> - Garantiniz geçersizdir.
> - Deneme yapmaya karar verirseniz ve bir şeyleri bozarsanız, **beni suçlamayın**.
> - Bunu **kendi sorumluluğunuzda** yapıyorsunuz ve olabilecek her şeyden tamamen siz sorumlusunuz.

> [!NOTE]
> - Cihazın **bootloader'ı açılmış** olmalıdır.
> - Google SDK platform araçları **kurulu olmalıdır**.
> - Yüklemeden önce **tam bir veri yedeği** alın.
> - Şarjınızın en az **%30** olduğundan emin olun.
> - **Yalnızca** **Poco X6 Pro (Duchamp)** için tasarlanmış dosyaları yükleyin.
> - İlk önyükleme 5-10 dakika sürebilir. 10 dakikayı aşmadığı sürece **kabloyu çekmeyin** veya zorla yeniden başlatmayın.

 ---

## Temiz Kurulum

1. [Güncelleme kanalından](https://t.me/akrapogluhell) en son **custom_rom_duchamp.zip** dosyasını indirin.

2. Telefonunuzu bilgisayara bağlayın ve güç düğmesi ile ses kısma tuşlarını aynı anda basılı tutarak **fastboot** moduna alın.

3. Aşağıdaki bölümleri **tek tek** PowerShell/terminal üzerinden şu komutları kullanarak flaşlayın:

```
fastboot flash boot <sürükle-bırak-boot.img>
```
```
fastboot flash vendor_boot <sürükle-bırak-vendor_boot.img>
```
```
fastboot flash init_boot <sürükle-bırak-init_boot.img>
```
4. Şu komutu kullanarak **recovery** moduna yeniden başlatın:

```
fastboot reboot recovery
```
5. **Factory reset → Format data/factory reset** seçeneğini seçin.

 6. **Apply update → Apply from ADB** seçeneğini seçin, ardından ROM'u şu komutla yükleyin:

```
adb sideload <sürükle-bırak-rom.zip>
```
7. Yükleme tamamlandıktan sonra, ek paketleriniz (örneğin, GApps) varsa yeniden başlatmak için **YES**'i, yoksa **NO**'yu seçin.

8. **Reboot system now** seçeneğini seçin.

---

## Güncelleme (Dirty Flash)

> [!NOTE]
> Dirty flash, büyük Android sürüm yükseltmeleri için **çalışmaz**
> (örnek: **15.x → 16.x**).

1. **Kurtarma** moduna yeniden başlatın.

 2. **Apply update → Apply from ADB** seçeneğini seçin, ardından ROM'u şu komutla yükleyin:

```
adb sideload <sürükle-bırak-rom.zip>
```

3. Yükleme tamamlandıktan sonra, ek paketleriniz (örneğin GApps) varsa yeniden başlatmak için **YES**'i, yoksa **NO**'yu seçin.

4. **Reboot system now** seçeneğini seçin.

---

> [!IMPORTANT]
> **Vanilla sürümler** için, **GApps her güncellemeden sonra yeniden yüklenmelidir**,
> **OTA** ve **kurtarma tabanlı kirli flaşlamalar** dahil.

---

## Destek / Hata Bildirimleri

📢 **[Telegram Grubu](https://t.me/akrapchat)**
