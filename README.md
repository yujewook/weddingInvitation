<html lang="en-US">
<head>
    <meta charset="UTF-8">
    <meta content="IE=edge" http-equiv="X-UA-Compatible">
    <meta content="width=device-width, initial-scale=1" name="viewport">
    <title>유제욱과 김유주의 결혼식</title>
    <meta content="유제욱과 김유주의 결혼식에 와서 축하해주세요~!" name="description"/>
    <meta property="og:image" content="images/pic2.jpeg">
    <meta property="fb:app_id" content="781066922265598" />
    <meta property="fb:admins" content="Choi.Anderson"/>
    <link href="images/favicon/apple-touch-icon.png" rel="apple-touch-icon" sizes="180x180">
    <link href="images/favicon/favicon-32x32.png" rel="icon" sizes="32x32" type="image/png">
    <link href="images/favicon/favicon-16x16.png" rel="icon" sizes="16x16" type="image/png">
    <link href="https://fonts.googleapis.com/css?family=Dosis:400,500" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Great+Vibes" rel="stylesheet">
    <link href="css/ekko-lightbox.css" rel="stylesheet">
    <link href="styles/main.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Gamja+Flower|Gugi|Noto+Serif+KR|Stylish|Sunflower:300"
          rel="stylesheet">
    <script src="https://code.jquery.com/jquery-2.2.1.js"></script>


    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script src="https://cdn.emailjs.com/sdk/2.3.2/email.min.js" type="text/javascript"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/remarkable/1.7.1/remarkable.js" type="text/javascript"></script>
    <script type="text/javascript">
        function sendMail() {

            (function () {
                emailjs.init("user_yjLL5xG0A3kkOCH5BGIDh");
                emailjs.send("wedding-mail", "gift_send", {
                    name: $("#sender-name").value,
                    gift: $("#gift-name").text(),
                    message: $("#sender-message").value
                }).then(function (response) {
                    console.log("SUCCESS. status=%d, text=%s", response.status, response.text);
                }, function (err) {
                    console.log("FAILED. error=", err);
                });
            })();
        }

        function findGetParameter(parameterName) {
            var result = null,
                tmp = [];
            location.search
                .substr(1)
                .split("&")
                .forEach(function (item) {
                  tmp = item.split("=");
                  if (tmp[0] === parameterName) result = decodeURIComponent(tmp[1]);
                });
            return result;
        }

    </script>
</head>

