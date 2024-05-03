<!DOCTYPE html>
<html>
    <head>
        <title>자기 소개 페이지</title>
        <link href="웹프로그래밍 과제.css" type="text/css" rel="stylesheet">
    </head>
    <body>
    <header>
        <div class="image-container">
            <img src="파도.png">
            <div class="text-overlay">자기 소개 페이지</div>
        </div>
        <hr>
        <div id="b1">
            <span class="text1">저는 장현정입니다.</span>
            <br><br>
            저는 순천향대학교에서 컴퓨터소프트웨어공학을 전공하고 있는 대학교 1학년 학생입니다. <br> 프로그래밍과 웹 개발에 큰 관심이 있어 이 분야를 더 깊게 공부하고 싶습니다.
        </div>
    </header>
    
  <nav>
        <ul>
            <div id="nav_p">
                <div class="nav_c a">
                    <a href="#habbit" class="a">취미</a>
                </div>
                <div class="nav_c a">
                    <a href="#dream" class="a">꿈</a>
                </div>
                <div class="nav_c a">
                    <a href="#favorit" class="a">좋아하는 것</a>
                </div>
                <div class="nav_c a">
                    <a href="#email" class="a">이메일 주소</a>
                </div>
                <div class="nav_c a">
                    <a href="#time table" class="a">시간표</a>
                </div>
            </div>            
        </ul>
    </nav>
    <hr><br>
    <section>
        <div class="flex_container">
            <div class="flex_item" id="habbit">
                <span class="text2">[취미]</span><br><br>
                제 취미는 TV 프로그램을 보는 것과 음악 감상입니다.<br>
                또한 다양한 음악을 들으며 휴식을 취하는 것을 좋아합니다.
            </div>
            <div class="flex_item" id="dream">
                <span class="text2">[꿈]</span><br><br>
                제 꿈은 웹 개발자가 되어 사용자 친화적이고 혁신적인 웹 사이트를 만드는 것입니다. <br>
                기술을 통해 사람들의 삶을 더 편리하고 즐겁게 만드는 것에 기여하고 싶어요.
            </div>
        </div>
        <br><hr><hr><br>
        <div id="favorit">
        <span class="text2">[좋아하는 것]</span>
        </div>
        <ul>
            <div id="sec1_p">
                <div class="sec1_c">
                <div class="dropdown">
                    <span class="drop_a" >좋아하는 노래</span>
                    <div class="dropdown-content">
                        <a href="#section1">한 페이지가 될 수 있게</a>
                        <a href="#section2">Passionfruit(패션후르츠)</a>
                        <a href="#section3">Drunk text</a>
                    </div>
                </div>
                </div>
                <div class="sec1_c">
                <div class="dropdown">
                    <span class="drop_a">좋아하는 스포츠</span>
                    <div class="dropdown-content">
                        <a href="#section4">배드민턴</a>
                        <a href="#section5">축구</a>
                    </div>
                </div>
                </div>
            
                <!-- 세 번째 드롭다운 메뉴 -->
