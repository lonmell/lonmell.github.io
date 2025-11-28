---
layout: default
title: 안드로이드 개발자 방창배 포트폴리오
---
<style>
  /* Slate 테마의 기본 콘텐츠 폭을 조금 넓혀줌 */
  .wrapper {
    max-width: 1100px;  /* 필요하면 1000~1200 사이로 숫자 조절 */
  }
</style>
<div style="margin-bottom:24px;">
  <div
    style="
      padding:16px 20px;
      background:#ffffff;
      border-radius:12px;
      border:1px solid #e5e7eb;
      box-shadow:0 4px 10px rgba(0,0,0,0.03);
    "
  >
    <!-- 위: 프로필 이미지 + 이름 한 줄 -->
    <div style="display:flex; align-items:center; gap:12px; margin-bottom:8px;">
      <img src="images/profile_img.png"
           alt="안드로이드 개발자 방창배 프로필 이미지"
           style="width:72px; height:72px; border-radius:50%; object-fit:cover;">
      <h1 style="margin:0;">Android & Mobile Developer</h1>
    </div>
    <!-- 아래: 소개 문장 + 연락처 -->
    <p style="margin:0 0 8px 0; font-size:0.95rem;">
      약 7년간 안드로이드 앱을 개발해 왔으며,<br>
      이 중 최근 3년은 시각장애인 보조기기·모바일 서비스와 공공 R&amp;D 과제에 집중하고 있습니다.
    </p>
    <p style="margin:0; font-size:0.95rem;">
      <strong>이메일</strong>:
      <a href="mailto:lonmell0213@gmail.com">lonmell0213@gmail.com</a><br>
      <strong>GitHub</strong>:
      <a href="https://github.com/lonmell" target="_blank" rel="noopener noreferrer">
        방창배 깃 허브로 이동
      </a>
    </p>

  </div>
</div>

---
<div
  style="
    display:flex;
    flex-wrap:wrap;
    gap:16px;
    align-items:flex-start;
    margin-bottom:24px;
  "
