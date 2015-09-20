# oemoticon
Menambahkan Emoticon Kaskus Pada Blogger/Blogspot

Pertama, pergi ke dashboard, pilih Tata Letak, lalu edit HTML copy ini berikut kode JavaScript ke template HTML Anda, tepat sebelum </ head>:

<!-- <script src='https://raw.githubusercontent.com/oemunix/oemoticon/master/oemoticon_kaskus.js' type='text/javascript'></script> -->

Kedua, tambah kode javascript dibawah ini sebelum kode </html>

<!--
<script type='text/javascript'> 
addSmileyById('comments-block');
addSmileyByClass('entry-content');
</script> 
-->

ket :

comments-block adalah selector id dari css #comments-block

entry-content adalah selector class dari css .entry-content


silahkan sesuaikan dengan template blogger sobat !

sumber : https://sites.google.com/site/gman/blogger/emoticon
