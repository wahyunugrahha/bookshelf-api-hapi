# 📚 Bookshelf API

Bookshelf API adalah sebuah RESTful API sederhana untuk mengelola data buku, dibangun menggunakan [Hapi.js](https://hapi.dev/). API ini memungkinkan pengguna untuk menambahkan, membaca, memperbarui, dan menghapus data buku.

## 🚀 Fitur

- Tambah buku baru
- Ambil daftar semua buku (dengan filter opsional)
- Ambil detail buku berdasarkan ID
- Perbarui data buku
- Hapus buku berdasarkan ID

## 📁 Struktur Proyek

```
bookshelf-api/
├── src/
│   ├── books.js
│   ├── handler.js
│   ├── routes.js
│   └── server.js
├── .gitignore
├── .prettierrc
├── eslint.config.mjs
├── package.json
├── package-lock.json
└── README.md
```

## 📦 Instalasi

1. Clone repositori ini:

```bash
git clone https://github.com/username/bookshelf-api.git
cd bookshelf-api
```

2. Install dependencies:

```bash
npm install
```

3. Jalankan server dalam mode development:

```bash
npm run start-dev
```

Server akan berjalan di: `http://localhost:9000`

## 📌 Endpoint

### `POST /books`
Menambahkan buku baru.

### `GET /books`
Mengambil seluruh daftar buku (dapat difilter dengan query `name`, `reading`, `finished`).

### `GET /books/{id}`
Mengambil detail buku berdasarkan ID.

### `PUT /books/{id}`
Memperbarui data buku berdasarkan ID.

### `DELETE /books/{id}`
Menghapus buku berdasarkan ID.

## ⚙️ Konfigurasi CORS

Semua origin diizinkan untuk mengakses API ini.

## 🧪 Tools & Library

- [@hapi/hapi](https://www.npmjs.com/package/@hapi/hapi)
- [nanoid](https://www.npmjs.com/package/nanoid)
- [nodemon](https://www.npmjs.com/package/nodemon)
- [eslint](https://eslint.org/) (linting)

--------