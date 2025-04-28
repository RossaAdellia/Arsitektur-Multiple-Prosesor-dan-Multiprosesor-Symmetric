# Arsitektur-Multiple-Prosesor-dan-Multiprosesor-Symmetric

![Arsitektur Multiplr Prosesor dsn Multiprosesor](https://github.com/user-attachments/assets/11cd3089-fe3a-44c0-ab55-e80bdb73f64a)


# Multiple Prosesor (kiri):
Terdapat satu Master CPU yang mengatur dan membagi tugas ke beberapa CPU lainnya (CPU 1, 2, 3).
Semua CPU berhubungan dengan Memory/I/O melalui jalur utama yang dikendalikan Master.
Ini disebut arsitektur terpusat karena semua kendali dipegang oleh Master CPU.

# Multiprosesor Simetris (kanan):
Semua CPU (CPU 1-4) memiliki hak yang sama.
CPU-CPU tersebut berbagi Shared Memory/I/O secara langsung.
Ini disebut arsitektur simetris, karena tidak ada satu CPU yang lebih tinggi kedudukannya dari CPU lain.
