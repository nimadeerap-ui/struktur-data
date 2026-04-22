```mermaid
flowchart TD
    A([Mulai]) --> B[/Input data peminjam/]
    B --> C[Enqueue<br/>(Tambahkan ke antrian)]
    C --> D[Dequeue<br/>(Proses antrian terdepan)]
    D --> E[Display<br/>(Tampilkan semua antrian)]
    E --> F[Peek<br/>(Lihat antrian terdepan)]
    F --> G([Selesai])
