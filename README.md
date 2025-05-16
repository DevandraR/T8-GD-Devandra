# Implementasi Tutorial 8 - Game Balancing & Polishing

- **Nama:** Devandra Reswara Arkananta
- **NPM:** 22060835552

## Implementasi Game Balancing

1. **Repositioning Spawner**
   - Memindahkan posisi spawner ke x=1938, y=80
   - Ini menciptakan tantangan bagi pemain untuk mencapai posisi akhir

2. **Penyesuaian Spawn Rate**
   - Mengubah spawn rate dari 0.5 detik menjadi 1.5 detik
   - Pemain masih bisa menghindari musuh namun tetap memiliki tingkat tantangan yang sesuai

3. **Modifikasi Platform**
   - Menambahkan celah pada platform untuk mencegah penumpukan musuh
   - Ini memungkinkan pemain tetap dapat bernavigasi melewati musuh dengan berhasil

## Implementasi Efek Partikel

1. **Efek Lingkungan**
   - Menambahkan efek partikel hujan dengan trail pada Level 1
   - Meningkatkan atmosfer dan feedback visual

2. **Feedback Karakter**
   - Menerapkan partikel yang responsif terhadap pergerakan karakter pemain
   - Partikel muncul ketika pemain bergerak di atas platform
   - Memberikan feedback visual untuk aksi pemain