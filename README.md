  <h2>SIMPLE SETUP(BASİT KURULUM)</h2>
<p>ufw kontrol --> sudo ufw status</p>
<p>ssh kontrol --> sudo service ssh status</p>
<p>işletim sistemi kontrol --> uname -a</p>

  <h2>USER(KULLANICI)</h2>
<p>kullanıcı gruplarını kontrol etme --> sudo groups <kullanıcı adı></p>
<p>yeni kullanıcı ekleme --> sudo adduser <yeni kullanıcı></p>
<p>kullanıcıları listeleme --> less /etc/passwd</p>
<p>şifreleme politikaları düzenleme --> sudo vim /etc/pam.d/common-password</p>
<p>grup oluştırma --> sudo groupadd <grup adı></p>
<p>gruba kullanıcı ekleme --> sudo adduser <kullanıcı adı> <grup adı></p>

  <h2>HOSTNAME AND PARTITION(ANA BİLGİSAYAR VE BÖLÜM)</h2>
<p>makine adı kobtrol --> hostnamectl</p>
<p>makine adı değiştirme --> hostnamectl set-hostname <yeni mak. adı></p>
                          <p>sudo reboot</p>
<p>bölümleri listeleme --> lsblk</p>

  <h2>SUDO</h2>
<p>sudo kontrolü --> sudo --version</p>
<p>yeni kullanıcıyı sudo grubuna ekleme --> sudo adduser <yeni kul. adı> sudo</p>
<p>/var/log/sudo klasöründeki dosya kontrolü --> cd /var/log/sudo</p>

  <h2>UFW</h2>
<p>ufw kontrölü --> sydo ufw status numbered</p>
<p>yeni bağlantı noktası ekleme --> sudo ufw allow <port num> </p>
<p>bağlantı noktasını silme --> sudo ufw status numbered</p>
                             sudo ufw delete <silmek istediğin port no></p>

  <h2>SSH</h2>
<p>ssh kontrölü --> sudo service ssh status</p>
<p>yeni oluşturulan kullanıcı ile ssh kullanma --> <yeni kullanıcı> @localhost -p 4242</p>

  <h2>SCRIP MONITORING</h2>
<p>monitoring.sh dostasını açmak için --> sudo vim /usr/local/bin/monitoring.sh</p>
<p>crontab ayarkarını görüntülemek için --> sudo crontab -e</p>