<div class="sec1_c">
                <div class="dropdown">
                    <span class="drop_a">좋아하는 방송</span>
                    <!-- 세 번째 드롭다운 내용 -->
                    <div class="dropdown-content">
                        <a href="#section7">푸바오와 할부지</a>
                        <a href="#section8">신서유기</a>
                        <a href="#section9">알고보면 쓸데없는 지구별 잡학사전</a>
                    </div>
                </div>
                </div>
            
                <!-- 첫 번째 섹션 -->
  <div id="section1" class="section">
                    <span class="text4">한 페이지가 될 수 있게</span>
                    <p>'한페이지가 될 수 있게'는 2019년 7월 15일에 발매된 그룹 'DAY6(데이식스)'의 노래입니다.</p>
                    <a href="https://youtu.be/vnS_jn2uibs?si=uoOXb7XJYsciPeQg" target="_blank">이 노래 [바로가기]</a>
                </div>
            
                <!-- 두 번째 섹션 -->
   <div id="section2" class="section">
                    <span class="text4">Passionfruit(패션후르츠)</span>
                    <p>Passionfruit(패션후르츠)'는 2024년 1월 15일에 발매된 그룹 'NMIXX(엔믹스)'의 노래입니다. </p>
                    <a href="https://youtu.be/v7rfkLyeTzs?si=srBrkHB8B4xh_cUq" target="_blank">이 노래 [바로가기]</a>
                </div>
            
                <!-- 세 번째 섹션 -->
  <div id="section3" class="section">
                    <span class="text4">Drunk text</span>
                    <p>'Drunk text'는 2023년 1월 27일에 발매된 가수 'Henry Moodie'의 노래입니다.</p>
                    <a href="https://youtu.be/OqEc_169ywY?si=69WHkXrj3114B2GG" target="_blank">이 노래 [바로가기]</a>
                </div>
            <!-- 네 번째 섹션 -->
                <div id="section4" class="section">
                    <span class="text4">배드민턴</span>
                    <p>배드민턴은 네트를 사이에 두고 라켓으로 셔틀콕을 서로 치고 받는 구기 경기이다.</p>
                </div>
        <!-- 다섯 번째 섹션 -->
                <div id="section5" class="section">
                    <span class="text4">축구</span>
                    <p>축구는 11명이 팀을 이루어 발로 공을 차서 상대편의 골에 공을 많이 넣는 것으로 승부를 겨루는 경기이다.</p>
                </div
                  <!-- 일곱 번째 섹션 -->
                <div id="section7" class="section">
                    <span class="text4">푸바오와 할부지</span>
                    <p>푸바오와 할부지'는 전 국민의 사랑을 받은 판다 푸바오와 강철원, 송영관 사육사의 만남과 이별을 관찰하는 토크 프로그램이다.</p>
                    <link rel="stylesheet" type="text/css" href="reset.css"/>
                        <style>
                            .img-concer{
                                        width:123px;
                                        height:68px;
                                        }
                        </style>
                        <a href="https://programs.sbs.co.kr/enter/fubaongrandpa/main" target="_blank">
                            <img class="img-concert" src="푸바오와 할부지.png"/><br><br>
                        </a>
                </div>
                <!-- 여덟 번째 섹션 -->
                <div id="section8" class="section">
                    <span class="text4">신서유기</span>
                    <p>'신서유기'는 미션을 통해 7개의 용볼을 모으는 리얼 버라이어티 프로그램이다</p>
                    <link rel="stylesheet" type="text/css" href="reset.css"/>
                        <style>
                            .img-concer{
                                        width:104px;
                                        height: 400px;
                                        }
                        </style>
                        <a href="https://tvn.cjenm.com/ko/tvnbros8/" target="_blank">
                            <img class="img-concert" src="신서유기.png"/><br><br>
                        </a>
                </div>
                <!-- 아홉 번째 섹션 -->
                <div id="section9" class="section">
                    <span class="text4">알고보면 쓸데없는 지구별 잡학사전</span>
                    <p>'알고보면 쓸데없는 지구별 잡학사전'은 건축, 역사, 문학, 물리학, 영화의 여러 박사들과 함께 지구와 도시에 대해 이야기한은 토크 프로그램이다.</p>
                    <link rel="stylesheet" type="text/css" href="reset.css"/>
                        <style>
                            .img-concer{
                                        width:80px;
                                        height:180px;
                                        }
                        </style>
                        <a href="https://tvn.cjenm.com/ko/aroundtheearth/" target="_blank">
                            <img class="img-concert" src="알쓸별잡.png"/><br><br>
                        </a>
                </div>
            </div>
        </ul>
        <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><hr><br>
        <div id="email">
        <span class="text3">[이메일 주소]</span>
        </div>
        이메일 : <a href="mailto:hyeonjeong15526@gmail.com">hyeonjeong15526@gmail.com</a><br><br>
    </section>
    <section>
        <hr>
        <div id="time table">
        <table border="1" class="time">
            <caption><p>시간표</p></caption>
            <thead>
                <tr><td>시간/요일</td><td>월요일</td><td>화요일</td><td>수요일</td><td>목요일</td><td>금요일</td></tr>
            </thead>
            <tbody>
                <tr><td>9:00~9:30</td><td rowspan="6" id="table_web">웹 프로그래밍<br>M503</td><td rowspan="3" id="table_com">컴퓨터 개론<br>M503</td><td></td><td rowspan="4" id="table_write">글쓰기<br>U629</td><td></td></tr>
                <tr><td>9:30~10:00</td><td></td><td></td></tr>
                <tr><td>10:00~10:30</td><td></td><td></td></tr>
                <tr><td>10:30~11:00</td><td></td><td></td><td></td></tr>
                <tr><td>11:00~11:30</td><td></td><td rowspan="6" id="table_python">파이썬 프로그래밍<br>M503</td><td></td><td></td></tr>
                <tr><td>11:30~12:00</td><td></td><td></td><td></td></tr>
                <tr><td>12:00~12:30</td><td></td><td></td><td></td><td></td></tr>
                <tr><td>12:30~13:00</td><td></td><td></td><td></td><td></td></tr>
                <tr><td>13:00~13:30</td><td></td><td></td><td></td><td></td></tr>
                <tr><td>13:30~14:00</td><td></td><td></td><td></td><td rowspan="6" id="table_coding">컴퓨터코딩과 문제해결<br>9115</td></tr>
                <tr><td>14:00~14:30</td><td></td><td></td><td></td><td rowspan="6" id="table_math">일반 수학<br>M503</td></tr>
                <tr><td>14:30~15:00</td><td></td><td></td><td></td></tr>
                <tr><td>15:00~15:30</td><td rowspan="3" id="table_com">컴퓨터 개론<br>M503</td><td></td><td></td></tr>
                <tr><td>15:30~16:00</td><td></td><td></td></tr>
                <tr><td>16:00~16:30</td><td></td><td rowspan="4" id="table_python_practice">파이썬 프로그래밍 실습<br>M518</td></tr>
                <tr><td>16:30~17:00</td><td></td><td></td><td></td></tr>
                <tr><td>17:00~17:30</td><td></td><td rowspan="2" id="table_m">자기개발과 전공탐색(M&M)<br>M503</td><td></td><td></td></tr>
                <tr><td>17:30~18:00</td><td></td><td></td><td></td></tr>
            </tbody>
        </table>
        </div>
        <br>
    </section>    
    <footer id="footer">
        <div class="text5">자기소개 페이지를 읽어주셔서 감사합니다!</div>
    </footer>
        
  </body>
</html>
