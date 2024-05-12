# Roadmap CSS dari Pemula hingga Ahli

Berikut adalah roadmap yang bisa diikuti untuk menjadi ahli dalam CSS, mulai dari pemula hingga ahli.

## Tahap 1: Pemula
1. **Dasar-dasar HTML dan CSS**: Pelajari struktur dasar HTML dan CSS.
2. **Box Model**: Pahami konsep box model CSS, termasuk margin, border, padding, dan content.
3. **Selektor CSS**: Pelajari berbagai tipe selektor CSS seperti selektor elemen, kelas, id, dan kombinasi mereka.
4. **Properti Dasar**: Kuasai properti dasar CSS seperti color, font, background, dan margin.
5. **Flexbox**: Pelajari layouting dengan Flexbox untuk mengatur elemen dalam container.
6. **Responsif Web Design**: Pahami konsep responsif web design menggunakan media queries.

## Tahap 2: Menengah
1. **Grid CSS**: Pelajari layouting dengan Grid CSS untuk pembuatan layout yang lebih kompleks.
2. **Pseudo-classes dan Pseudo-elements**: Pahami penggunaan pseudo-classes dan pseudo-elements untuk styling dinamis.
3. **CSS Preprocessor (SASS/LESS)**: Pelajari salah satu dari preprocessor CSS seperti SASS atau LESS untuk meningkatkan produktivitas dalam menulis CSS.
4. **Transformasi dan Transisi**: Pelajari cara menggunakan transformasi dan transisi CSS untuk efek visual yang lebih menarik.
5. **Animasi CSS**: Pahami cara membuat animasi menggunakan CSS untuk menambahkan interaktivitas ke situs web Anda.
6. **Responsive Frameworks**: Kenali framework responsif seperti Bootstrap untuk mempercepat pembangunan website responsif.

## Tahap 3: Lanjutan
1. **CSS Architecture**: Pelajari prinsip-prinsip arsitektur CSS seperti BEM (Block Element Modifier) atau OOCSS (Object-Oriented CSS) untuk meningkatkan skalabilitas dan pemeliharaan kode.
2. **CSS Custom Properties (Variables)**: Pelajari penggunaan variabel CSS untuk memudahkan pengelolaan dan pengubahan nilai-nilai yang sering digunakan.
3. **CSS Methodologies**: Pelajari metodologi CSS seperti SMACSS (Scalable and Modular Architecture for CSS) atau Atomic CSS untuk membangun kode CSS yang terstruktur dan mudah dipelihara.
4. **CSS Grid Frameworks**: Pelajari framework grid yang lebih canggih seperti Susy untuk lebih banyak kontrol dalam layout.
5. **CSS Optimization**: Pelajari teknik-teknik optimasi CSS seperti pengurangan CSS yang tidak terpakai, penggabungan file, dan minifikasi untuk meningkatkan kinerja situs web.
6. **CSS-in-JS**: Pahami konsep CSS-in-JS untuk memadukan CSS dengan logika JavaScript dalam pengembangan web modern.

## Tahap 4: Ahli
1. **CSS Transforms**: Pelajari transformasi CSS yang lebih kompleks seperti 3D transforms untuk pembuatan efek yang lebih mendalam.
2. **CSS Architecture Patterns**: Kuasai pola arsitektur CSS yang kompleks seperti ITCSS (Inverted Triangle CSS) untuk proyek skala besar.
3. **CSS Performance Optimization**: Lanjutkan dengan optimasi kinerja CSS yang lebih dalam seperti menggunakan teknik critical CSS untuk mempercepat waktu muat halaman.
4. **CSS Animations Performance**: Pelajari cara meningkatkan kinerja animasi CSS dengan memanfaatkan GPU dan membatasi repaints dan reflows.
5. **CSS Framework Authoring**: Pahami cara membuat framework CSS sendiri untuk kebutuhan proyek khusus atau untuk kontribusi ke komunitas.
6. **Cross-browser Compatibility**: Pelajari teknik untuk memastikan konsistensi tampilan antar browser dengan menggunakan vendor prefixes dan polyfills.

Setiap tahap membutuhkan latihan yang konsisten dan proyek nyata untuk menerapkan apa yang telah dipelajari. Juga, jangan ragu untuk terus mengikuti perkembangan terbaru dalam CSS dan teknologi web untuk tetap relevan. Semoga roadmap ini membantu!



