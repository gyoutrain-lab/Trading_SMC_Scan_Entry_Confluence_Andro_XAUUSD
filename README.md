# SMC Auto Analyzer (Android + Desktop)

Deploy ke GitHub Pages:
1. Buat repo `smc-analyzer`, upload semua file di folder ini (index.html, og-image.png, icon-*.png, favicon.png, manifest.webmanifest, .nojekyll).
2. Settings → Pages → Branch `main` / root.
3. Ganti placeholder URL di index.html:
   `sed -i 's#https://USERNAME.github.io/smc-analyzer/#https://NAMAKAMU.github.io/NAMA-REPO/#g' index.html`
4. Refresh cache preview: Facebook Sharing Debugger (developers.facebook.com/tools/debug). WhatsApp/IG menyimpan cache, tambahkan `?v=2` di link bila gambar lama masih tampil.
