# ChessBot (Android)

chess.com mobil uygulamasında, ikinci cihazdaki kendi hesabına karşı Stockfish ile oynayan Android uygulaması.
Ekran görüntüsü alır, tahtayı okur, Stockfish'e sorar ve hamleyi ekrana dokunarak oynar.

## Derleme (GitHub Actions)
1. Bu klasörün içeriğini bir GitHub reposuna yükle (main dalı).
2. Actions sekmesinde "Build APK" çalışır (~5-10 dk).
3. Bitince run sayfasındaki **Artifacts > chessbot-apk** dosyasını indir, zip'ten çıkan `app-debug.apk`'yı telefona kur.

## Kullanım
Uygulamayı aç ve içindeki 4 adımı izle.

## Notlar
- Android 11+ gerekir (ekran görüntüsü için), arm64 telefon.
- Android 13+: APK'yı yan yükleme ile kurduysan Erişilebilirlik'i açmadan önce Uygulama bilgisi > ⋮ > "Kısıtlı ayarlara izin ver".
- Tahta temasını düz renkli yap. Taş şablonları her oyunun başlangıç pozisyonundan öğrenilir, bu yüzden ▶'e oyunun ilk anında bas.
- Terfi (piyon -> vezir) için chess.com'da otomatik vezir ayarı varsa aç.
- Sadece kendi hesapların arasında kullan; rastgele rakiplere karşı kullanma.
