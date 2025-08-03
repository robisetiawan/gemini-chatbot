# Chatbot Laravel dengan Gemini AI

Proyek ini adalah contoh implementasi chatbot sederhana yang didukung oleh model AI Gemini. Chatbot ini dirancang untuk berfungsi sebagai asisten ahli khusus dalam framework Laravel, dengan persona layaknya Taylor Otwell, kreator Laravel.

### Model AI yang Digunakan

Chatbot ini dibangun menggunakan model **Gemini 1.5 Pro** dari Google. Model ini dipilih karena kemampuannya yang canggih dalam pemahaman konteks, penalaran, dan efisiensi dalam menjawab pertanyaan spesifik, menjadikannya ideal untuk peran asisten teknis.

### Peran AI dalam Chatbot Ini

Peran utama AI dalam chatbot ini adalah sebagai **konsultan ahli Laravel**. Melalui `systemInstruction` yang telah ditentukan, AI dilatih untuk:

* Berperan sebagai **Taylor Otwell**, kreator Laravel.
* Menjawab semua pertanyaan seputar framework Laravel.
* Membantu menyelesaikan masalah dan error dalam kode Laravel.
* Memberikan solusi yang akurat, singkat, dan langsung pada intinya.
* Menolak dengan sopan pertanyaan yang berada di luar konteks Laravel dan mengalihkan kembali percakapan ke topik yang relevan.

Dengan peran ini, chatbot dapat memberikan dukungan yang terfokus dan berharga bagi para developer Laravel.

### Cara Instalasi

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek secara lokal.

#### Prasyarat

Pastikan Anda sudah menginstal:

* Node.js dan npm
* Kunci API Gemini (dapat diperoleh dari Google AI Studio)

#### Langkah-langkah

1.  **Clone repository ini**:
    ```bash
    git clone https://github.com/robisetiawan/gemini-chatbot.git
    cd nama-repo-anda
    ```
2.  **Instal dependensi Node.js**:
    ```bash
    npm install
    ```
3.  **Buat file konfigurasi**:
    Buat file `.env` di root direktori dan tambahkan kunci API Gemini Anda, dan bisa didapatkan di https://aistudio.google.com:
    ```
    GEMINI_API_KEY=YOUR_API_KEY
    ```
4.  **Jalankan aplikasi**:
    ```bash
    node index.js
    ```
    Aplikasi akan berjalan pada `http://localhost:3000`. Anda bisa menguji endpoint `/chat` dengan mengirimkan permintaan POST yang berisi pesan dari pengguna.
