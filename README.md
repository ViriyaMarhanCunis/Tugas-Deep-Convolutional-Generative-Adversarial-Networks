<h1 align="center"> Sentiment Analysis Using Caikit and Hugging Face </h1>
<p align="center"> 
Nama                : Viriya Marhan Cunis
</p>
<p align="center">
Asal Universitas    : Institut Teknologi Batam
  </p>
  <p align="center">
Ini merupakan isi analisis dari salah satu proyek dari Deep Convolutional Generative Adversarial Networks (DCGANs)
</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>
<h2 align="center"> Analisis</h2> 
<p align='center'>
Deep Convolutional Generative Adversarial Networks (DCGANs) merupakan sebuah arsitektur Deep Learning yang menggunakan lapisan konvolusional 
untuk membuat sebuah gambar sintesis

DCGANs menggunakan dua model yang dilatih secara bersama untuk melakukan proses pembuatan gambar sintesis.
Model satu adalah "Generator" yang dilatih untuk membuat gambar yang terlihat senyata mungkin untuk kemudian dimasukkan ke model selanjutnya.
Model kedua adalah "Discriminator" yang dilatih untuk membedakan gambar yang asli dengan gambar yuang buatan.

Selama pealtihan, "Generator" akan menjadi semakin bagus dalam membuat gambar yang nyata, sementara "Discriminator" menjadi semakin bagus dalam membedakan gambar yang asli
dengan gambar buatan. Proses ini akan mencapai puncak tertingginya ketika "Discriminator" tidak bisa membedakan gambar yang asli dengan gambar buatan.

Salah satu contoh dari proyek DCGANs adalah yang berada di repository ini yakni 
"Creating anime characters using Deep Convolutional Generative Adversarial Networks (DCGANs) and Keras"

Dalam notebook ini, saya memperlajari tentang bagaimana cara DCGANs membuat sebuah gambar karakter anime dari hasil pembuatannya. Disini saya juga mempelajari tentang bagaimana cara perhitungan
dalam DCGANs sehingga model dapat melakukan pembuatan gambar serta membedakan gambar yang asli dengan yang buatan.

Berikut merupakan contoh hasil dari 1 kali latihan DCGANs.
<div align="center">
<img src="image/Hasil Latihan.png">
</div>

Bisa dilihat bahwa gambar yang dihasilkan masih memiliki noise sehingga gambar masih terlihat burik dan gampang dibedakan oleh "Discriminator".
Seiring dengan pelatihan, "Generator" akan dapat membuat gambar yang terlihat nyata sehingga "Discriminator" tidak dapar membedakannya dengan gambar aslinya.
</p>