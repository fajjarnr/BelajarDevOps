## Plan > Code > Build > Testing > Release > Deploy > Operate > Monitor >

### Plan

Tahap Plan akan mencakup semua perencanaan dan perancangan dari sebuah aplikasi yang akan dikembangkan. Biasanya pada tahap ini seorang Project Manager yang akan memimpin. Semua aturan, persyaratan, dan feedback dari stakeholders atau project owner dan bahkan user akan dikumpulkan, dan akan digunakan untuk membuat roadmap project. Tools yang umumnya digunakan untuk melakukan tracking diantaranya ada Asana, Jira, ClickUp, dan lain sebagainya.

### Code

Pada tahap ini developer akan mulai menuliskan code dari aplikasi yang dibangun. Untuk tools yang digunakan pun ada banyak salah satunya yang populer adalah VSCode. Setelah developer menuliskan code, kemudian mereka melakukan push atau proses menyimpan code ke sebuah repository terpusat, salah satunya adalah Github.

### Build

Selanjutnya setelah code di-push ke repository akan dilakukan build. Build disini bermaksud mengubah code dari developer menjadi sebuah aplikasi. Biasanya sebelum melakukan build, developer lain akan melakukan diskusi untuk mendapatkan feedback dan review terhadap code. Setelah selesai melakukan diskusi selanjutnya adala melakukan build aplikasi. Build aplikasi bisa menggunakan berbagai macam tools tergantung dari aplikasi yang dibuat, jika dibuat menjadi image maka Docker dapat digunakan. Atau juga dibuat menjadi compressed file (zip, jar, dan lain-lain).

### Testing

Tahapan berikutnya adalah melakukan Testing pada aplikasi yang di-build. Apakah aplikasi yang dibuat memenuhi kriteria atau tidak, secara fungsional berjalan dengan semestinya atau tidak, secara desain, dan sebagainya. Apabila ternyata tidak sesuai maka akan berhenti ditahap ini dan melakukan perbaikan. Namun apabila sudah sesuai maka selanjutnya adalah Release.

### Release

Pada tahap Release aplikasi yang sudah lolos dari tahap Test akan diberikan label atau nomor versi. Kapan aplikasi tersebut dirilis, apa saja perubahan yang dilakukan, dan pada tanggal berapa dilakukan release, sebelum akhirnya aplikasi tersebut akan di-deploy.

### Deploy

Deploy adalah proses dimana aplikasi yang dibuat ditempatkan atau disebarkan, dan akhirnya bisa diakses oleh user. Salah satu tools yang digunakan adalah AWS CodeDeploy, Jenkins, dan sebagainya.

### Operate

Pada tahap Operate, tim Operation akan memastikan aplikasi dan infrastruktur berjalan sebagaimana mestinya. Dan juga mengambil data performance, errors, dan sebagainya. Apabila ternyata ada berupa kesalahan atau bug, user pun dapat memberikan feedback yang nantinya akan menjadi sebuah patokan untuk melakukan pengembangan dari aplikasi.

### Monitor

Monitor adalah tahap terakhir dari DevOps Lifecycle. Dari tahap sebelumnya sudah dikumpulkan berupa data performance, error, atau bahkan feedback. Dari data-data tersebut bisa dilakukan introspeksi atau evaluasi dari aplikasi yang dikembangkan. Bahkan juga dapat dilakukan monitor untuk pipeline yang dibuat, apakah kedepannya akan terjadi bottlenecks yang dapat menghambat produktivitas pengembangan aplikasi.

### Repeat

Selanjutnya kembali ke tahap awal perencanaan dan mengulangi semuanya lagi.

### Continuous Delivery

Continuous Delivery = Plan > Code > Build > Test

### Continuous Integration

Secara efektif merupakan hasil dari fase Continuous Delivery di atas ditambah hasil dari fase Rilis. Jika prosesnya gagal kembali ke proses Continuous Delivery dan jika berhasil dipindahkan ke Continuous Deployment.

Continuous Integration = Plan > Code > Build > Test > Release

### Continuous Deployment

Continuous Integration proses rilis berhasil = Continuous Deployment = Deploy > Operate > Monitor
