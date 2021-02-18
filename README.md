<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>박병현의 포트폴리오</title>
  <link rel="stylesheet" href="/assets/css/jquery.fullpage.min.css">
</head>
<body>
  <!-- header -->
  <header>
    <nav>
      <!-- left -->
      <span>로고</span>
      <!-- // left -->
      <!-- right -->
      <ul>
        <li>자기소개</li>
        <li>
          <div>나의 기술</div>
          <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JQUERY</li>
          </ul>
        </li>
        <li>
          <span>코딩 사이트</span>
          <ul>
            <li>연습 코딩</li>
            <li>실무 코딩</li>
          </ul>
        </li>
      </ul>
      <!-- // right -->
    </nav>
  </header>
  <!-- // header -->
  <!-- main -->
  <main id="fullpage">
    <!-- page01 -->
    <section class="section section01">
      박병현의 포트폴리오입니다.
    </section>
    <!-- // page01 -->
    <!-- page02 -->
    <section class="section section02">
      HTML, CSS, JQUERY를 주로 사용합니다
    </section>
    <!-- // page02 -->
    <!-- page03 -->
    <section class="section section03">
      <div class="slide">HTML 기술</div>
      <div class="slide">슬라이드2</div>
      <div class="slide">슬라이드3</div>
      <div class="slide">슬라이드4</div>
    </section>
    <!-- // page03 -->
    <!-- page04 -->
    <section class="section section04">CSS 기술</section>
    <!-- // page04 -->
    <!-- page05 -->
    <section class="section section05">JQUERY 기술</section>
    <!-- // page05 -->
    <!-- page06 -->
    <section class="section section06">연습 코딩과 실무 코딩</section>
    <!-- // page06 -->
  </main>
  <!-- // main -->
  <!-- footer -->
  <footer></footer>
  <!-- // footer -->
  <!-- script -->
  <script src="https://code.jquery.com/jquery-3.5.1.js"></script>
  <script src="/assets/js/jquery.fullpage.min.js"></script>
  <script>
    $(document).ready(function () {
      $('#fullpage').fullpage({
        autoScrolling: true,
        scrollHorizontally: true
      });
    });

    //methods
	  $.fn.fullpage.setAllowScrolling(false);
  </script>
  <!-- // script -->
</body>
</html>
