+++
title =  "Tahun Baru, Blog Baru"
date = "2019-02-09"
tags = ["blog", "ssl", "github pages", "cloudflare"]
+++


Tidak terasa sudah setahun dari terakhir kali saya menulis [blog](https://medium.com/dotnetid/membuat-chatbot-apps-menggunakan-bot-framework-dan-xamarin-f3aaad3f283). Saya selalu membuat resolusi saya tiap awal tahun untuk menulis terus, tetapi saya selalu menemukan alasan untuk tidak melakukannya. Saya tidak tahu kenapa saya sendiri selalu malas untuk menulis blog.

## Lalu kenapa menulis blog lagi?

Mari kita _flash back_ terlebih dahulu kenapa saya ingin menulis blog. Saya selalu menikmati belajar sesuatu yang baru dan selalu ingin membagikannya. Saya terkadang berbicara di depan umum dan merasa bahagia untuk bisa berbagi pengetahuan saya kepada rekan-rekan _developer_ (meskipun saya selalu merasa gugup ketika berbicara di depan umum, bahkan sampai sekarang). Tetapi berbicara di depan umum membutuhkan waktu yang sangat banyak dan kita tidak bisa melakukannya tiap hari. Kita harus mencari peserta, menyiapkan isi pembicaraan, dan berlatih tiap hari sehingga kita tidak aneh ketika sudah berbicara di depan umum. Itulah kenapa kemudian saya menulis blog. Menulis blog itu tidak membutuhkan waktu yang banyak, kita bisa menulisnya kapanpun kita mau, kita tidak perlu mencari peserta, kita hanya perlu membagikannya di media sosial dan orang-orang bisa membacanya, dan kita juga tidak perlu menghadapi orang-orang dan mengatasi kegugupan.

## Teknologi di balik website ini

Tahun lalu situs web ini menggunakan wordpress dan kemudian untuk blog saya sambungkan ke medium saya. Sekarang saya ingin sesuatu yang berbeda. Saya mencoba beberapa _platform_ blog. Pertama, saya mencoba [ghost](https://tryghost.org) dan kemudian memasangnya di [azure](https://portal.azure.com), namun kemudian saya merasa bahwa hal tersebut terlalu mahal untuk saya kalau saya ingin menggunakan _custom domain_ dan _SSL_, meskipun saya menggunakan _SSL_ yang gratis dari [LetsEncrypt](http://letsencrypt.org/). Saya tidak bisa menghabiskan sekitar ~ IDR 800.000/bulan. Oleh karena itu saya akhirnya mencari solusi lain. Ketika [hugo](https://gohugo.io/) populer, saya pun mencobanya. Ternyata penggunaannya sangat sederhana. Akhirnya pun saya menggunakan hugo untuk blog ini karena mereka juga support multilingual secara _default_. Saya juga ingin menggunakan SSL untuk website ini dan di saat itu saya berpikir kalau saya harus membuatnya lebih sederhana daripada menggunakan LetsEncrypt jadi saya menggunakan [cloudflare](https://www.cloudflare.com) untuk mengatur SSL dan hal-hal lain seperti _caching_. Ternyata hal itu cukup mudah, kita hanya perlu mendaftar di cloudflare dan ganti _nameserver_ untuk mengarah ke cloudflare dan cloudflare akan mengatur sisanya.

## Apa yang akan ditulis di blog ini?

Blog ini kebanyakan akan berisikan tentang pengalaman saya menggunakan Xamarin karena saya adalah Developer Xamarin. Tetapi hanya membahas satu topik akan membosankan bagi saya, dan saya juga tidak memiliki terlalu banyak materi tentang Xamarin. _hehehe..._ Jadi blog ini akan juga berisi tentang pengalaman saya sebagai manusia dan juga teknologi-teknologi lain yang akan saya _explore_ di kemudian hari. Semoga saya bisa konsisten menulis blog **lagi** dan kalian bisa menikmati isi dari blog ini. _Cheers_ :D

