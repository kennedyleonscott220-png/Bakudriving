# Drive Bakı — Sürüş Simulyatoru

Azərbaycan dilində, HTML/CSS/JavaScript ilə hazırlanmış yüngül brauzer əsaslı sürüş oyunu prototipi. Heç bir build mərhələsi və əlavə kitabxana tələb etmir.

## Xüsusiyyətlər

- Mexaniki (mufta və əl ilə sürət dəyişmə) və avtomatik sürətlər qutusu
- **Analog qaz, əyləc və mufta pedalları** — pedala basıb barmağı yuxarı-aşağı sürüşdürərək basma səviyyəsini tənzimlə
- Pedalların ölçüsü və şəffaflığı üçün parametrlər
- 4–7 pilləli sürət qutusu seçimi, mühərrik gücü, sükan həssaslığı və maksimum sürət ayarları
- Klaviatura idarəetməsi: ox düymələri və ya WASD; `Shift` mufta; `1`–`6` sürət seçimi
- Telefon və masaüstü brauzerlərə uyğun responsiv ekran
- Xal, məsafə, sürət göstəricisi və trafik

## İşə salmaq

1. Repozitoriyanı yüklə və ya ZIP faylını aç.
2. `index.html` faylını müasir brauzerdə aç.
3. Parametrlərdən sürətlər qutusunu və idarəetməni seç, sonra **Oyuna başla** düyməsinə bas.

Ən yaxşı nəticə üçün Chrome, Edge, Firefox və ya Safari-nin yenilənmiş versiyasından istifadə et. Oyun tamamilə lokal işləyir; server və internet bağlantısı tələb etmir.

## GitHub-da paylaşmaq

1. GitHub-da yeni repository yarat (məsələn, `baki-drive-simulator`).
2. Bu qovluqdakı `index.html`, `README.md`, `LICENSE` və `.gitignore` fayllarını repository-yə yüklə.
3. Sayt kimi yayımlamaq üçün repository-də **Settings → Pages** bölməsinə keç, `Deploy from a branch` seç, `main` branch və `/ (root)` qovluğunu seç, sonra yadda saxla.
4. Bir az gözlədikdən sonra GitHub Pages bölməsində göstərilən ünvanı paylaş.

## Məhdudiyyətlər

Bu, 2D canvas prototipidir; 3D qrafika və real avtomobil fizikasını tam simulyasiya etmir. Trafik və yol hərəkəti sadələşdirilmişdir.

## Lisenziya

MIT lisenziyası — detalları `LICENSE` faylında.