>

  <!-- 왼쪽 칼럼: 소개 / 기술 스택 / 대표 프로젝트 -->
  <div style="flex:2 1 360px;">

    <h2>소개</h2>
    <p>
      초기에는 일반 기업용·교육용 모바일 서비스를 중심으로 안드로이드 앱을 개발했고,
      최근 3년간은 시각장애인 보조기기와 교육·평가 솔루션을 중심으로
      안드로이드 기반 모바일 서비스를 설계하고 개발해 왔습니다.
    </p>
    <p>
      단순히 화면과 기능을 만드는 것을 넘어, 실제 사용자 환경에서 안정적으로 동작하는지와
      시각장애인을 포함한 사용자가 얼마나 쓰기 쉬운지(접근성)를 중요하게 생각합니다.
      특히 「약자를 위한 기술개발 지원사업」을 통해 시각장애인의 의사소통 및 실내 이동을
      지원하는 서비스를 상용화하는 데 참여했고, 그 공로로 서울특별시장 표창을 수상했습니다.
      이 경험을 바탕으로, 사회적 약자를 돕는 기술과 공공 R&amp;D 과제에서 요구하는 품질 기준
     (TTA, GS인증 등)을 함께 고려하는 개발을 지향하고 있습니다.
    </p>

    <h2>기술 스택</h2>
    <h3 style="margin-bottom:4px;">Language</h3>
    <ul>
      <li>Java (Android)</li>
      <li>Kotlin (기초/경험)</li>
      <li>Dart (Flutter 경험)</li>
      <li>PHP (간단한 API 개발)</li>
    </ul>

    <h3 style="margin-bottom:4px;">Mobile / Framework</h3>
    <ul>
      <li>Android Native (Camera2, View, Service 등)</li>
      <li>BLE / iBeacon 연동</li>
      <li>Retrofit 기반 REST API 연동</li>
      <li>FCM(Push), TTS, SpeechRecognizer(음성 인식)</li>
      <li>Flutter (기본 화면 및 간단 앱 개발 경험)</li>
    </ul>

    <h3 style="margin-bottom:4px;">기타</h3>
    <ul>
      <li>Git / GitHub</li>
      <li>MySQL / MariaDB 연동</li>
      <li>Notion / Jira 등 협업 도구</li>
    </ul>

    <h2>대표 프로젝트</h2>

    <h3>HatioEye – 시각장애인 보조·실내 내비게이션 앱</h3>
    <p style="font-size:0.9rem; color:#4b5563;">
      기간: 2023.05 ~ 진행 중 · 역할: 안드로이드 앱 개발 / 핵심 기능 설계
    </p>
    <p>
      시각장애인이 실내에서 안전하게 이동하고, 주변 텍스트와 사물 정보를 음성으로 안내받을 수 있도록 돕는
      보조기기 및 안드로이드 앱입니다. 웨어러블 디바이스와 스마트폰을 연동해
      실내 내비게이션, 문자 인식, 사물/환경 인식 기능을 제공합니다.
    </p>
    <ul>
      <li>안드로이드 앱 전체 구조 설계 및 핵심 화면/기능 개발</li>
      <li>BLE / iBeacon 기반 실내 내비게이션 로직 및 TTS 음성 안내 기능 구현</li>
      <li>Camera2 기반 카메라 프리뷰·촬영 및 서버 업로드, 인식 결과 수신·안내 흐름 구현</li>
      <li>시각장애인을 고려한 제스처 기반 메뉴, 음성 안내·음성 명령 인터랙션 설계</li>
      <li>예외 상황(네트워크/센서 등)을 고려한 안정성 개선 및 오류 처리</li>
    </ul>

    <h3>모바일 작업현황 보고 시스템</h3>
    <p style="font-size:0.9rem; color:#4b5563;">
      기간: 2022 · 역할: 안드로이드 앱 단독 개발
    </p>
    <p>
      공기업 현장의 작업·안전 관련 정보를 하루 전 수기/엑셀로 취합하던 방식을 개선하기 위해,
      스마트폰에서 작업 현황을 간편히 등록·조회할 수 있도록 만든 안드로이드 앱입니다.
    </p>
    <ul>
      <li>요구사항을 바탕으로 전체 화면 구조 및 데이터 흐름 설계</li>
      <li>작업 일정, 작업 유형(위험 공종 등) 입력·조회 화면 및 리스트 UI 구현</li>
      <li>REST API 연동을 가정한 작업 데이터 전송·조회 로직 설계</li>
      <li>현장 사용성을 고려한 간단한 입력 UX, 필수 정보 중심 화면 구성</li>
    </ul>

  </div>

  <!-- 오른쪽 칼럼: 경력 요약 / R&D / 수상 -->
  <div style="flex:1.2 1 260px;">

    <h2>경력 요약</h2>
    <ul>
      <li>총 7년 안드로이드 개발 경력
        <br>(일반 모바일 서비스·업무 시스템 개발 4년 + 시각장애인 보조기기·교육/평가 솔루션 개발 3년)</li>
      <li>최근 3년간 시각장애인 보조기기(HatioEye) 및 관련 공공 R&amp;D 과제 중심으로 개발 수행</li>
      <li>TTA 성능평가, GS인증, ISO9001, Inno-Biz 등 품질·인증 대응 경험</li>
      <li>시각장애인 보조기기 하티오아이 PH 출시·조달 등록, CES 2025 출품 등 상용화 과정에 기술 기여</li>
    </ul>

    <h2>R&amp;D · 공공 사업 참여</h2>
    <ul>
      <li>2023 약자를 위한 기술개발 지원사업 – 시각장애인 의사소통·실내이동지원 스마트 서비스 상용화(WW230076)</li>
      <li>2024 디지털인프라(SW) 종합 진단 및 개선 사업(정보통신산업진흥원, TTA/NIPA)</li>
      <li>2024 경상북도 4차산업혁명 핵심기술개발사업 – 온라인 비대면 시험 감독 시스템 개발 참여</li>
      <li>2024 양자기술개발 지원사업(기획지원) – 양자센싱 기반 시각장애인 웨어러블 디바이스 개발 기획 참여</li>
      <li>2024 인천공항 신기술 테스트베드 공모전 선정 – 시각장애인 보조기기 ‘하티오아이’ 실증 기술 지원</li>
      <li>스마트라이프위크, 디지털미디어테크쇼, 월드IT쇼, CES 2025 등 전시·박람회 데모 및 기술 지원</li>
    </ul>

    <h2>수상 및 인증</h2>
    <ul>
      <li>서울특별시장 표창 – 약자를 위한 기술개발 지원사업 우수성과 (2024)</li>
      <li>대구경북 스타트업 페스티벌 공기업 대학생 부문 수상 – 모바일 작업현황 보고 앱 (2022)</li>
      <li>한국교통안전공단 소셜벤처 선정 (2021)</li>
      <li>소프트웨어 품질인증(GS인증) 1등급 대상 서비스 개발·인증 대응 참여</li>
    </ul>

  </div>

</div>
