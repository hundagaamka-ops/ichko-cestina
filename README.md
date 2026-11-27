# ICHKO Čeština

Монгол тайлбартай чех хэлний дадлагын веб апп.

## GitHub Pages-д байрлуулах
1. Repository-ийн үндсэн хавтсанд `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` файлуудыг байрлуул.
2. GitHub → Settings → Pages хэсэгт `Deploy from a branch` сонго.
3. Branch: `main`, Folder: `/ (root)` сонгоод Save дар.
4. Deploy дууссаны дараа `https://<username>.github.io/<repository>/` хаягаар нээнэ.

## Шинэ хувилбар
- Service worker cache: v5 (хуучин cache автоматаар цэвэрлэгдэнэ).
- Ахиц: давхар тоолохгүй, энэ төхөөрөмжийн browser storage-д хадгална.
- Чех дуудлага: төхөөрөмжид байгаа `cs-CZ` voice-г ашиглана.
- Интернэтгүй үед өмнө нь нээгдсэн аппын файлууд cache-ээс ажиллана.
