<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>이준석 | 색소폰 연주자</title>
<style>
* {
  box-sizing: border-box;
}
body {
  margin: 0;
  min-height: 100vh;
  font-family: Arial, "Noto Sans KR", sans-serif;
  background: #fff;
  color: #d60000;
  display: flex;
  justify-content: center;
}
.card {
  width: 100%;
  max-width: 520px;
  min-height: 100vh;
  padding: 70px 28px 40px;
  display: flex;
  flex-direction: column;
  text-align: center;
}
h1 {
  margin: 0 0 14px;
  font-size: 52px;
  font-weight: 900;
  letter-spacing: -3px;
}
.intro {
  margin: 0;
  font-size: 24px;
  font-weight: 700;
  line-height: 1.5;
}
.work {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 18px;
  margin: 40px 0;
}
.work div {
  border: 3px solid #d60000;
  border-radius: 18px;
  padding: 24px 15px;
  font-size: 30px;
  font-weight: 900;
}
.contact {
  display: block;
  padding: 22px;
  border-radius: 18px;
  background: #d60000;
  color: #fff;
  text-decoration: none;
  font-size: 30px;
  font-weight: 900;
  transition: .2s;
}
.contact:active {
  transform: scale(.97);
}
@media (max-width: 380px) {
  h1 { font-size: 44px; }
  .intro { font-size: 21px; }
  .work div { font-size: 26px; }
  .contact { font-size: 27px; }
}
</style>
</head>
<body>
<main class="card">
  <header>
    <h1>이준석</h1>
    <p class="intro">색소폰 연주자</p>
  </header>

  <section class="work">
    <div>🎷 연주하고</div>
    <div>🎓 레슨하고</div>
    <div>📚 교재만들기</div>
  </section>

  <a class="contact" href="tel:01000000000">
    문의하기
  </a>
</main>
</body>
</html> skydeer76-spec-github.io