<body id="top">
<header></header>
<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/ko_KR/sdk.js#xfbml=1&version=v3.2"></script>
<div class="page-content">
    <div class="div">
        <div class="ww-home-page" id="home">
            <div class="ww-wedding-announcement d-flex align-items-center justify-content-start">
                <div class="container ww-announcement-container">
                    <p class="ww-couple-name ww-title" style="font-size:4.0em">Jewook & Yuju</p>
                    <p class="h2 mt-5 ww-title" style="font-family: 'Gugi', cursive; font-size:1.0em">
                        | WE ARE GETTING MARRIED |
                    </p>
                    <p class="h2 mt-5 ww-title"
                       style="font-family: 'Noto Serif KR', serif; font-size:1.0em; letter-spacing:-1px">
                        <b style="font-size:1.4em;">2025. 05. 10. SAT PM 12:30</b>
                        <br>판교 컨베션센터 W
                    </p>
                </div>
            </div>
        </div>
        <div class="ww-nav-bar sticky-top bg-light">
            <nav class="navbar navbar-expand-lg navbar-light">
                <div class="container">
                    <button aria-controls="ww-navbarNav" aria-expanded="false" aria-label="Toggle navigation"
                            class="navbar-toggler"
                            data-target="#ww-navbarNav" data-toggle="collapse" type="button">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse text-uppercase" id="ww-navbarNav">
                        <ul class="navbar-nav ml-auto">
                            <li class="nav-item"><a class="nav-link smooth-scroll" href="#home">Home</a></li>
                            <li class="nav-item"><a class="nav-link smooth-scroll" href="#couple">Couple</a></li>
                            <li class="nav-item"><a class="nav-link smooth-scroll" href="#events">Events</a></li>
                            <li class="nav-item"><a class="nav-link smooth-scroll" href="#gallery">Gallery</a></li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
        <div class="ww-section" id="couple">
            <div class="container">
                <h2 class="h1 text-center pb-3 ww-title" style="font-family: 'Noto Serif KR', serif;">신랑 & 신부</h2>
                <div class="row text-center">
                    <div class="col-md-6">
                        <div class="mt-3">
                            <h3 class="h2 ww-title" style="font-family: 'Sunflower', sans-serif; font-size:1.5em">
                                김유주</h3>
                            <img alt="Groom" class="img-fluid" src=""/>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="mt-3">
                            <h3 class="h2 ww-title" style="font-family: 'Sunflower', sans-serif; font-size:1.5em">
                                유제욱</h3>
                            <img alt="Bride" class="img-fluid" src=""/>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="ww-section bg-light" id="events">
            <div class="container ww-wedding-event">
                <h2 class="h1 text-center pb-3 ww-title" style="font-family: 'Noto Serif KR', serif;">초대합니다</h2>
                    <div class="col text-center mb-5">
                        <h6 style="font-family: 'Noto Serif KR', serif;">
                            1463<br>
                            (만난지 4년+1일 되는날 결혼 = 1463일)
                        </h6>
                    </div>
                <div class="row">
                    <div class="col-md-7 col-sm-12">
                        <div class="my-3">
                            <div class="h4">웨딩 본식</div>
                            <ul>
                                <li>
                                    <i class="text-muted fas fa-map-marker-alt"></i>
                                    <span class="pl-2 text-muted">부산 해운대 우동 센텀사이언스 파크 23층</span>
                                </li>
                                <li class="pt-2">
                                    <i class="text-muted far fa-calendar-alt"></i>
                                    <span class="pl-2 text-muted">2019년 5월 18일, 2:30PM</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-md-5 col-sm-12">
                        <div class="my-3">
                            <img alt="Wedding Party" class="img-fluid" src=""/>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-7 col-sm-12">
                        <div class="my-3">
                            <div class="h4">식사</div>
                            <ul>
                                <li>
                                    <i class="text-muted fas fa-map-marker-alt "></i>
                                    <span class="pl-2 text-muted">부산 해운대 우동 센텀사이언스 파크 지하 1층 더파티 센텀점</span>
                                </li>
                                <li class="pt-2">
                                    <i class="text-muted far fa-calendar-alt "></i>
                                    <span class="pl-2 text-muted">2019년 5월 18일, 2:30PM - 4:30PM</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-md-5 col-sm-12">
                        <div class="my-3"><img alt="Reception" class="img-fluid" src=""/></div>
                    </div>
                </div>
            </div>
        </div>
        <div class="ww-section" id="gallery">
            <div class="ww-photo-gallery">
                <div class="container">
                    <h2 class="h1 text-center pb-3 ww-title" style="font-family: 'Noto Serif KR', serif;">포토 갤러리</h2>
                    <div class="ww-gallery">
                        <div class="card-columns">
                            <div class="card" data-groups="[&quot;party&quot;,&quot;wedding&quot;]">
                                <a data-gallery="ww-gallery" data-toggle="lightbox">
                                    <img alt="Gallery Pic 2" class="img-fluid" src=""/>
                                </a>
                            </div>
                            <div class="card" data-groups="[&quot;vacation&quot;]">
                                <a data-gallery="ww-gallery" data-toggle="lightbox">
                                    <img alt="Gallery Pic 3" class="img-fluid" src=""/>
                                </a>
                            </div>
                            <div class="card" data-groups="[&quot;party&quot;,&quot;vacation&quot;]">
                                <a data-gallery="ww-gallery" data-toggle="lightbox">
                                    <img alt="Gallery Pic 4" class="img-fluid" src=""/>
                                </a>
                            </div>
                            <div class="card" data-groups="[&quot;vacation&quot;]">
                                <a data-gallery="ww-gallery" data-toggle="lightbox">
                                    <img alt="Gallery Pic 5" class="img-fluid" src=""/>
                                </a>
                            </div>
                            <div class="card"
                                 data-groups="[&quot;wedding&quot;,&quot;ceremony&quot;,&quot;party&quot;]">
                                <a data-gallery="ww-gallery" data-toggle="lightbox">
                                    <img alt="Gallery Pic 6" class="img-fluid" src=""/>
                                </a>
                            </div>
                            <div class="card" data-groups="[&quot;vacation&quot;]">
                                <a data-gallery="ww-gallery" data-toggle="lightbox">
                                    <img alt="Gallery Pic 7" class="img-fluid" src=""/>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="ww-section ww-rsvp-detail" id="map">
            <div class="container">
                <div class="col text-center">
                    <h2 class="h1 text-center pb-3 ww-title" style="font-family: 'Noto Serif KR', serif;">오시는 길</h2>
                    <div>
                        <h5 style="font-family: 'Noto Serif KR', serif;">판교컨벤션센터 W</h5>
                        <h6 style="font-family: 'Noto Serif KR', serif;">(경기도 성남시 분당구 판교역로226번길 16)</h6>
                    </div>
                </div>

                <div class="form-group">
                    <div class="col-md-12">
                        <div class="my-3 text-center">
                            <a href="http://naver.me/5pTy3HCa">
                                <img alt="naver-map" class="map-icon" id="naver-map"
                                     src="images/map/naver-map.png"/>
                            </a>
                            <a href="http://dmaps.kr/2bms8">
                                <img alt="kakao-map" class="map-icon" id="kakao-map"
                                     src="images/map/kakao-map.png"/>
                            </a>
                            <a href="https://maps.app.goo.gl/jfDxw">
                                <img alt="google-map" class="map-icon" id="google-map"
                                     src="images/map/google-map.png"/>
                            </a>
                        </div>
                        <div class="col text-center">
                            <label style="font-family: 'Noto Serif KR', serif; font-size: 15px;">
                                셔틀버스 - 
                            </label>
                        </div>
                        <div class="my-3">
                            <iframe src="https://www.google.com/maps/place/%EB%8D%94%EB%B8%94%EC%9C%A0%EC%8A%A4%ED%80%98%EC%96%B4%EC%BB%A8%EB%B2%A4%EC%85%98/data=!4m6!3m5!1s0x357ca7e540109215:0x192fc7c81979cbac!8m2!3d37.4005556!4d127.1113889!16s%2Fg%2F11bw5w3lfd?entry=ttu&g_ep=EgoyMDI0MTAwMi4xIKXMDSoASAFQAw%3D%3D" width="100%" height="400" frameborder="0" style="border:0" allowfullscreen></iframe>
                        </div>
                    </div>
                </div>


            </div>
        </div>

        <div class="ww-section bg-light" id="comment">
            <div class="ww-photo-gallery">
                <div class="container">
                    <div class="col text-center">
                        <h2 class="h1 text-center pb-3 ww-title" style="font-family: 'Noto Serif KR', serif;">축하메시지</h2><br>
                        <div id="comments"></div>
                        <br>
                        <div class="row">
                            <div class="col text-center"><form action="https://github.com/AndersonChoi/wedding-card/blob/master/README.md">
                                <button class="btn btn-primary btn-submit" type="submit">메시지 남기러 가기</button></form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>
