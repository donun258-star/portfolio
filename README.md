# portfolio

---

## 💻 [2] 포트폴리오 샘플 수정본 (HTML 파일)

아래는 CSS나 JS 없이 **HTML만으로 완성된 포트폴리오**예시입니다.  
이걸 그대로 깃허브에 `index.html`로 저장하면 완벽해요.

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>김도윤 - 포트폴리오</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f9f9f9; color: #333; }
    header { background: #004aad; color: white; text-align: center; padding: 2rem 1rem; }
    section { max-width: 800px; margin: 2rem auto; background: white; padding: 2rem; border-radius: 12px; }
    h2 { color: #004aad; border-bottom: 2px solid #004aad; padding-bottom: 0.3rem; }
    p { line-height: 1.6; }
    footer { text-align: center; padding: 1rem; color: #777; font-size: 0.9rem; }
  </style>
</head>
<body>
  <header>
    <h1>김도윤</h1>
    <p>한신대학교 1학년 | 학업 중심 포트폴리오</p>
  </header>

  <section>
    <h2>👋 자기소개</h2>
    <p>안녕하세요. 저는 한신대학교에 재학 중인 김도윤입니다.<br>
    웹 개발과 컴퓨터 관련 기술에 관심이 있으며, 기초부터 차근히 배워가고 있습니다.<br>
    아직은 1학년이지만, 앞으로 다양한 프로젝트를 경험하며 실력을 키우는 것이 목표입니다.</p>
  </section>

  <section>
    <h2>🎓 학력</h2>
    <ul>
      <li>한신대학교 (재학 중, 1학년)</li>
      <li>원곡고등학교 졸업</li>
    </ul>
  </section>

  <section>
    <h2>💻 관심 분야</h2>
    <ul>
      <li>웹 프론트엔드 개발</li>
      <li>HTML / CSS / JavaScript 기초</li>
      <li>인공지능(AI) 및 클라우드 기술</li>
    </ul>
  </section>

  <section>
    <h2>📬 연락처</h2>
    <p>이메일: example@email.com</p>
    <p>GitHub: <a href="https://github.com/사용자명" target="_blank">https://github.com/사용자명</a></p>
  </section>

  <footer>
    © 2025 Kim Doyun. All rights reserved.
  </footer>
</body>
</html>
