# Regression Test Suite - CRUD API

![Regression Tests](https://github.com/Auliah17/regression-test-sipk/actions/workflows/test.yml/badge.svg)

---

## 📋 Deskripsi Tugas

Implementasi Regression Test Suite untuk REST API CRUD (Create, Read, Update, Delete) menggunakan **Jest** dan **Supertest**.

### Endpoint yang Diuji

| Method | Endpoint | Deskripsi |
|--------|----------|-----------|
| GET | /data | Ambil semua data |
| GET | /data/:id | Ambil data berdasarkan ID |
| POST | /data | Tambah data baru |
| PUT | /data/:id | Update data |
| DELETE | /data/:id | Hapus data |

---

## 🚀 Cara Menjalankan Test

```bash
npm install
npm test
