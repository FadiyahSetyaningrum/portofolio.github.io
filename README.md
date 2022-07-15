# portofolio.github.io
echo "# portofolio.github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/FadiyahSetyaningrum/portofolio.github.io.git
git push -u origin main
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" type="text/css" href="style.css"
    <title>Website Portofolio</title>
</head>
<body id="body">
    <ul class="nav" id="Topnav">
      <li><a href="#">FS</a></li>
      <li><a href="#about">About Me</a></li>
    </ul>
  
    <div class="container container-fd" id="fs">
      <div class="row">
        <div class="col-aip-2"></div>
        <div class="col-aip-8">
        </div>
        <div class="col-aip-2"></div>
      </div>
      <div class="box-container">
        <div class="name">
          <h2>Fadiyah Setyaningrum</h2>
          <br><a href="#" class="fa fa-facebook"></a>
          <a href="#" class="fa fa-twitter"></a>
          <a href="#" class="fa fa-google"></a>
          <a href="#" class="fa fa-instagram"></a>
        </div>
        <div class="img">
          <img src="img.png" alt="">
        </div>
      </div>
    </div>
    <div class="about">
      <div style=" " id="about"></div>
      <div class="about-text ">
          <p>About Me</p>
          <center>Profil tentang saya di bawah ini hanya sebagian yang tertera</center>
      </div>
       
      <div class="box-container">
          <div class="box-1">
              <span>1</span>
              <p class="heading">Biodata Diri</p>
              <p class="details">Nama : Fadiyah Setyaningrum  
                Alamat : Graha Elysia, Banjararum 
                TTL : Malang, 28 November 2001 
                Jenis Kelamin : Perempuan</p>
          </div>
          <div class="box-2">
              <span>2</span>
              <p class="heading">Pendidikan</p>
              <p class="details">2020-Sekarang : Berkuliah di Universitas Merdeka Malang Jurusan S1 Sistem Informasi Angkatan 2020</p>
          </div>
          <div class="box-3">
              <span>3</span>
              <p class="heading">Hobi</p>
              <p class="details">Menulis puisi, cerpen dan novel, berolahraga, dan membuat desain seperti poster dan banner</p>
          </div>
      </div>
  </div>
    <footer class="my-footer">
      <p style="padding: 10px;">Copyright - 2020 - Fadiyah Setyaningrum</p>
    </footer>
  
  </body>
  
  </html>
