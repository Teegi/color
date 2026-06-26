# Өнгө сонгогч (Color Picker)

Товч дарахад **улаан** (#e63946) болон **хөх** (#1d3557) хоёрын нэгийг санамсаргүйгээр сонгож, дэлгэцийн фон өнгийг өөрчилдөг энгийн вэб апп.

## Файлууд
- `index.html` — бүх код (HTML + CSS + JS) нэг файлд багтсан.

## Локалаар турших
`index.html`-ийг хөтөч дээрээ нээхэд хангалттай.

## GitHub дээр байршуулах

### 1. Шинэ repo үүсгэх
1. https://github.com/new руу ор.
2. Repository name: жишээ нь `color-picker`.
3. **Create repository** дар.

### 2. Код оруулах (хялбар арга — upload)
1. Шинэ repo хуудсан дээрх **uploading an existing file** холбоос дээр дар.
2. `index.html` болон `README.md` файлуудыг чирч оруулаад **Commit changes** дар.

### 2-р хувилбар (терминалаар)
```bash
git init
git add index.html README.md
git commit -m "Add color picker app"
git branch -M main
git remote add origin https://github.com/<хэрэглэгч>/color-picker.git
git push -u origin main
```

### 3. GitHub Pages-ээр нийтлэх (онлайн линк авах)
1. Repo → **Settings** → зүүн талын **Pages**.
2. **Source** хэсэгт **Deploy from a branch** сонго.
3. Branch: `main`, хавтас: `/ (root)` → **Save**.
4. Хэдэн минутын дараа `https://<хэрэглэгч>.github.io/color-picker/` хаягаар апп нээгдэнэ.
