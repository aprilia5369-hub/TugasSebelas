# TugasSebelas

# PERSISTENCE
Persistence adalah proses menyimpan dan mengambil data dari database secara terstruktur.
# ENTITY CLASS
Entity class adalah representasi sebuah tabel database dalam bentuk objek Java.
Anotasi penting:@Entity → menandai class sebagai entity.
o	@Table(name="tabel") → menandai nama tabel di database.
o	@Id → menandai primary key.
o	@GeneratedValue → strategi auto increment untuk primary key.
o	@Column → menandai kolom, bisa diatur nullable, length, dan unique.

# STEPS
1. Buat persistence unit dengan cara, klik kanan package – new – Entity Classes from Database
2. Pilih koneksi databasenya dan pindahkan ke kanan tabel yang dibutuhkan
3. Centang atas dan bawah lalu, Klik next
4. Klik Finish
5. Akan muncul secara otomatatis package dan file ini
6. Coding pada Insert, Update, Delete, Tampilkan Data, Cetak, Upload 
