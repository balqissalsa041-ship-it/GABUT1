FLOWSCOPE ORDERFLOW — WEBSITE

CARA MEMBUAT WEBSITE ONLINE DARI HP ANDROID:
1. Buka https://github.com dan login.
2. Buat repository baru bernama flowscope-orderflow. Pilih Public.
3. Ekstrak ZIP ini di HP menggunakan ZArchiver atau aplikasi Files.
4. Upload semua file yang ada di dalam folder FlowScope_Website langsung ke root repository (jangan upload folder pembungkusnya).
5. Tekan Commit changes.
6. Buka Settings > Pages.
7. Pada Build and deployment pilih Deploy from a branch, branch main, folder /(root), lalu Save.
8. Tunggu beberapa menit. Website akan tersedia di:
   https://USERNAME.github.io/flowscope-orderflow/
   Ganti USERNAME dengan username GitHub kamu.

FITUR:
- Dashboard heatmap likuiditas bergaya Bookmap
- Bubble transaksi, Time & Sales, DOM/order book demo
- Delta, CVD, buy/sell pressure
- Layout responsif untuk Android dan desktop
- Mode simulasi dan kolom koneksi WebSocket untuk feed backend

PENTING:
- Data awal adalah SIMULASI, bukan harga atau orderflow market real-time.
- GC COMEX adalah proxy futures, bukan order book spot XAUUSD HFM.
- Mode LIVE memerlukan backend/provider data yang sah dan mengirim JSON WebSocket.
- Jangan pernah memasukkan API Secret atau private key ke file website atau repository publik.
- Website GitHub Pages publik dapat dibuka orang lain. Ini bukan sistem login pribadi; jangan simpan data rahasia di dalamnya.
