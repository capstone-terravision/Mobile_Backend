# Mobile Backend

## Langkah-langkah Setup

1. **Clone repository ini:**
    ```sh
    git clone https://github.com/capstone-terravision/Mobile_Backend
    ```

2. **Buka Visual Studio Code dan buka folder sebagai tempat penyimpanan:**
    - Buka Visual Studio Code.
    - Klik `File` > `Open Folder...` dan pilih folder tempat kamu menyimpan repository ini.

3. **Tambah file `.env` di direktori `MOBILE_BACKEND` sejajar dengan `.gitignore` atau `package.json`:**
    - Buat file baru dengan nama `.env`.

4. **Tambahkan kode berikut ke dalam file `.env`:**
    ```env
    DATABASE_URL=mongodb+srv://capstoneterravision:vrQHo5UIuLezmzOn@terravision.hqtcw7g.mongodb.net/
    PORT=8000

    ACCESS_TOKEN_SECRET=QpfG9PvFkLwt7Hs4UNq68bK2XRVSdjuaWzhgeT5mCB3rMJDyYn
    REFRESH_TOKEN_SECRET=tJcunEk8WjrwR932Zhm6LsB4YqFvHg5xaAVXMeTbUdPSzpDNKQ

    //default

    DEFAULT_PIC=http://res.cloudinary.com/dnnwlqjk8/image/upload/v1712689326/hjtaewkaj0izgtpfuf73.png
    DEFAULT_STATUS=Investor
    ```

5. **Buka terminal dan instal dependencies:**
    - Jalankan perintah berikut di terminal untuk menambah nodemon:
      ```sh
      npm add nodemon
      ```
    - Instal dependencies yang diperlukan dengan perintah:
      ```sh
      npm install
      ```
    - Untuk menjalankan backend, gunakan perintah:
      ```sh
      npm run dev
      ```

## Menjalankan Aplikasi

Untuk menjalankan backend, buka terminal di direktori proyek dan jalankan perintah:
```sh
npm run dev
