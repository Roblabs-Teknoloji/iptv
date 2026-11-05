# Türkçe IPTV

Bu depo, Türkiye'den ve yurt dışından erişilebilen Türkçe canlı yayınları IPTV oynatıcılarında açmak için M3U listesi sunar.

## Oynatıcıya ekleme

VLC, TiviMate veya M3U destekleyen oynatıcınızda şu adresi kullanın:

`https://raw.githubusercontent.com/Roblabs-Teknoloji/iptv/master/index.m3u`

## Yayın kapsamı

Liste yalnızca yayıncıların kendi altyapısında sunduğu, oturum açma gerektirmeyen ve en az 720p olduğu adresinde açıkça belirtilen yayınları içerir. Türkiye'deki ve dünyadaki her kanalın herkese açık, kalıcı bir 720p akışı bulunmadığından liste bu koşulları karşılayan kanallarla sınırlıdır. Ücretli servislerden, erişim belirteci paylaşan bağlantılardan veya yetkisiz yeniden yayınlardan bağlantı eklenmez.

HLS adresleri yayıncı tarafından değiştirilebilir. Çalışmayan yayınları bildirin veya katkı göndermeden önce yayıncının resmî web sitesindeki canlı yayın bağlantısını doğrulayın. Yeni bir akış için resmî kaynak ve en az 1280×720 çözünürlük bilgisi belirtilmelidir.

## Katkı

Yeni kanal için `index.m3u` dosyasına `#EXTINF` satırı ve yayıncının herkese açık doğrudan HLS adresini ekleyin. Kanal adını, dilini ve ülkesini belirtin. DRM, coğrafi kısıtlamayı aşma veya erişim anahtarı gerektiren yayınları eklemeyin.