</div>
</div>
<div aria-hidden="true" aria-labelledby="exampleModalLabel" class="modal fade" id="giftMailModal" role="dialog"
     tabindex="-1">
    <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLongTitle">선물하기 - <span id="gift-name"></span></h5>
                <button aria-label="Close" class="close" data-dismiss="modal" type="button">
                    <span aria-hidden="true">&times;</span>
                </button>
            </div>
            <div class="modal-body">
                <div class="input-group mb-3">
                    <div class="input-group-prepend">
                        <span class="input-group-text">보내는 분 성함</span>
                    </div>
                    <input aria-describedby="basic-addon3" class="form-control" id="sender-name" type="text">
                </div>
                <div class="input-group">
                    <textarea aria-label="With textarea" class="form-control" id="sender-message"
                              placeholder="신랑, 신부에게 선물 예약과 함께 보낼 메시지를 입력해주세요. 이 메시지는 신랑, 신부에게 발송됩니다." rows=4></textarea>
                </div>
            </div>
            <div class="modal-footer">
                <button class="btn btn-primary" id="reserveGiftButton" type="button">예약</button>
            </div>
        </div>
    </div>
</div>
<footer></footer>
<script src="https://code.jquery.com/jquery-3.3.1.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
<script src="js/aos.js"></script>
<script src="js/parallax.min.js"></script>
<script src="js/ekko-lightbox.min.js"></script>
<script src="scripts/main.js"></script>

<div class="bottom_right"><i class="fa fa-arrow-up fa-2x" id="go-to-top"></i>
</div>

<div class="bottom_left">
    <audio id="player" src="mus.mp3"></audio>
    <div>
        <i class="fa fa-music fa-2x" onclick="document.getElementById('player').play()"></i>
    </div>
</div>

</body>
</html>
