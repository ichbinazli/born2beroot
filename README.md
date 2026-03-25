# 🖥️ B2b

> Sistem yönetimi ve Linux güvenliği üzerine odaklanan bir proje.

---

## 🚀 Proje Hakkında

Temel bir Linux sunucusunun kurulması ve yapılandırılması üzerine odaklanır. Amaç:

* 🔐 Güvenli bir sistem kurmak
* 🧱 Minimal ve doğru yapılandırma yapmak
* ⚙️ Sistem servislerini yönetmek

---

## 🧱 Kullanılan Teknolojiler

* Debian / CentOS (Linux)
* VirtualBox
* Bash
* System administration tools
* UFW (Firewall)
* SSH

---

## ⚙️ Yapılanlar

✔️ Linux sanal makine kurulumu
✔️ Disk partitioning (LVM)
✔️ SSH servisi kurulumu
✔️ Güvenlik politikaları (firewall - UFW)
✔️ Kullanıcı ve grup yönetimi
✔️ Şifre politikaları oluşturma
✔️ Cron ile otomasyon

---

## 🔐 Güvenlik Ayarları

* Root erişimi kısıtlandı
* SSH sadece belirli port üzerinden açık
* Firewall ile portlar kontrol edildi
* Güçlü parola politikaları uygulandı

---

## 📊 İzleme ve Loglama

* Sistem logları takip edildi
* CPU, RAM kullanımı izlenebilir hale getirildi
* Cron ile belirli aralıklarla bilgi toplandı

---

## 🧠 Öğrendiklerim

* Linux sistem yönetimi
* Kullanıcı ve izin yönetimi
* Ağ ve güvenlik konuları
* Disk yönetimi ve partition
* Servis yönetimi

##Disk Yapısı (LVM)

- `/` (root)
- `/home`
- `/var`
- `/srv`
- `swap`

Bu yapı sayesinde:
- Disk yönetimi daha esnek olur
- Genişletme kolaylaşır
