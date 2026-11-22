# 🚀 MT16 AI Studio - Canlı Konsol Paneli

Bu proje, sunucudaki PM2 süreçlerini izleyen, canlı log akışı (SSE) sunan ve yetkili kullanıcılara web üzerinden terminal komutu çalıştırma yetkisi veren hafif bir yönetim panelidir.

## 🛠️ Kurulum

1. Projeyi klonlayın:
   \`\`\`bash
   git clone https://github.com/bytrkr/konsol.git
   cd konsol
   \`\`\`

2. Başlatın:
   \`\`\`bash
   node kokpit3001.mjs
   \`\`\`

*(Not: Sunucunuzda PM2 yüklü olmalıdır. Konsol, logları okumak için \`pm2 logs\` komutunu kullanır.)*

## ⚙️ Özellikler
- **Canlı Log Akışı:** Port 3000'deki React uygulamasıyla entegre çalışır (SSE).
- **Uzaktan Komut:** Web arayüzünden sunucuya terminal komutu gönderme (PIN korumalı).
- **Canlı Portföy:** \`sanal_portfoy.json\` dosyasını anlık okur.
- **Hafif:** Sadece 2 dosya, sıfır dış bağımlılık.

## 🔐 Güvenlik
Varsayılan PIN kodu: \`1616\`
