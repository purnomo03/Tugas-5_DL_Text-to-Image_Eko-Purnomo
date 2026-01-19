# Tugas 5 Deep Learning Lanjut: Text-to-Image Transformer (Stable Diffusion)

**Data Mahasiswa**
* **NIM:** 41236697
* **Nama:** Eko Purnomo
* **Kelas:** TI-2023-KIP-P2
* **Prodi:** Teknik Informatika
* **Mata Kuliah:** Deep Learning Lanjut
* **Tugas:** Ke-5 Individu (Text-to-Image menggunakan Transformer)
  
---

## Deskripsi Tugas
Tugas ini merupakan implementasi model Text-to-Image berbasis Transformer dengan mekanisme Cross-Attention (konsep Stable Diffusion) menggunakan dataset Pokémon dengan caption teks.

Model dilatih untuk memprediksi token visual berdasarkan prompt teks, sehingga informasi tekstual dapat membimbing proses pembentukan gambar di ruang laten.
Implementasi ini mencakup:

1.  **Text Vectorization:** Mengubah caption teks menjadi representasi numerik.
2.  **Multimodal Data Pipeline:** Integrasi data teks dan gambar menggunakan tf.data.Dataset.
3.  **Transformer dengan Cross-Attention:** Menggabungkan embedding teks dan fitur visual.
4.  **Training Model:** Melatih model untuk memprediksi token visual secara autoregressive.
5.  **Inference (Text-to-Image):** Menghasilkan gambar berdasarkan perintah teks (prompt).
