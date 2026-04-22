## 🔥 Kalau mau 2 baris (lebih rapi kayak gambar)

Pakai tanda \n:

markdown
mermaid
flowchart TD
    A([Mulai]) --> B[/Input data peminjam/]
    B --> C[Enqueue\n(Tambahkan ke antrian)]
    C --> D[Dequeue\n(Proses antrian terdepan)]
    D --> E[Display\n(Tampilkan semua antrian)]
    E --> F[Peek\n(Lihat antrian terdepan)]
    F --> G([Selesai])
