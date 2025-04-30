# ☕ Coffee App – Storyboard & User Flow

## 1. Splash Screen  
*Tujuan:* Memberikan kesan pertama yang menarik dan memperkuat branding.  
*Elemen:*  
- Gambar: Ilustrasi biji kopi melompat dari cangkir  
- Judul: “Choose your favorite coffee”  
- Subjudul: “The best grain, the finest roast, the powerful flavor”  
- Tombol: *Get Started*  
- Navigasi: → Menuju ke Home Screen

---

## 2. Home Screen  
*Tujuan:* Menampilkan berbagai jenis kopi, fitur pencarian, dan promosi.  
*Elemen:*  
- Search Bar  
- Filter Kategori: *Espresso* | *Cappuccino (aktif)* | *Latte*  
- Banner Promo: "Buy One, Get One Free" + tombol *Order Now*  
- Grid Produk: Gambar | Nama Produk | Harga | Rating  
- Bottom Navigation Bar:
  - Explore  
  - Cart  
  - Wishlist  
  - My Orders  
  - Profile  

*Navigasi:*  
→ Klik produk → Detail Produk  
→ Gunakan bottom navigation untuk berpindah halaman

---

## 3. List Produk (Opsional)  
*Tujuan:* Menampilkan daftar produk dalam format vertikal.  
*Elemen:*  
- Judul: *List*  
- Tombol: < Back  
- Daftar Produk: Gambar | Nama Produk | Harga | Rating  

*Navigasi:*  
→ Klik produk → Detail Produk

---

## 4. Detail Produk  
*Tujuan:* Menampilkan informasi lengkap kopi & pilihan pembelian.  
*Elemen:*  
- Gambar besar  
- Nama Produk: *Cappuccino*  
- Ukuran: Small / Medium / Large  
- Jumlah: + / –  
- Rating: ⭐ 4.9  
- Deskripsi  
- Tombol: *Proceed to Checkout*  

*Navigasi:*  
→ Ke halaman My Cart

---

## 5. My Cart  
*Tujuan:* Tinjau pesanan sebelum lanjut ke pembayaran.  
*Elemen:*  
- Judul: *My Cart*  
- Daftar Item: Nama | Ukuran | Jumlah | Harga  
- Input Kode Diskon + Tombol *Apply*  
- Ringkasan Biaya:
  - Subtotal  
  - Delivery Fee  
  - Tax  
  - Total  
- Tombol: *Proceed to Checkout*  

*Navigasi:*  
→ Ke halaman Checkout

---

## 🔁 User Flow (Alur Navigasi)

```text
Splash Screen 
    ↓
Get Started 
    ↓
Home Screen 
    ↓
Pilih Produk 
    ↓
(Opsional) List Produk 
    ↓
Detail Produk 
    ↓
Add to Cart 
    ↓
My Cart 
    ↓
Checkout
