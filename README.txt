SLS v29.5 — LAUNCHER

1. В Google Apps Script:
   - заменить Код.gs файлом Код.gs из этого комплекта
   - заменить Index.html файлом Index.html из этого комплекта
   - сохранить
   - создать новую версию развертывания

2. В публичном GitHub репозитории:
   slsrentalkz-glitch/SLS-pwa-assets

   Заменить / добавить в КОРНЕ репозитория:
   - index.html       <- файл launcher-index.html, при загрузке переименовать в index.html
   - manifest.webmanifest
   - sls-icon-180.png
   - sls-icon-192.png
   - sls-icon-512.png

3. В GitHub Pages:
   Settings -> Pages
   Source: Deploy from a branch
   Branch: main / root
   Save

4. Ярлык на телефон создавать УЖЕ с адреса GitHub Pages,
   а не с script.google.com.

Apps Script URL внутри launcher:
https://script.google.com/macros/s/AKfycbzpM52b7oy1dqKWaTiSPB8iHgpzBG9pa30m8KlZrXpllLYnbCs6tuGqE6srlJljamJq/exec