## RANGKUMAN MATERI BELAJAR CSS :
- VARIABEL dalam CSS 
    DI dalam css variabel di definisikan sebagai 
    :root{
    --warnakesukaan: #4aca17;}
    root berarti untuk global ( seluruh element html )
    --warna kesukaan sebagai nama variabel 
    aturanya definisi root hanya ada 1 dan tidak boleh ada 2 jika ada 2 yang terbaca adalah bagian yang bawah atau yang terahir
    keudian cara memangginya cuku dengan **var(--nama_variabel )**
    contoh pengunaan 

    h1 {
    color: var(--warnakesukaan);
    }

- TRANSFORM = transform: fungsi() ;

   transform adalah salah satu properties css, sudut utama x + y di mulai dari sudut kiri atas 
   memiliki 5 fungtion dan dapat di kombinasikan dengan sudut x y dan z(3d)
    - rotate : rotate(10deg)
        fungsi ini akan memutar object, selain "deg" bisa mengunakan satuan derajat lain seperti
        - deg = 1 deg berarti 1 derajat 
        - turn = 360 derajat artinya 1trun akan memutar object kembali ke semula
        - grad = sama dengan deg aritunya 1 grad sama dengan 1 derajat
        - rat = setara 50 derajat 
        selain memutar searah atau berlawana jarum jam kita juga bisa memutar ke depan dan ke belakang dengan menambahkan fungsi x = rotatex yang bisa langsung di masukan ke dalam fungsi 
        contoh 
        - transform : rotatex(10deg)
        kita juga bisa mengunakan sumbu y untuk memutar elemet kanan ke kiri dengan cara menambahkan y pada fungsi : rotatey contohnya 
        - transform : rotatex(10deg)
    - scale : scale(0.5);
        fungsi dari scale mengubah ukuran dari suatu object,
        untuk membesarkan object ke samping atau menarik ke samping bisa mengunakan x : scalex
        untuk membesarkan object ke atas bawahg bisa mengunakan y : scaley
        bisa juga di gabungkan menjadi 3d : scale3d
    - translate : translate(10px) 
        di gunakan untuk mengatur posisi element pada halaman untukk mengatur ke bawah atau samping bisa mengunakan sumbu x dan y (stranslatex dan translatey) sebagai patokan
        bisa juga mengunakan 3d (translate3d) 
    - skew : memiringkan element dalam bentuk 2D
    - matrix : tidak terlu berguna | tidak tau juga fungsinya

- TRANSFORM ORIGIN : transform-origin: fungsi();
   property transform ini di gunakan untuk mengatur posisi awal titik pusat atau x y z, jadi kita tau bahwa property transform itu selalu memiliki posisi titik awal di sudut kir atas elementnya transform origin ini di gunakan untuk mengubah posisinya dengan fungsi berikut :
   - top
   - center
   - right
   - left
   - bottom
  dari ke 4 posisi itu dapat di kombinasikan sesuka user sebagai contoh 
   - transform-origin: center left;
   - transform-origin: bottom left;
   kemudian bisa juga di mengunakan ukuran px agar sesuai dengan keinginan user dengan cara menentukan sudut x dan y nya :
   - transform-origin: 10px 90px;
- TRANSFOR STYLE : transform-style: funsi; 
  cara kerjanya dapat membuat 2 atau lebih element menjadi satu cara kerjanya mirip mirip dengan section, ada 2 fungsi untama dalam property ini yaitu :
   - transform-style: flat; 
     fungsinya sangat mirip dengan section di mana ini dapat menyatukan 2 element dalam bentu 2D sederhananya di sebuah element kita ingin membentuk sebuah bagian tersendiri dengan box dan latar putih kemudian kita ingin menambahkan bulat bulatan kecil di dalam box tersebut kode ini adalah kode yang sesuai 

    .parent{transform-style: flat;}
    <div class="parent">
        <div class="child">
            Child Element
        </div>
        .....
        semua yang di tulis di dalam sini akan berada di dalam kelompok ini
    </div>

    dalam kode di atas jika kita mengatur div class="parent" sebagai transform-style: flat; di css maka semua element yang di tulis di dalamnya berada di dalam div class="parent"
  - transform-style: preserve-3d; 
    inti penjelasanya sama saja dengan  flat cuman bedanya ini dapat membentuk 3D dimana element kedua atau element anak dapat berada di belakang element utama baik setengah atau seluruh element tergantung pengkondisian dari user 

- OVERFLOW : overflow: fungsi;
  overflow biasanya di gunakan untuk memberi batasan area di dalam tampilan web, cara kerjanya mirip mirip dengan section dan transform-style untuk fungsi, overflow akan membuat sebuah bagian bagian di website yang berisi konten web biasanya bentuknya kotak kotak pada area web yang berisikan text atau element lain untuk mengunakan element ini biasanya harus di gabungkan dengan property width, height, boreder, dan lainya agar mendapat tampilan yang lebih menarik contoh kodenya bisa di lihat di bawah ini :
      .container {
        width: 200px;
        height: 200px;
        overflow: auto;
        border: 1px solid black;
      
    }
    <div class="container">
    <p>
    buat lebih panjanh
    </p>
    </div>

  kode di atas akan menghasilkan sebuah box yang berisi element paragraf, namun ketika isi konten semakin banyak box tidak akan merubah ukuranya di karnakan telah di tetapkan sebelumnya 
  untu property overflow memiliki 4 fungtion yaitu : 
    - overflow: hidden; : membuat isi konten tersebunyi jika melebihi area yang di tetapkan dan tidak memiliki tombol scrol
    - overflow: visible; : 