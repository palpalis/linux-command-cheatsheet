
# 🐧 Linux Terminal Komutları Rehberi

## 🔍 Temel Komutlar
### Dosya İşlemleri
ls -la                           # Detaylı liste
cp kaynak hedef               # Kopyalama
mv eski_ad yeni_ad              # Taşıma/Yeniden adlandırma
grep "metin" dosya.txt          # Metin arama

### 🌟 **Özellikler**
- **Kopyala-Yapıştır Dostu**: Tüm kod blokları direkt kullanılabilir
- **Kategorize Edilmiş**: Komut türlerine göre gruplandırılmış
- **Markdown Uyumlu**: GitHub/GitLab'da mükemmel görünür
- **Renkli Vurgular**: Okumayı kolaylaştıran format
```
### 💻 **Terminalde Hızlı Oluşturma**
Tek komutla dosya oluşturmak için:

uname -a                        # Çekirdek bilgisi
df -h                           # Disk kullanımı
free -h                         # RAM kullanımı
ping google.com                 # Bağlantı testi
ifconfig                        # Ağ arabirimleri
netstat -tuln                   # Açık portlar
top                             # Canlı sistem izleme
ps aux | grep "proses_adı"      # Süreç arama
kill -9 PID                     # Süreç sonlandırma

```
```
log() {
  echo "$(date '+%Y-%m-%d %H:%M:%S') - $1" >> /var/log/custom.log
}
```

```bash
  ╭───╮ ╭───╮
  │ █ │ │ █ │
  ╰───╯ ╰───╯
  ```

  ```bash
  # Sistem
alias update='sudo apt update && sudo apt upgrade -y'
alias c='clear'

# Güvenlik
alias rm='rm -i'                # Onaylı silme

sudo apt install paket_adı      # Kurulum
sudo apt remove paket_adı       # Kaldırma
sudo apt autoremove             # Gereksizleri temizle

glow commands.md || cat commands.md]
EOF

```
