<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>فريق أتريوس</title>
<link rel="stylesheet" href="styles.css">
<script src="script.js"></script>
<style>
  /* أسلوب التنسيق الإضافي هنا */
  .carousel {
    width: 100%;
    overflow: hidden;
    margin: 20px 0;
  }

  .carousel ul {
    list-style: none;
    width: 400%;
    display: flex;
    transition: transform 0.5s ease-in-out;
  }

  .carousel li {
    width: 25%;
  }

  .login-form {
    margin: 20px auto;
    max-width: 400px;
    padding: 20px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  .rating {
    display: inline-block;
    unicode-bidi: bidi-override;
    direction: rtl;
  }

  .rating > input {
    display: none;
  }

  .rating > label {
    float: right;
    padding: 0 1px;
    font-size: 30px;
    color: #aaa;
    cursor: pointer;
  }

  .rating > input:checked ~ label,
  .rating > input:checked ~ label:hover,
  .rating > label:hover ~ input:checked ~ label {
    color: #f90;
  }

  .rating > label:hover,
  .rating > label:hover ~ label {
    color: #f90;
  }
</style>
</head>
<body>

<header>
  <nav>
    <ul>
      <li><a href="#home">الرئيسية</a></li>
      <li><a href="#releases">الإصدارات</a></li>
      <li><a href="#about">عن الفريق</a></li>
      <li><a href="#contact">تواصل معنا</a></li>
    </ul>
  </nav>
</header>

<section id="home">
  <h1>مرحباً بكم في موقع فريق أتريوس</h1>
  <p>مكانك المفضل لأحدث إصدارات المانجا.</p>
</section>

<section id="releases">
  <h2>أحدث الإصدارات</h2>
  <div class="carousel">
    <ul>
      <li><img src="https://via.placeholder.com/150" alt="إصدار 1"></li>
      <li><img src="https://via.placeholder.com/150" alt="إصدار 2"></li>
      <li><img src="https://via.placeholder.com/150" alt="إصدار 3"></li>
      <li><img src="https://via.placeholder.com/150" alt="إصدار 4"></li>
    </ul>
  </div>
</section>

<section id="about">
  <h2>عن الفريق</h2>
  <p>نحن فريق متخصص في ترجمة المانجا إلى العربية.</p>
</section>

<section id="contact">
  <h2>تواصل معنا</h2>
  <form class="login-form">
    <input type="text" id="username" name="username" placeholder="اسم المستخدم">
    <input type="password" id="password" name="password" placeholder="كلمة المرور">
    <button type="submit">تسجيل الدخول</button>
  </form>
</section>

<footer>
  <p>جميع الحقوق محفوظة لفريق أتريوس © 2024</p>
</footer>

</body>
</html>![82_20240516140041](https://github.com/rivanido/Revan-Hasan/assets/171208317/b6441262-468a-4712-972f-9d384279165f)

