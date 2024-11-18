# Materi

### HTML
---
#### HTML Basic Structure
HTML terdiri dari dua elemen , header dan body.
untuk menambahkan elemen pada HTML adalah dengan menggunakan tags, tags menunjuk fungsinya secara spesifik. Tags harus mencakup start tag di depan content dan end tag dibelakang content.

#### Basic Elements
- <h5> Headings <h5> 
Untuk headings yang tersedia adalah h1, yang merupakan heading yang paling penting atau paling besar, lalu ada h6 yang merupakan heading yang terkecil. Heading dapat diberi attribut khusus.

- <h5> Paragraph <h5>
Paragraph ditandai dengan tag p. Paragraph tidak mendapatkan formatting khusus seperti heading, Hanya nampak seperti teks pada umumnya.

- <h5> Links 
Links atau bisa juga disebut hyperlink adalah element yang ketika diklik dapat mengarahkan kepada sebuah webpage atau page section. Tapi di HTML link dapat di buat menjadi teks sesuai keinginan. Saat di mode tampil, link ditandai dengan garis bawah dan umumnya warna teks biru atau ungu. Tag yang digunakan adalah a dengan atribut penunjuk href.


<h6> Note: <br>
- <b> Tags <b> adalah penanda yang diberikan khusus untuk membuat sebuah elemen, dan isinya adalah content. <br> <br>
- <b> Attributes<b> adalah atribut atau pengaturan tambahan yang dapat kita tambahkan kedalam tags untuk mengatur stylingnya, sehingga lebih unik

#### Styling Attribute
Kita dapat mengatur beberapa pengaturan styling dengan atribut "style", yang bisa memuat beberapa pengaturan diantara lain:
- Background Color
- Text Color
- Font
- Text Size
- dan lain lain..

#### Styling Tags
Kita dapat menambahkan tag pada teks yang kita buat dengan beberapa tag sebagai berikut.

b - Membuat Teks menjadi bold
strong - Hampir sama seperti bold
i - Membuat teks menjadi italic atau miring
em - Miring dan Bold
mark - Menambahkan highlight pada teks 
small - Menjadikan teks kecil


## Media
Dalam HTML kita dapat menambahkan beberapa jenis media yaitu 

- <h5> Images
Kita bisa menambahkan image pada web page HTML kita dengan dua langkah, menambahkan tag lalu mencantumkan src untuk mencari sumber gambar. Lalu kita juga bisa menambahkan attribut tambahan seperti alt untuk alternative text dan mengatur width serta height nya. 

- <h5> Video 
Dengan menambahkan video pada web page HTML kita dengan dua langkah, menambahkan tag lalu mencantumkan src untuk mencari sumber video format mp4. Lalu disini kita bisa menambahkan atribut seperti "autoplay" untuk memutar video secara otomatis dan "mute" 
untuk membisukan video kecuali user mematikan mute nya. Berbeda dari images, untuk video kita memisahkan media tag dengan source tag seperti ini;

video width="320" height="240" controls>
  source src="movie.mp4" type="video/mp4"
  source src="movie.ogg" type="video/ogg"
/video

- <h5> Audio
Sama seperti video , kita dapat membuat audio dengan menambahkan tag audio lalu tag source secara terpisah. Di audio (juga di video) kita bisa menambahkan attribut control. Untuk audio ini mensupport berbagai jenis file audio.
Misalnya wav, mp3, aac, ogg dan lain lain.

### CSS
---
CSS atau Cascading style sheet adalah sebuah bahasa scripting yang digunakan secara khusus untuk styling elemen pada HTML. Dalam CSS ada selector, yang merupakan elemen yang akan kita styling misalnya h1 adalah selector untuk heading, lalu ada properti dan value, properti adalah jenis stylingnya sedangkan value adalah nilai dari properti.
#### Basic Styling 
disini saya akan membahas 4 Styling pada CSS.
- Color dan Background Color
Dalam mengoding CSS kita dapat memberikan warna dengan dua value, yaitu value dalam HEX, RGB , HSL, RGBA, HSLA dan dengan nama bahasa inggris dari warna tersebut.
HEX misalnya #ff6347, dan warna misalnya "tomato" akan memberikan warna merah tomat. Lalu kita bisa merubah background color. Ini dapat kita terapkan ke elemen HTML seperti
section, box, atau div. 
- CSS Text Color
Dalam CSS kita bisa memberikan warna tertentu pada teks. Pertama kita memberitahu tag elemen teks yang dituju. Lalu memberikan properti dan valuenya "color: green". Kita juga bisa memberikan semacam highlighter misalnya "background-color: yellow"
- CSS Text Formatting
Text Formatting merubah bentuk text menjadi misalnya mau diberi garis bawah atau dijadikan kapital, memberi garis dengan "text-decoration" dan menjadikan kapital dengan "text-transform".
- CSS Font dan Font Family 
Font Family adalah kelompok font atau typeface yang memiliki style language yang sama. Kita dapat mengganti font pada teks yang akan kita tuju.
misal untuk menentukan font family = "font-family: "Times New Roman", Times, serif;"
Adapun kalau anda ingin menggunakan satu font spesifik maka bisa menggunakannya seperti ini" font: 20px Arial, sans-serif;"

