<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>منظمة تمكين للتنمية البشرية</title>
  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    body{
      margin:0;
      font-family:'Tajawal',sans-serif;
      background:#f8fafc;
      color:#1f2933;
    }
    header{
      background:#ffffff;
      padding:15px;
      text-align:center;
      box-shadow:0 4px 15px rgba(0,0,0,0.05);
    }
    header img{max-height:65px;}
    .hero{
      padding:50px 20px;
      text-align:center;
      background:url('https://images.unsplash.com/photo-1521737604893-d14cc237f11d') center/cover no-repeat;
      color:#fff;
    }
    .hero h1{font-size:26px;margin-bottom:10px;}
    .hero p{font-size:15px;background:rgba(0,0,0,0.5);padding:10px;border-radius:12px;}
    section{padding:50px 20px;}
    .title{text-align:center;margin-bottom:35px;}
    .title h2{font-size:22px;color:#1b4965;}
    .card{
      background:#ffffff;
      border-radius:18px;
      padding:25px 20px;
      margin-bottom:25px;
      box-shadow:0 15px 30px rgba(0,0,0,0.06);
      text-align:center;
      cursor:pointer;
    }
    .card img{width:100%;border-radius:14px;margin-bottom:15px;}
    .card i{font-size:36px;color:#3a86b8;margin-bottom:10px;}
    .card .more{display:none;font-size:14px;color:#4b5563;margin-top:10px;}
    footer{
      background:#1b4965;
      color:#fff;
      text-align:center;
      padding:25px 15px;
      font-size:14px;
    }
  </style>
</head>
<body>

<header>
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjsZVpOEadqvq-4tHSC31H1qtFlGBa6GX6KwPKVSyX38F8_LTNyzrJlpwgi5MeZWUS_hUmpU06ZRRtH77sVCUCXtbThN9erRaFHkw3ndhfbCuZuXOPfL7iqChcUDfTDU66Tf5s1jQ5Pe3c4hriFqnJVQ8ZW6R4RDFM6H81_5jSGKbk9t5xux9MnD5VHbfc/s320/Photoroom_20260201_1322533.png" alt="شعار منظمة تمكين" />
</header>

<div class="hero">
  <h1>منظمة تمكين للتنمية البشرية</h1>
  <p>نحو إنسان واعٍ ومجتمع قادر على التنمية المستدامة</p>
</div>

<section>
  <div class="title"><h2>من نحن</h2></div>
  <div class="card">
    <img src="https://images.unsplash.com/photo-1523580846011-d3a5bc25702b" />
    <p>منظمة تنموية تعمل على تطوير الإنسان وبناء قدراته عبر برامج نوعية.</p>
  </div>
</section>

<section>
  <div class="title"><h2>رؤيتنا ورسالتنا</h2></div>
  <div class="card"><i class="fa-solid fa-eye"></i><h3>الرؤية</h3><div class="more">مجتمع متمكن يمتلك المعرفة والمهارة.</div></div>
  <div class="card"><i class="fa-solid fa-bullseye"></i><h3>الرسالة</h3><div class="more">تمكين الإنسان من خلال التدريب والتنمية.</div></div>
</section>

<section>
  <div class="title"><h2>برامجنا</h2></div>
  <div class="card"><img src="https://images.unsplash.com/photo-1552664730-d307ca884978" /><h3>التدريب</h3><div class="more">ورش ودورات لبناء القدرات.</div></div>
  <div class="card"><img src="https://images.unsplash.com/photo-1509099836639-18ba1795216d" /><h3>التمكين المجتمعي</h3><div class="more">مبادرات إنسانية وتنموية.</div></div>
</section>

<footer>
  © 2026 منظمة تمكين للتنمية البشرية
</footer>

<script>
  document.querySelectorAll('.card').forEach(c=>{
    c.addEventListener('click',()=>{
      const m=c.querySelector('.more');
      if(m) m.style.display=m.style.display==='block'?'none':'block';
    });
  });
</script>

</body>
</html>
