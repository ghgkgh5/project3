# project3
<!doctype html>
{% load staticfiles %}
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="Mark Otto, Jacob Thornton, and Bootstrap contributors">
    <meta name="generator" content="Jekyll v3.8.5">
    <title>GAME SITE</title>

    <link rel="canonical" href="https://getbootstrap.com/docs/4.3/examples/album/">

    <!-- Bootstrap core CSS -->

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }
    </style>
    <!-- Custom styles for this template -->
    <link href="album.css" rel="stylesheet">
  </head>
  <body>
    <header>
  <div class="collapse bg-dark" id="navbarHeader">
    <div class="container">
      <div class="row">
        <div class="col-sm-8 col-md-7 py-4">
          <h4 class="text-white"></h4>
          <p class="text-muted"></p>
        </div>
        <div class="col-sm-4 offset-md-1 py-4">
          <h4 class="text-white"></h4>
          <ul class="list-unstyled">
            <li><a href="#" class="text-white">로그인</a></li>
            <li><a href="#" class="text-white">회원가입</a></li>
            <li><a href="#" class="text-white">아이디 비밀번호 찾기</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <div class="navbar navbar-dark bg-dark shadow-sm">
    <div class="container d-flex justify-content-between">
      <a href="{% url 'home' %}" class="navbar-brand d-flex align-items-center">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" aria-hidden="true" class="mr-2" viewBox="0 0 24 24" focusable="false"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg>
        <strong>Game</strong>
      </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarHeader" aria-controls="navbarHeader" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
    </div>
  </div>
</header>

<main role="main">

  <section class="jumbotron text-center">
    <div class="container">
      <h1 class="jumbotron-heading">GAME</h1>
      <p class="lead text-muted">여기는 게임사이트 입니다. </p>
    </div>
    <p>
        <a href="#" class="btn btn-primary my-2">게시판</a>
      </p>
  </section>
  <div class="album py-5 bg-light">
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card mb-4 shadow-sm">
          	<img src="http://blogfiles.naver.net/20121115_30/info27_1352971307668BmC6a_PNG/%B5%CE%B3%FA%B9%DF%B4%DE_%B0%D4%C0%D3_%C5%D7%C6%AE%B8%AE%BD%BA1.png"height="300"/>
            <div class="card-body">
              <p class="card-text" width="500">테트리스</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
              </div>
            </div>
          </div>
        </div>
      </div>
       <div class="col-md-4">
          <div class="card mb-4 shadow-sm">
            <img src="http://cafefiles.naver.net/20160217_147/muttul58_1455710849834GqtjG_PNG/%BC%D2%C4%DA%B9%DD04.png" height="300" />
            <div class="card-body">
              <p class="card-text">소코반</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
              </div>
            </div>
          </div>
        </div>
      </div>
       <div class="col-md-4">
          <div class="card mb-4 shadow-sm">
            <img src="http://blogfiles.naver.net/20101107_108/k9617454_1289126511824H2S6V_JPEG/%BF%C0%B8%F11.jpg"height="300"/>
            <div class="card-body">
              <p class="card-text">오목</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
              </div>
            </div>
          </div>
        </div>
      </div>
       <div class="col-md-4">
          <div class="card mb-4 shadow-sm">
            <img src="http://post.phinf.naver.net/20160106_31/whitebearmjf_1452041520546WUi10_JPEG/mug_obj_201601060952003441.jpg"height="300"/>
            <div class="card-body">
              <p class="card-text">체스</p>
              <div class="d-flex justify-content-between align-items-center">
                <div class="btn-group">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</main>

<footer class="text-muted">
  <div class="container">
    <p>임승준 송지원 위진욱</p>
  </div>
</footer>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
     </body>
</html>
