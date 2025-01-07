<html>
  <head>
    <meta charset='UTF-8'/>
    <meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/>
    <meta content='IE=edge' http-equiv='X-UA-Compatible'/>
    <link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap" rel="stylesheet"><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script><link href="https://Bbyy.feeldream.repl.co/style.css" rel="stylesheet" type="text/css" /><script src="https://Bbyy.feeldream.repl.co/script.js"></script>
    <title>Script HTML Bucin Buat Pacar</title>
  </head>
  <body>
    <div id="bodyblur">
      <img id="wallpaper" src="" width="100%" height="100%"/>
    </div>
    <div id='Content'><p id="idgeser"></p>
      <div>
        <blockquote id='bq'>
          <img id="foto1" src=""/>
          <img id="foto2" src=""/>
          <img id="foto3" src=""/>
          <img id="foto4" src=""/>
          <img id="foto5" src=""/>
          <img id="foto6" src=""/>
          <p id="katakata"></p>
          <p id="katabawah"></p>
        </blockquote>
      </div>

      <div id="contTom" style="display:none;">
        <a id="By" class='button' onClick="terima()"></i>Lanjut</a><b id='buttonv2'></b><a id="Bn" class='button' onClick="tolak()"></i>Engga</a>
      </div>
    </div>

    <script>
      const body = document.querySelector("body");
      function createHeart() {
        const heart = document.createElement("div"); 
        heart.className = "fas fa-heart"; 
        heart.style.left = (Math.random() * 90)+"vw"; 
        heart.style.animationDuration = (Math.random()*3)+2+"s"; 
        body.appendChild(heart);
      } 
      setInterval(function name(params) {
        var heartArr = document.querySelectorAll(".fa-heart"); 
        if (heartArr.length > 100) {heartArr[0].remove()}
      },100);
    </script>
    <script>
      function nonFo() {
        document.getElementById('idfoto').style.display = "none";
      } 
      function showFo() {
        document.getElementById('idfoto').style.display = "block";
      }
      function nonDiv() {
        document.getElementById('Content').style = "opacity:0;visibility:hidden;margin-top:30vh;";
      } 
      function showDiv() {
        Bn.style="display:none";
        setTimeout(kpemb,100);
        document.getElementById('Content').style = "opacity:1;margin-top:4vh;animation:kont 3s infinite;";
        document.getElementById("katakata").innerHTML = kata1;
      }
      function loadfoto() {
        document.getElementById('foto1').src = gambar1;
        document.getElementById('foto2').src = gambar2;
        document.getElementById('foto3').src = gambar3;
        document.getElementById('foto4').src = gambar4;
        document.getElementById('foto5').src = gambar5;
        document.getElementById('foto6').src = gambar6;
      }
      function showAkhir() {
        setInterval(createHeart,200);
        document.getElementById('k2').style = "opacity:1;transform:scale(1);margin:0;";
        document.getElementById('ftdua').style = "transform:scale(1);";
        document.getElementById('final1').style = "transform:scale(1);";
        document.getElementById('Content').style.display = "none";
      }
      function mulaiakhir() {
        nonDiv();
        setTimeout(showAkhir,1400);
        setTimeout(finalis,2400);
      }
      function showTom() {
        document.getElementById('idkirim').style = "opacity:1;visibility:visible;margin-top:140px;";
      } 
      function tombol(){
        contTom.style="display:flex";
      }
      function otomatis() {
        befanimkata();setTimeout(animkata,400);
        contTom.style="display:none";
        setTimeout(tombol,1200);
      }
      function befanimkata(){
        katakata.style="transform:scale(.01);";
        katabawah.style="transform:scale(.01);";
      } 
      function animkata() {
        katakata.style="transform:scale(1);";
        katabawah.style="transform:scale(1);";
      }
  
      async function terimateks(){
        By.innerHTML = "Mau";Bn.style="display:flex";
        