Dalam CSS kita dapat menggunakan Bootstrap, yang merupakan salah satu Framework dari CSS. Framework sendiri adalah kerangka kerja yang menyediakan struktur dasar dan komponen-komponen siap pakai untuk memudahkan dan mempercepat proses pengembangan aplikasi/website. 

### JS
---
JS atau JavaScript adalah jenis bahasa yang dapat mengubah content dari HTML. Ini membuat bahasa ini dapat mengembangkan fungsional dari HTML. 

Sintaks JavaScript mendefinisikan dua jenis nilai:
yaitu Nilai tetap disebut Literals(let) sedangkan nilai variabel disebut Variabel(var).

Framework Bootstrap memiliki beberapa fungsi yang menggabungkan fungsionalitas CSS dan JavaScript untuk mempermudah membangun website. Walaupun JavaScript memiliki beberapa Framework misalnya React.js, Vue.js, Angular dan lain lain.


## Mengapa kita memerlukan <br> HTML, CSS, dan JS
---
W3School memberikan 3 Pillar dari Pemograman Web
   1. HTML yang digunakan untuk membangun konten dalam web page

   2. CSS kita gunakan untuk mengatur tata letak dari elemen-elemen pada website

   3. JavaScript untuk mengendalikan tindakan dari web page.

Kita bisa membayangkannya begini:
Jika Pemograman Web adalah seorang manusia maka HTML adalah kerangka atau tulangnya, lalu CSS akan menjadi kulit, rambut yang membentuk penampilannya, dan JS akan mengatur perilaku dan sifatnya.

Masing-masing memiliki fungsi yang penting dan esensial dalam pemograman web.


## Bagaimana cara mengimplementasikan <br>HTML, CSS dan JS
---

### HTML
HTML dapat di buat struktur basic nya menggunakan DOCTYPE HTML, ada sebuah shortcut di vscode yang dimana jika anda mengetik tanda seru '!' lalu tekan tab maka akan jadi struktur head dan body. Oh Ya HTML terbentuk atas struktur head dan struktur body. Dua duanya harus ada. 
Lalu sebelum head kita harus menyebutkan "meta charset yang biasanya UTF-8" lalu "meta name dan content", kemudian title atau judul website dan langkah opsional, anda bisa menyertakan css atau JS dengan memasukkan link tujuan pada link rel


### CSS
CSS dapat di-inisialisasi dengan 3 cara diantaranya;
- Inline CSS : adalah memasukkan styling langsung kedalam tag dengan menggunakan attribut styling.

- Internal CSS : adalah membuat blok kode (umumnya berada di bagian atas program) yang dikutip dalam tag style. Biasanya dalam menggunakan teknik ini diperlukan untuk menjadikan elemen-elemen menjadi sebuah class
yang nanti class ini kita tuju untuk mengatur styling pada blok style nya. Cara menununjuk suatu class misal (.classcontoh {attribut})

- External CSS : Ini adalah cara dimana kita menggunakan file external seperti style.css misalnya, untuk menjadi file rujukan untuk styling sebuah html. Sehingga file HTML lebih bisa difokuskan mengandung fungsi-fungsi HTML saja. 
Namun dengan catatan bahwa sama seperti internal CSS, untuk External, elemen yang mau diberikan styling harus diberi attribut class nya juga.  Dalam penggunaan external CSS, Anda harus memberikan link yang menghubungkan ke file CSS. 

### JS
untuk membuat Internal JS kita memasukkan blok code program js didalam tag script.