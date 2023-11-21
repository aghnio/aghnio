- 👋 Hi, I’m @aghnio
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
aghnio/aghnio is a ✨ special/*==================== toggle icon navbar ====================*/
let menuIcon = document.querySelector('#menu-icon');
let navbar = document.querySelector('.navbar');


/*==================== scroll sections active link ====================*/
let sections = document.querySelectorAll('section');
let navLinks = document.querySelectorAll('header nav a');

window.onscroll = () => {


    /*==================== sticky navbar ====================*/

    /*==================== remove toggle icon and navbar when click navbar link (scroll) ====================*/
};


/*==================== scroll reveal ====================*/


/*==================== typed js ====================*/
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  border: none;
  outline: none;
  scroll-behavior: smooth;
  font-family: "Poppins", sans-serif;
}

:root {
  --bg-color: #1f242d;
  --second-bg-color: #323946;
  --text-color: #fff;
  --main-color: #0ef;
}

html {
  font-size: 62.5%;
  overflow-x: hidden;
}

body {
  background: var(--bg-color);
  color: var(--text-color);
}

section {
  min-height: 100vh;
  padding: 10rem 9% 2rem;
}

.header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  padding: 2rem 9%;
  background: var(--bg-color);
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 100;
}

.logo {
  font-size: 2.5rem;
  color: var(--text-color);
  font-weight: 600;
  cursor: default;
}

.navbar a {
  font-size: 1.7rem;
  color: var(--text-color);
  margin-left: 4rem;
  transition: 0.3s;
}

.navbar a:hover,
.navbar a.active {
  color: var(--main-color);
}

#menu-icon {
  font-size: 3.6rem;
  color: var(--text-color);
  display: none;
}

.home {
  display: flex;
  justify-content: center;
  align-items: center;
}

.home-img img {
  width: 35vw;
}

.home-content h3 {
  font-size: 3.2rem;
  font-weight: 700;
}

.home-content h3:nth-of-type(2) {
  margin-bottom: 2rem;
}

span {
  color: var(--main-color);
}

.home-content h1 {
  font-size: 5.6rem;
  font-weight: 700;
  line-height: 1.3;
}

.home-content p {
  font-size: 1.6rem;
}

.social-media a {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: 4rem;
  height: 4rem;
  background: transparent;
  border: 0.2rem solid var(--main-color);
  border-radius: 50%;
  font-size: 2rem;
  color: var(--main-color);
  margin: 3rem1.5rem 3rem 0;
  transition: 0.5s ease;
}

.social-media a:hover {
  background: var(--main-color);
  color: var(--second-bg-color);
  box-shadow: 0 0 1rem var(--main-color);
}

.btn {
  display: inline-block;
  padding: 1rem 2.8rem;
  background: var(--main-color);
  border-radius: 4rem;
  box-shadow: 0 0 1rem var(--main-color);
  font-size: 1.6rem;
  color: var(--second-bg-color);
  letter-spacing: 0.1rem;
  font-weight: 600;
}

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>zlatan Website</title>

    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<style>
    body {
      background-image: url('R.jpeg');
      background-repeat: no-repeat;
      background-attachment: fixed;  
      background-size: cover;
    }
</style>
<body>
    <nav>
        <a href="index.html">Home</a> |
        <a href="cv-eko.pdf">Download CV</a> |
        <a href="contact.html">Contact</a> |
        <a href="about.html">About me</a>
    </nav>

    <hr />

    <article>
        <h1>About Me</h1>
        <p>
            Hi, saya adalah salah satu guru di SMK Krian 1 yang mengajar mata pelajaran Pemrograman Web. <br>
            Saat ini sedang belajar HTML di situs Petnai Kode.
        </p>
        <p>
            Saya memang masih baru dalam web development, karena itu
            saya tidak akan pernah berhenti belajar.
        </p>
        <p>
            Saya ingin menguasai bahasa HTML, CSS, dan Javascript.
            Simak video lengkap tentang saya.
        </p>
        <p>
            <!-- <video width="520" height="320" controls>
                <source src="video/video-about.mp4" type="video/webm" width="300">
            </video> -->
            <table>
                <tr>
                    <th>cover</th>
                    <th>Portofolio</th>
                </tr>
                <tr>
                    <td><img src="image/foto.jpg" alt=""></td>
                    <td><a href="index.html">Login</a></td>
                </tr>
                <tr>
                    <td><img src="image/foto.jpg" alt=""></td>
                    <td><a href="contact.html">Blogger</a></td>
                </tr>
            </table>
        </p>
    </article>

   

    <hr>
    <footer style="text-align: center;">
        <p>Copyright &copy; 2023 zlatan aghnio rasya royyano.</p>
    </footer>
</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>zlatan aghnio Personal Website</title>

    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<style>
    body {
      background-image: url('R.jpeg');
      background-repeat: no-repeat;
      background-attachment: fixed;  
      background-size: cover;
    }
</style>
<body>
    <nav>
        <a href="index.html">Home</a> |
        <a href="cv-eko.pdf">Download CV</a> |
        <a href="contact.html">Contact</a> |
        <a href="about.html">About me</a>
    </nav>

    <hr />

    <div>
        <h1>Contact Me</h1>
        <form>
            <label for="email">Email</label><br />
            <input type="email" name="email" placeholder="alamat email" />
            <br />
            <label for="message">Pesan</label><br />
            <textarea placeholder="Tulis pesan anda..." rows="4" cols="80"></textarea>
            <br />
            <br />
            <input type="submit" value="Kirim" />
        </form>
    </div>

    <hr>
    <footer style="text-align: center;">
        <p>Copyright &copy; 2023 Zlatan aghnio rr.</p>
    </footer>
</body>

</html>


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Personal Portfolio Website Design | Codehal</title>
    <link rel="stylesheet" href="style.css">

    <!-- box icons -->
    <link
      href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
      rel="stylesheet"
    />

    <!-- custom css -->
  </head>

  <body>
    <!-- header design -->
    <a href="#" class="logo">Portfolio</a>

    <i class="bx bx-menu" id="menu-icon"></i>

    <nav class="navbar">
      <a href="#home" class="active">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#portofolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>

    <!-- home section design -->
    <section class="home" id="home">
      <div class="home-content">
        <h3>Hello, It's Me</h3>
        <h1>zlatan aghnio rasya royyano</h1>
        <h3>And I'm a <span>Frontend Developer</span></h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
          accusantium sapiente aspernatur fugiat officiis, quisquam omnis
          cupiditate.
        </p>
        <div class="social-media">
          <a href="#"><i class="bx bxl-facebook"></i></a>
          <a href="#"><i class="bx bxl-twitter"></i></a>
          <a href="#"><i class="bx bxl-instagram"></i></a>
          <a href="#"><i class="bx bxl-linkedin"></i></a>
        </div>
        <a href="#" class="btn">Download CV</a>
      </div>

      <div class="home-img">
        <img src="images/foto.jpg" alt="" />
      </div>
    </section>

    <!-- about section design -->

    <!-- services section design -->

    <!-- portfolio section design -->

    <!-- contact section design -->

    <!-- footer design -->

    <!-- scroll reveal -->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!-- typed js -->
    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>

    <!-- custom js -->
    <script src="js/script.js"></script>
  </body>
</html> ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
