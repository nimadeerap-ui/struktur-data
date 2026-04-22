```mermaid
flowchart TD
    A([Mulai]) --> B[/Input data peminjam/]
    B --> C[Enqueue (Tambahkan ke antrian)]
    C --> D[Dequeue (Proses antrian terdepan)]
    D --> E[Display (Tampilkan semua antrian)]
    E --> F[Peek (Lihat antrian terdepan)]
    F --> G([Selesai])
