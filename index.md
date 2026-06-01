---
layout: default
title: 안드로이드 및 풀스택 개발자 방창배 포트폴리오
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
    border-bottom: 2px solid #007aff;
    display: inline-block;
  }

  h3 {
    font-size: 1.3rem;
    margin-top: 5px;
    margin-bottom: 15px;
    color: #111;
  }

  /* 프로젝트/경력 박스 */
  .content-box {
    background: #fdfdfd;
    padding: 25px;
    border-radius: 15px;
    margin-top: 15px;
    margin-bottom: 30px;
    border: 1px solid #efefef;
    box-shadow: 0 2px 8px rgba(0,0,0,0.01);
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
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
  }

  .skill-item strong {
    display: block;
    color: #007aff;
    margin-bottom: 5px;
  }

  .project-tag-group {
    margin-bottom: 15px;
  }

  .project-tag {
    display: inline-block;
    background: #e1f0ff;
    color: #007aff;
    padding: 3px 10px;
    border-radius: 5px;
    font-size: 0.85rem;
    font-weight: bold;
    margin-right: 5px;
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

  <!-- 프로필 카드 -->
  <div class="profile-card">
    <img src="images/profile_img.png" alt="방창배 프로필" class="profile-img">
    <div class="profile-info">
      <h1 style="margin:0 0 10px 0;">Android & Full-Stack Developer</h1>
      <p style="margin:0 0 15px 0; font-size:1.05rem; color:#555;">
        기능 구현을 넘어 최적화와 안정성을 고민하는 <strong>8년 차 안드로이드 중심 풀스택 개발자</strong>입니다.<br>
        모바일 네이티브 앱 설계부터 대용량 서버 데이터 처리, 공공 R&D 시스템 품질 검증까지 전체 개발 공정을 주도해 왔습니다.
      </p>
      <div style="font-size: 0.95rem; line-height: 1.8;">
        <strong>이름</strong>: 방창배 (1991년생)<br>
        <strong>Email</strong>: <a href="mailto:lonmell0213@gmail.com">lonmell0213@gmail.com</a><br>
        <strong>GitHub</strong>: <a href="https://github.com/lonmell" target="_blank">https://github.com/lonmell</a><br>
        <strong>Portfolio</strong>: <a href="https://lonmell.github.io/" target="_blank">https://lonmell.github.io/</a>
      </div>
    </div>
  </div>

  <h2>소개</h2>
  <div class="content-box">
    <p style="margin: 0;">
      사용자 환경에 최적화된 <strong>접근성(Accessibility)</strong>과 시스템의 <strong>성능 최적화</strong>를 개발의 핵심 가치로 둡니다. 
      시각장애인을 위한 AI 비전 인식 실내 보행 서비스를 상용화하여 공공 조달 시장에 등록시켰으며, 최근에는 스마트공장 전용 태블릿 UX 전면 리뉴얼 및 DB 조회 속도를 최대 100배 이상 개선하는 성능 최적화를 성공적으로 완수했습니다. 
      TTA 성능평가 대응 및 GS인증 기술 검증 경험을 바탕으로, 높은 신뢰성과 무결성이 요구되는 공공·기업용 미션 크리티컬 시스템 개발에 강점이 있습니다.
    </p>
  </div>

  <h2>기술 스택</h2>
  <div class="content-box skill-grid">
    <div class="skill-item">
      <strong>Language</strong>
      Java(Main), Kotlin, PHP, JavaScript, TypeScript, TypeScript, HTML5/CSS3
    </div>
    <div class="skill-item">
      <strong>Mobile Framework</strong>
      Android Studio (Native), Accessibility API, Camera API, STT/TTS SDK, Social Login SDK, WebView, BLE/iBeacon
    </div>
    <div class="skill-item">
      <strong>Backend & Web</strong>
      eGovFrame/Spring, MyBatis, JSP, React.js, Next.js, Node.js, Streamlit, Python(reportlab)
    </div>
    <div class="skill-item">
      <strong>Database & Ops</strong>
      MySQL, MariaDB (Procedure, Trigger, FEDERATED), Tomcat, Linux (CentOS), Git/GitHub, Playwright (E2E), Figma
    </div>
  </div>

  <h2>대표 프로젝트</h2>
  
  <!-- 프로젝트 1 -->
  <div class="content-box">
    <h3>1. 식품 제조 HACCP 스마트공장 시스템 및 kbsNew 수불 ERP 구축</h3>
    <p style="color:#666; margin-bottom:10px;">2026.04 ~ 2026.05 | 아이티팩토리 | 단독/풀스택 개발자</p>
    <div class="project-tag-group">
      <span class="project-tag">Java/Spring</span>
      <span class="project-tag">MyBatis</span>
      <span class="project-tag">MySQL</span>
      <span class="project-tag">JSP</span>
      <span class="project-tag">Playwright</span>
      <span class="project-tag">Streamlit</span>
    </div>
    <p>식품 제조 현장의 안전과 효율을 극대화하기 위해 IoT 센서 연동, CCP 모니터링, 태블릿 전용 UI 리뉴얼 및 백엔드 ERP 연동을 담당한 풀스택 프로젝트입니다.</p>
    
    <p><strong>주요 업무 및 성과:</strong></p>
    <ul>
      <li><strong>DB 성능 최적화:</strong> 복합 인덱스 설계 및 매퍼 재작성을 통해 CCP 자동 조회 성능을 획기적으로 개선 (가열일지: 4.6s → 1.2s로 4배 단축 / 금속일지: 4.0s → 0.03s로 100배 이상 속도 단축). FEDERATED 테이블의 원격 함수 오버헤드 원인을 파악하여 집계 쿼리로 전환 해결.</li>
      <li><strong>kbsNew 수불 ERP 신규 메뉴군 구축:</strong> 영업/구매/생산/재고/기초 모듈 등 신규 메뉴 13종 및 테이블 19개 설계·개발(LOT 재고 추적, 자동 발주 등 포함).</li>
      <li><strong>현장 전용 태블릿 v2 리뉴얼:</strong> 현장 거친 환경을 고려한 44px+ 터치 영역 및 시인성 높은 폰트를 적용한 'Industrial Minimal' 디자인 시스템 적용. 무단 업체 간 데이터 누수 차단을 위한 세션 기반 강제 적용 강화.</li>
      <li><strong>IoT 센서 연동 및 대시보드:</strong> 금속검출기, 가열기 등 16종 설비 센서 REST API 수집 표준화 및 Streamlit을 활용한 모니터링 대시보드 구축.</li>
      <li><strong>품질 검증 자동화:</strong> Playwright 기반 E2E 자동 테스트 인프라를 구축하여 전 메뉴(86종) 무결성 회귀 테스트 시스템 확립 (자동 검증 97/97 전 항목 PASS).</li>
    </ul>
  </div>

  <!-- 프로젝트 2 -->
  <div class="content-box">
    <h3>2. HatioEye(하티오아이) – AI 비전 인식 시각장애인 보조 및 실내 내비게이션</h3>
    <p style="color:#666; margin-bottom:10px;">2023.05 ~ 2026.01 | ㈜하가 | 안드로이드 핵심 개발자 및 팀장</p>
    <div class="project-tag-group">
      <span class="project-tag">Android Studio</span>
      <span class="project-tag">Java/Kotlin</span>
      <span class="project-tag">Accessibility API</span>
      <span class="project-tag">Camera API</span>
      <span class="project-tag">STT/TTS SDK</span>
      <span class="project-tag">PHP/MySQL</span>
    </div>
    
    <div class="video-group">
      <a href="https://youtu.be/RvpdKi8TPu4" class="video-tag" target="_blank">KBS 뉴스 보도</a>
      <a href="https://youtu.be/JWexY0MNggE" class="video-tag" target="_blank">인천공항 시연</a>
      <a href="https://youtu.be/h5G9FrHZ0Tc" class="video-tag" target="_blank">국정감사 시연</a>
      <a href="https://www.youtube.com/watch?v=86Rvdg7s8Kc" class="video-tag" target="_blank">복지전시회 참여</a>
    </div>

    <p>사회적 약자를 위한 독립적 보행 솔루션으로, 카메라 실시간 비전 인식 정보와 음성 피드백을 결합한 시각장애인 전용 내비게이션 플랫폼 개발을 총괄했습니다.</p>
    
    <p><strong>주요 업무 및 성과:</strong></p>
    <ul>
      <li><strong>핵심 모바일 기능 개발:</strong> Accessibility API 및 Camera API를 활용해 시각장애인 맞춤형 제스처 인터랙션 및 위험물 감지 알림 기능을 Native 환경으로 완벽히 설계·구현.</li>
      <li><strong>안정적 아키텍처 수립:</strong> 모바일 앱 서비스 구조 설계부터 센서 데이터 처리 백엔드 API 연동까지 풀스택 라이프사이클 리드. 하드웨어 연동 기술 규격서(SA) 및 협업 가이드 구축.</li>
      <li><strong>인증 및 대외 성과 도출:</strong> 조달청 혁신제품(시각장애인 보조기기) 공공 조달 등록 완료 및 인천공항 신기술 테스트베드 공모전 선정. CES 2025 출품을 통한 글로벌 현장 검증 성과 지원. <strong>서울특별시장 표창 수상</strong>에 핵심 개발자로 기여.</li>
    </ul>
  </div>

  <!-- 프로젝트 3 -->
  <div class="content-box">
    <h3>3. 무인매장 출입 및 근태 관리 통합 플랫폼</h3>
    <p style="color:#666; margin-bottom:10px;">2021.09 ~ 2023.05 | (주)크래프트 | 개발팀 팀장</p>
    <div class="project-tag-group">
      <span class="project-tag">Android Native</span>
      <span class="project-tag">Social Login SDK</span>
      <span class="project-tag">PHP</span>
      <span class="project-tag">MySQL</span>
      <span class="project-tag">Figma</span>
    </div>
    <p>무인매장의 상시 보안 출입 통제와 프랜차이즈 점주-근로자 간 실시간 근태 및 스케줄 관리를 연동한 스마트 매장 통합 플랫폼 구축을 리딩했습니다.</p>
    <p><strong>주요 업무 및 성과:</strong></p>
    <ul>
      <li><strong>출입 시스템 총괄 설계:</strong> QR코드 발급 및 스캔 기반의 실시간 매장 출입 게이트 제어 로직 기획 및 개발 총괄.</li>
      <li><strong>사용성 및 네이티브 연동 극대화:</strong> Kakao, Naver 등 주요 소셜 로그인 SDK 탑재를 통해 접근 장벽 완화 및 Figma를 활용해 직접 UI/UX를 기획하여 직관적인 점주용 어드민 웹과 연동 완료.</li>
      <li><strong>대용량 데이터 최적화:</strong> PHP API 서버 개발 및 수만 건 이상의 출입/근태 로그 적재를 위한 MySQL 데이터베이스 스키마 설계 및 인덱스 튜닝 수행.</li>
    </ul>
  </div>

  <!-- 프로젝트 4 -->
  <div class="content-box">
    <h3>4. 하이브리드 모바일 서비스 아키텍처 설계 및 고도화 (우리두리 등)</h3>
    <p style="color:#666; margin-bottom:10px;">2018.03 ~ 2021.04 | 아이에스이영어사 / 피플인넷 | 개발부 사원</p>
    <div class="project-tag-group">
      <span class="project-tag">Android Native</span>
      <span class="project-tag">In-app-browser</span>
      <span class="project-tag">PHP</span>
      <span class="project-tag">MySQL (Procedure/Trigger)</span>
      <span class="project-tag">Google Play Console</span>
    </div>
    <p>소개팅 플랫폼 '우리두리'를 비롯한 다수의 상용 하이브리드 앱의 안정적인 유지보수와 수익 구조 전환을 이끈 프로젝트입니다.</p>
    <ul>
      <li><strong>인앱 결제 안착:</strong> Google Play Billing Library 연동을 통한 유료 비즈니스 결제 모듈 시스템을 버그 없이 전면 고도화.</li>
      <li><strong>서버 로직 자동화:</strong> MySQL 내의 프로시저(Procedure) 및 트리거(Trigger) 기능을 도입·활용하여 복잡한 유저 매칭 데이터의 실시간 자동 갱신 아키텍처를 구축하고 서버 부하 최소화.</li>
      <li>안드로이드 스튜디오 기반의 안전한 웹뷰(WebView) 인터페이스 통신 프로토콜 정립 및 대규모 트래픽 대응을 위한 안정적인 PHP API 고도화.</li>
    </ul>
  </div>

  <!-- 프로젝트 5 -->
  <div class="content-box">
    <h3>5. 모바일 작업현황 보고 시스템</h3>
    <p style="color:#666; margin-bottom:10px;">2022 | 개인 프로젝트 (단독 개발)</p>
    <div class="project-tag-group">
      <span class="project-tag">Android Studio</span>
      <span class="project-tag">Java</span>
    </div>
    <ul>
      <li>공기업 현장 업무의 신속한 디지털 전환 및 수기 보고 체계의 데이터화를 목표로 한 안드로이드 Native 기반 스마트 보고서 앱 설계 및 단독 개발.</li>
      <li>대구경북 스타트업 페스티벌 <strong>공기업 대학생 부문 수상</strong> (한국가스공사 협업 트랙)을 통한 아이디어 및 기술력 공인 검증 완료.</li>
    </ul>
  </div>

  <h2>R&D · 공공 사업 및 품질인증 이력</h2>
  <div class="content-box">
    <p style="margin-top: 0; font-weight: bold; color: #007aff;">[정부부처 R&D 및 국가 공인 품질 인증 대응 기록]</p>
    <ul style="font-size: 0.95rem; padding-left: 20px; line-height: 2.0;">
      <li><strong>2024</strong> 과학기술정보통신부/NIPA 디지털인프라(SW) 종합 진단 사업 대응 (안전기능, 소스코드 보안성, DBMS 개선사항 반영 성공)</li>
      <li><strong>2024</strong> 인천국제공항공사 신기술 테스트베드 공모전 선정 및 현장 실증 테스트 완료</li>
      <li><strong>2024</strong> 경상북도 4차산업혁명 핵심기술개발 과제 (비대면 인공지능 시험 감독 모바일 시스템) 참여</li>
      <li><strong>2024</strong> 한국연구재단 양자기술개발 지원사업 기획 참여 및 양자 센싱 연계 서비스 아키텍처 설계 지원</li>
      <li><strong>2023</strong> 서울시/서울경제진흥원(SBA) 약자를 위한 기술개발 지원사업 최종 완수 및 <strong>서울특별시장 표창</strong> 달성</li>
      <li><strong>인증 역량</strong> 한국정보통신기술협회(TTA) 성능평가 통과, <strong>GS(Good Software) 인증 획득</strong> 기술문서 작성 및 대응 프로세스 총괄 수행</li>
      <li><strong>기타 대외 활동</strong> 스마트라이프위크(SLW), 월드IT쇼(WIS) 등 정보통신 주요 국제 박람회 참여 핵심 기술 시연 및 B2B 기술 교류 총괄</li>
    </ul>
  </div>

</div>
