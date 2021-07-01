<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta new="keyword" content="HTML CSS"/>
    <meta name="description" content="Programming">


    <link rel="stylesheet" href="css/global.css">
    <link rel="stylesheet" href="css/main.css">

    
    <link rel="stylesheet" media="(max-width:768px)" href="css/tablet.css">

    <link rel="stylesheet" media="(max-width:580px)" href="css/mobile.css">


<!-- Google Fonts-->
 
    <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">


<!-- Font awesome-->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">


    
    <title>Seydi Saritas</title>
</head>
<body>
    

<header class="bg-dark-blue">
    <div class="container">


        <nav id="navbar">

            <h1 class="heading-small">seydi sarıtaş</h1>
            
            <ul>
                <li><a href="#home">Anasayfa</a></li>
                <li><a href="#training">Eğitimler</a></li>
                <li><a href="#courses">Kurslar</a></li>
                <li><a href="#contact">İletişim</a></li>
            
            </ul>
            
            </nav>

    </div>



</header>

<section id="home">
    <img src="./images/cover-68729.jpg" alt="Foto">


    <div class="name text-center">
        <h2 class="heading-big">seydi sarıtaş</h2>
        <p>Founder of nothing</p>
    </div>
    
    <a href="#courses" class="btn btn-primary">Kurslara git</a>


</section>

<section id="training" class="bg-dark-blue">

<h3 class="text-center heading-medium">Eğitimler</h3>
<div class="items">
<article class="item">
    <i class="fa fa-pencil-alt"></i>

    <h3>Sınıf içi eğitimler</h3>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Incidunt, id.</p>
</article>

<article class="item">
    <i class="fa fa-pencil-alt"></i>
    
    <h3>Online İçerikler</h3>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Incidunt, id.</p>
</article>

<article class="item">
    <i class="fa fa-pencil-alt"></i>
    
    <h3>Konferanslar</h3>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Incidunt, id.</p>
</article>

</div>

</section>


<section id="courses">
    <h3 class="text-center heading-medium">Kurslar</h3>

    <div class="container">
      <div class="courses">
        <!-- Course 1 -->
        <div class="course">
          <div class="course-image">
            <img src="images/python.jpg" alt="Python" />
            <span>%90 İndirim</span>
          </div>

          <div class="course-info">
            <div class="title">
              (40+ Saat) Python | Sıfırdan İleri Seviye Programlama (2020)
            </div>
            <div class="description">
              (40+ Saat) Python | Sıfırdan İleri Seviye Programlama (2020)
            </div>
            <div class="instructor">Mustafa Murat Coşkun,Yazılım Bilimi</div>
            <div class="rating">4.6 | (19990 Oylama)</div>
          </div>
        </div>
        <!-- Course 2 -->
        <div class="course">
          <div class="course-image">
            <img src="images/java.jpg" alt="Java" />
            <span>%90 İndirim</span>
          </div>

          <div class="course-info">
            <div class="title">
              Komple Java Geliştirici Kursu
            </div>
            <div class="description">
              Komple Java Geliştirici Kursu | Sıfırdan Java Öğrenin
            </div>
            <div class="instructor">Mustafa Murat Coşkun,Yazılım Bilimi</div>
            <div class="rating">4.6 | (7000 Oylama)</div>
          </div>
        </div>

        <!-- Course 3 -->
        <div class="course">
          <div class="course-image">
            <img src="images/javascript.jpg" alt="JavaScript" />
            <span>%90 İndirim</span>
          </div>

          <div class="course-info">
            <div class="title">
              Komple Modern JavaScript Kursu
            </div>
            <div class="description">
              Komple Modern JavaScript Kursu - ES6+
            </div>
            <div class="instructor">Mustafa Murat Coşkun,Yazılım Bilimi</div>
            <div class="rating">4.7 | (2000 Oylama)</div>
          </div>
        </div>
      </div>
    </div>
  </section>


  
  
  <footer id= "contact" class="bg-dark-blue">
    <div class="contact-form">
        <form>
            
<h4 class="text-center heading-medium">Bana ulaşın</h4>

<div class="form-group">

    <label for="name">İsim</label>
    <input type="text" class="form-control" name="name" id="name" placeholder="İsim">
</div>

<div class="form-group">

    <label for="email">Email</label>
    <input type="text" class="form-control" name="email" id="email" placeholder="E-mail">
</div>


<div class="form-group">

    <label for="message">Mesaj</label>
    <textarea name="message" class="form-control" name="message" id="message" placeholder="Mesajınız"
    rows="5"></textarea>
</div>


<button type="submit" class="btn btn-block">
    Gönder
</button>

        </form>

        <ul>
            <li><a href="#"><i class="fab fa-facebook"></i> </a>
                <li><a href="#"><i class="fab fa-twitter"></i> </a>
                    <li><a href="#"><i class="fab fa-instagram"></i> </a>
            
            
            </li>
        </ul>


    </div>

  </footer>

</body>
</html>
