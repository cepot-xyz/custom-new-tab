# Custom New Tab Page

Dashboard produktif untuk tab baru Chrome Anda. Greeting, jam, tasks, bookmarks, dan background media.

## Setup (3 Langkah)

### 1. Simpan File
Letakkan `indexv.html` di folder dokumen atau Desktop Anda.

### 2. Install Ekstensi Chrome
Buka Chrome Web Store, cari "Custom New Tab Page", klik "Add to Chrome".

### 3. Konfigurasi Ekstensi
Di pengaturan ekstensi, masukkan path file:

**Windows:**
```
file:///C:/Users/NamaUser/Documents/indexv.html
```

**Mac/Linux:**
```
file:///home/namauser/Documents/indexv.html
```

Selesai! Buka tab baru.

## Fitur

- Double-click nama untuk edit
- Ketik `/` untuk cari
- "ADD BOOKMARK" untuk simpan link favorit
- "DAILY TASK" untuk daftar tugas
- Edit line 181 di `indexv.html` untuk ubah background:
  ```javascript
  const BACKGROUND_MEDIA = 'bg-video.webm';
  ```

## FAQ

**Dashboard tidak muncul?**
- Cek path file (gunakan `file:///` dengan 3 slash)
- Restart browser

**Background tidak muncul?**
- File harus di folder yang sama dengan `indexv.html`

**Data hilang?**
- Semua data simpan di browser (Local Storage)
- Clear cache akan hapus data
