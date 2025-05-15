<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <title>Uzay Tavugu</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background: black;
    }
    canvas {
      display: block;
      margin: 0 auto;
      background: #000022;
    }
  </style>
</head>
<body>
  <canvas id="gameCanvas" width="800" height="600"></canvas>
  <script>
    const canvas = document.getElementById('gameCanvas');
    const ctx = canvas.getContext('2d');

    const tavuk = {
      x: 400,
      y: 500,
      width: 40,
      height: 40,
      color: 'yellow',
      speed: 5
    };

    const yildizlar = [];
    let skor = 0;

    function rastgeleYildiz() {
      return {
        x: Math.random() * (canvas.width - 20),
        y: -20,
        size: 20,
        color: 'white',
        speed: 2 + Math.random() * 2
      };
    }

    function cizTavuk() {
      ctx.fillStyle = tavuk.color;
      ctx.fillRect(tavuk.x, tavuk.y, tavuk.width, tavuk.height);
    }

    function cizYildizlar() {
      for (let yildiz of yildizlar) {
        ctx.beginPath();
        ctx.arc(yildiz.x, yildiz.y, yildiz.size / 2, 0, Math.PI * 2);
        ctx.fillStyle = yildiz.color;
        ctx.fill();
        ctx.closePath();
      }
    }

    function guncelleYildizlar() {
      for (let i = yildizlar.length - 1; i >= 0; i--) {
        yildizlar[i].y += yildizlar[i].speed;

        if (
          yildizlar[i].x < tavuk.x + tavuk.width &&
          yildizlar[i].x + yildizlar[i].size > tavuk.x &&
          yildizlar[i].y < tavuk.y + tavuk.height &&
          yildizlar[i].y + yildizlar[i].size > tavuk.y
        ) {
          yildizlar.splice(i, 1);
          skor++;
        } else if (yildizlar[i].y > canvas.height) {
          yildizlar.splice(i, 1);
        }
      }
    }

    function cizSkor() {
      ctx.fillStyle = 'white';
      ctx.font = '20px Arial';
      ctx.fillText('Yildizlar: ' + skor, 10, 30);
    }

    function oyunDongusu() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      if (Math.random() < 0.03) yildizlar.push(rastgeleYildiz());
      guncelleYildizlar();
      cizYildizlar();
      cizTavuk();
      cizSkor();
      requestAnimationFrame(oyunDongusu);
    }

    document.addEventListener('keydown', (e) => {
      if (e.key === 'ArrowLeft' && tavuk.x > 0) tavuk.x -= tavuk.speed;
      if (e.key === 'ArrowRight' && tavuk.x + tavuk.width < canvas.width) tavuk.x += tavuk.speed;
    });

    oyunDongusu();
  </script>
</body>
</html>
