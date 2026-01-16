---
layout: default
title: 안드로이드 개발자 방창배 포트폴리오
---

<style>
  .portfolio-container {
    font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
    line-height: 1.7;
    color: #333;
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
    word-break: keep-all;
  }

  /* 프로필 섹션 */
  .profile-card {
    display: flex;
    align-items: center;
    gap: 30px;
    padding: 30px;
    background: #ffffff;
    border-radius: 20px;
    border: 1px solid #eee;
    box-shadow: 0 10px 30px rgba(0,0,0,0.05);
    margin-bottom: 50px;
  }

  .profile-img {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #f8f9fa;
  }

  /* 공통 타이틀 */
  h2 {
    font-size: 1.6rem;
    color: #007aff;
    padding-bottom: 8px;
    margin-top: 50px;
  }

  h3 {
    font-size: 1.3rem;
    margin-bottom: 15px;
    color: #111;
  }

  /* 프로젝트/경력 박스 */
  .content-box {
    background: #fdfdfd;
    padding: 25px;
    border-radius: 15px;
    margin-bottom: 30px;
    border: 1px solid #efefef;
  }

  .video-group {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin: 15px 0;
  }

  .video-tag {
    display: inline-block;
    padding: 6px 14px;
    background: #ff0000;
    color: #fff !important;
    border-radius: 5px;
    font-size: 0.85rem;
    text-decoration: none;
    font-weight: 600;
  }

  /* 기술 스택 그리드 */
  .skill-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
  }

  .skill-item strong {
    display: block;
    color: #007aff;
    margin-bottom: 5px;
  }

  /* 모바일 대응 */
  @media (max-width: 640px) {
    .profile-card {
      flex-direction: column;
      text-align: center;
      padding: 20px;
    }
    .profile-info { text-align: left; }
    h1 { font-size: 1.5rem; }
  }
</style>

<div class="portfolio-container">

  <div class="profile-card">
    <img src="images/profile_img.png" alt="방창배 프로필" class="profile-img">
    <div class="profile-info">
      <h1 style="margin:0 0 10px 0;">Android & Mobile Developer</h1>
      <p style="margin:0 0 15px 0; font-size:1.05rem; color:#555;">
        약 7년간 안드로이드 앱을 개발해 왔으며,<br>
        최근 3년은 <strong>시각장애인 보조기기 및 공공 R&D 과제</strong>에 집중하고 있습니다.
      </p>
      <div style="font-size: 0.95rem; line-height: 1.8;">
        <strong>이름</strong>: 방창배 (1991.10.27)<br>
        <strong>Email</strong>: <a href="mailto:lonmell0213@gmail.com">lonmell0213@gmail.com</a><br>
        <strong>GitHub</strong>: <a href="https://github.com/lonmell" target="_blank">깃허브 링크</a>
      </div>
    </div>
  </div>

  <h2>소개</h2>
  <div class="content-box">
    <p>단순히 기능을 만드는 것을 넘어, 실제 사용자 환경에서의 <strong>접근성(Accessibility)</strong>을 가장 중요하게 생각합니다. 「약자를 위한 기술개발 지원사업」을 통해 시각장애인 실내 이동 서비스를 상용화했으며, 공공 R&D의 까다로운 품질 기준(TTA, GS인증 등)을 충족하는 안정적인 개발을 지향합니다.</p>
  </div>

  <h2>기술 스택</h2>
  <div class="content-box skill-grid">
    <div class="skill-item">
      <strong>Language</strong>
      Java(Main), Kotlin, Dart(Flutter), PHP
    </div>
    <div class="skill-item">
      <strong>Mobile Framework</strong>
      Android Native (Camera2, View, Service), BLE/iBeacon 연동, Retrofit, FCM, TTS, 음성인식
    </div>
    <div class="skill-item">
      <strong>Database & Tools</strong>
      MySQL, MariaDB, Git/GitHub, Notion, Jira
    </div>
    <div class="skill-item">
      <strong>Certification / R&D</strong>
      TTA 성능평가, GS인증, ISO9001 대응 역량
    </div>
  </div>

  <h2>대표 프로젝트</h2>
  
  <div class="content-box">
    <h3>1. HatioEye – 시각장애인 보조·실내 내비게이션</h3>
    <p style="color:#666; margin-bottom:10px;">2023.05 ~ 재직 중 | 안드로이드 핵심 개발</p>
    
    <div class="video-group">
      <a href="https://youtu.be/RvpdKi8TPu4" class="video-tag" target="_blank">KBS 뉴스 보도</a>
      <a href="https://youtu.be/JWexY0MNggE" class="video-tag" target="_blank">인천공항 시연</a>
      <a href="https://youtu.be/h5G9FrHZ0Tc" class="video-tag" target="_blank">국정감사 시연</a>
      <a href="https://www.youtube.com/watch?v=86Rvdg7s8Kc" class="video-tag" target="_blank">복지전시회 참여</a>
    </div>

    <p><strong>주요 업무:</strong></p>
    <ul>
      <li>안드로이드 앱 전체 구조 설계 및 핵심 기능(Camera2, BLE 측위) 개발</li>
      <li>시각장애인 전용 제스처 메뉴 및 음성 인터랙션 설계</li>
      <li><strong>기술 문서화:</strong> 하드웨어 연동 규격서(SA) 및 프로젝트 가이드(README) 체계적 관리</li>
    </ul>
    <p><strong>주요 성과:</strong> 서울특별시장 표창 수상, 조달청 혁신제품 등록, CES 2025 출품 지원</p>
  </div>

  <div class="content-box">
    <h3>2. 모바일 작업현황 보고 시스템</h3>
    <p style="color:#666; margin-bottom:10px;">2022 | 단독 개발</p>
    <ul>
      <li>공기업 현장 업무 디지털 전환을 위한 안드로이드 앱 설계 및 개발</li>
      <li>대구경북 스타트업 페스티벌 <strong>공기업 대학생 부문 수상</strong> (한국가스공사)</li>
    </ul>
  </div>

  <h2>R&D · 공공 사업 참여 이력</h2>
  <div class="content-box">
    <ul style="font-size: 0.95rem; padding-left: 20px;">
      <li>2024 인천공항 신기술 테스트베드 공모전 선정</li>
      <li>2024 디지털인프라(SW) 종합 진단 및 개선 사업 (TTA/NIPA) 대응</li>
      <li>2024 경상북도 4차산업혁명 핵심기술개발 (비대면 시험 감독 시스템)</li>
      <li>2024 양자기술개발 지원사업 기획 참여</li>
      <li>2023 약자를 위한 기술개발 지원사업 (서울시)</li>
      <li>스마트라이프위크, 월드IT쇼 등 주요 박람회 기술 시연 및 지원</li>
    </ul>
  </div>

</div>
