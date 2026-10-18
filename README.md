print("--- Program Hitung DP Innova Reborn ---")
tabungan = int(input("Masukkan total tabungan kamu saat ini: "))

if tabungan >= 100000000:
    print("Selamat! DP Rp100 Juta sudah terkumpul. Siap bawa pulang Innova Reborn G Manual!")
else:
    kekurangan = 100000000 - tabungan
    print(f"Tetap semangat ngoding! Uang kamu kurang Rp{kekurangan} lagi untuk capai target DP.")

