  SIMPLE SETUP(BASİT KURULUM)
ufw kontrol --> sudo ufw status /n
ssh kontrol --> sudo service ssh status
işletim sistemi kontrol --> uname -a

  USER(KULLANICI)
kullanıcı gruplarını kontrol etme --> sudo groups <kullanıcı adı>
yeni kullanıcı ekleme --> sudo adduser <yeni kullanıcı>
kullanıcıları listeleme --> less /etc/passwd
şifreleme politikaları düzenleme --> sudo vim /etc/pam.d/common-password
grup oluştırma --> sudo groupadd <grup adı>
gruba kullanıcı ekleme --> sudo adduser <kullanıcı adı> <grup adı>

  HOSTNAME AND PARTITION(ANA BİLGİSAYAR VE BÖLÜM)
makine adı kobtrol --> hostnamectl
makine adı değiştirme --> hostnamectl set-hostname <yeni mak. adı>
                          sudo reboot
bölümleri listeleme --> lsblk

  SUDO
sudo kontrolü --> sudo --version
yeni kullanıcıyı sudo grubuna ekleme --> sudo adduser <yeni kul. adı> sudo
/var/log/sudo klasöründeki dosya kontrolü --> cd /var/log/sudo

  UFW
ufw kontrölü --> sydo ufw status numbered
yeni bağlantı noktası ekleme --> sudo ufw allow <port num>
bağlantı noktasını silme --> sudo ufw status numbered
                             sudo ufw delete <silmek istediğin port no>

  SSH
ssh kontrölü --> sudo service ssh status
yeni oluşturulan kullanıcı ile ssh kullanma --> <yeni kullanıcı> @localhost -p 4242

  SCRIP MONITORING
monitoring.sh dostasını açmak için --> sudo vim /usr/local/bin/monitoring.sh
crontab ayarkarını görüntülemek için --> sudo crontab -e
