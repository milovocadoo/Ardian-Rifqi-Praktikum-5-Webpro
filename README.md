1. Pengertian Bootstrap

  Bootstrap adalah framework CSS yang digunakan untuk mempermudah pembuatan tampilan website agar lebih menarik, rapi, dan responsif. Bootstrap menyediakan berbagai komponen dan class siap pakai, seperti navbar, tombol, form, card, dan grid.
  Kegunaan Bootstrap adalah mempercepat proses pembuatan website karena kita tidak perlu menulis semua kode CSS dari awal. Bootstrap juga membantu membuat tampilan website yang dapat menyesuaikan ukuran layar, baik laptop maupun HP.

2. Memasang Bootstrap 
  Ada beberapa cara untuk menggunakan Bootstrap dalam sebuah project, yaitu:
    1. Menggunakan CDN (Content Delivery Network), yaitu menghubungkan file HTML dengan Bootstrap melalui URL. Cara ini praktis karena tidak perlu mengunduh file Bootstrap terlebih dahulu.
    
    Contoh:
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
            rel="stylesheet">
    2. Mengunduh file Bootstrap, yaitu mengunduh file CSS dan JavaScript Bootstrap, kemudian menyimpannya di dalam folder project dan menghubungkannya dengan HTML.
    3. Menggunakan package manager, seperti npm, untuk memasang Bootstrap ke dalam project melalui terminal.

3. Grid dan Breakpoint 
- Grid adalah sistem tata letak Bootstrap yang digunakan untuk mengatur posisi dan ukuran elemen pada halaman website. Sistem grid Bootstrap menggunakan 12 kolom dan biasanya disusun menggunakan class container, row, dan col.

    Contoh:
    <div class="container">
        <div class="row">
            <div class="col-6">Kolom 1</div>
            <div class="col-6">Kolom 2</div>
        </div>
    </div>

Kode itu membagi area menjadi dua kolom dengan lebar masing-masing setengah baris.

- Breakpoint adalah batas ukuran layar yang digunakan Bootstrap untuk menyesuaikan tata letak berdasarkan ukuran perangkat. Breakpoint membantu website tampil responsif pada HP, tablet, dan laptop.

    Contoh class breakpoint:
    - col-sm-6: menggunakan lebar 6 dari 12 kolom mulai dari ukuran layar sm ke atas.
    - col-md-6: menggunakan lebar 6 dari 12 kolom mulai dari ukuran layar md ke atas.
    - col-lg-4: menggunakan lebar 4 dari 12 kolom mulai dari ukuran layar lg ke atas.

4. Class Bootstrap 

    Class Bootstrap	Kegunaan
    container	Membuat wadah konten dengan lebar yang menyesuaikan breakpoint.
    text-center	Membuat teks rata tengah.
    bg-success	Memberikan warna latar hijau.
    btn	Memberikan tampilan dasar pada tombol.
    btn-primary	Memberikan tampilan tombol berwarna biru.
    d-flex	Mengaktifkan layout Flexbox.
    justify-content-center	Memposisikan konten di tengah pada sumbu utama Flexbox.
    form-control	Memberikan tampilan standar pada elemen input form.
    mt-3	Memberikan margin atas sebesar 1 rem.
    img-fluid	Membuat gambar responsif terhadap ukuran wadahnya.

5. Gambar Responsif
    Agar gambar pada website responsif dan menyesuaikan ukuran layar perangkat, kita dapat menggunakan class Bootstrap img-fluid. Class ini membuat gambar memiliki lebar maksimum 100% dari wadahnya dan tinggi otomatis sehingga proporsi gambar tetap terjaga.

    Contoh:
    <img src="gambar.jpg" class="img-fluid" alt="Gambar buku">

    Dengan menggunakan img-fluid, gambar tidak akan melebihi lebar wadahnya sehingga lebih mudah menyesuaikan tampilan pada HP, tablet, maupun laptop.
