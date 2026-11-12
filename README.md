# 🚜 중장비 대탐험

공사장에서 일하는 힘센 중장비 8대를 사진으로 소개하는, 아이를 위한 한 장짜리 웹페이지입니다.

**보러 가기 → https://edhan1984-byte.github.io/heavy-machines/**

## 들어 있는 것

| 기계 | 영어 이름 |
|---|---|
| 굴착기 | Excavator |
| 불도저 | Bulldozer |
| 덤프트럭 | Dump Truck |
| 크레인 | Crane |
| 레미콘 | Mixer Truck |
| 로드롤러 | Road Roller |
| 휠로더 | Wheel Loader |
| 지게차 | Forklift |

각 기계마다 실제 사진 한 장, 하는 일 한 줄 설명, 그리고 "알고 있니?" 토막 상식이 붙어 있습니다.
맨 아래에는 사진을 보고 이름을 고르는 **이름 맞히기 퀴즈**(8문제)가 있습니다.

## 기술 메모

- 빌드 과정이 없는 정적 HTML 한 장입니다. `index.html`을 브라우저로 열면 바로 보입니다.
- 외부 의존성은 Google Fonts(Jua / Noto Sans KR)뿐이고, 사진은 모두 `img/`에 들어 있습니다.
- 카드와 퀴즈는 `index.html` 안의 `MACHINES` 배열 하나로 만들어집니다. 기계를 추가하려면
  `img/`에 1400×875 사진을 넣고 배열에 항목 하나만 더하면 됩니다.
- 라이트/다크 모드를 `prefers-color-scheme`로 자동 전환하고, `prefers-reduced-motion`을 존중합니다.

## 사진 출처

모든 사진은 위키미디어 공용(Wikimedia Commons)의 자유 이용 가능 이미지이며,
저작자와 라이선스는 페이지 하단 '사진 출처'에 표시되어 있습니다.

- 퍼블릭 도메인: 굴착기(U.S. Navy / Jacob McBride)
- CC0: 불도저(Alf van Beem), 덤프트럭(AlfvanBeem)
- CC BY 3.0 DE: 레미콘(High Contrast)
- CC BY-SA 4.0: 크레인(Tbatb), 로드롤러(Marc-Lautenbacher), 휠로더(めどい), 지게차(Mrbobax)
