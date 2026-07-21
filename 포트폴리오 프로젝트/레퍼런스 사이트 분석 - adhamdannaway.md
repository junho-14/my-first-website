# 레퍼런스 포트폴리오 분석: adhamdannaway.com

- 분석 대상: https://www.adhamdannaway.com/
- 분석 방식: WebFetch를 통한 텍스트/구조 추출 기반 (색상 hex, font-family, 애니메이션 동작 등 순수 시각 요소는 스크린샷 없이 확인 불가 — 필요 시 스크린샷 기반 재분석 가능)

## 1. 첫인상 분석
- 히어로가 "designer" / "coder" 이중 정체성 토글로 구성되어 있어, 3초 안에 "UI 디자인도 하고 코딩도 하는 사람"이라는 포지셔닝이 명확히 전달됨.
- 중앙 프로필 사진 + 두 줄 헤드라인(디자이너 설명 / 개발자 설명) 구조로, 시선이 "사람(얼굴) → 정체성 문구" 순으로 흐르도록 설계된 것으로 보임.
- 톤앤매너는 무겁지 않고 유쾌함: "Swearing at my computer", "Eating pizza"를 스킬처럼 나열하는 자기소개는 전형적인 포트폴리오의 딱딱함과 거리가 멂.

## 2. 디자인 요소 분석 (제한적)
- 색상 hex 값, font-family 선언은 텍스트 추출로 확인 불가.
- 구조적으로 유추 가능한 것: WordPress 기반("dannaway" 테마), `.webp` 이미지 사용 → 최신 포맷 최적화에 신경 쓴 흔적.
- 레이아웃/여백/시각적 계층은 스크린샷 없이는 신뢰성 있게 판단하기 어려움.

## 3. UX 분석
- 내비게이션: about / learn / portfolio / blog / contact — 5개 항목의 플랫 구조로 매우 직관적.
- 정보구조 흐름이 논리적: **about(사람)** → **learn(책/전문성 콘텐츠)** → **portfolio(증거)** → **blog** → **contact(전환)**. "나는 누구인가 → 얼마나 잘하는가 → 실제로 뭘 만들었는가 → 연락"으로 이어지는 설득 퍼널.
- "designer"/"coder" 라벨 구조상 호버·탭 전환 인터랙션이 있을 가능성이 높지만, 텍스트 구조로부터의 추정이며 실제 동작은 미확인.
- 모바일 반응형 수준은 확인 불가.

## 4. 콘텐츠 전략 분석
- 자기소개: "based in sunny Sydney, Australia. Since 2005..." — 지역성 + 경력 연차(20년 이상)를 자연스럽게 노출.
- 스킬 표기가 독특함: Figma 95%, Design Systems 90% 같은 진짜 역량과 Tea drinking 95%, Calisthenics 40% 같은 유머를 나란히 배치 — 전문성은 유지하면서 인간적인 매력을 더하는 브랜딩 장치.
- 프로젝트가 16개로 다양한 카테고리(디자인 시스템, 저서, 스피킹, 대기업 제품 디자인 - Qantas, 브랜드/웹사이트 디자인 - Freelancer.com·Quest Research·HRHR·Petra Capital, 사이드 프로젝트)를 아우름 → 실무 역량 + 사고 리더십(저서/스피킹) + 대기업 레퍼런스를 동시에 보여주는 다층적 신뢰 구조.
- CTA: `/contact` 페이지는 존재하지만, 추출된 범위에서 강력한 CTA 문구("Let's work together" 류)는 확인되지 않음 — 실제로 약할 수도, 텍스트 추출 한계일 수도 있어 단정하기 어려움.

## 5. 장점과 개선점

**강점 3가지**
1. 뚜렷한 퍼스널 브랜드 보이스(유머 + 이중 정체성)로 기억에 남음
2. Qantas 등 대기업 클라이언트 + 저서 출간 + 컨퍼런스 스피킹이라는 3중 신뢰 증거
3. 5개 메뉴의 단순한 IA로 탐색 부담이 낮음

**개선 가능 지점**
- 프로젝트 16개가 카테고리 태그만으로는 임팩트(수치, 성과)가 잘 드러나지 않을 수 있음 — 스캔 시 프로젝트 간 차별점 파악이 어려울 수 있음
- 눈에 띄는 강한 CTA 문구 부재(단순 메뉴 항목 수준)
- 시각 디자인 완성도는 별도 확인 필요

**적용 아이디어**
- "실무 역량 + 유머러스한 자기소개"의 조합, "사람 → 증거 → 전환" 순의 정보 흐름은 my-portfolio에도 참고할 만함
- 현재 my-portfolio의 Home 구성(Hero → About → Skill → Projects → Contact → Guestbook)이 이미 유사한 퍼널을 갖고 있음

## 6. 타겟 분석
- **목표 직무**: 시니어~리드급 Product/UI Designer, 특히 디자인 시스템 전문성 + 프론트엔드 구현력을 동시에 요구하는 포지션
- **경력 수준**: 2005년부터 활동, 대기업(Qantas) 프로젝트 경험과 저서·스피킹 경력으로 보아 10년 이상 시니어~수석급으로 판단됨
- **효과적인 이유**: 유머와 인간미를 살린 브랜딩은 컬처핏을 중시하는 스타트업/에이전시 채용에 특히 강점이 있고, 동시에 대기업 클라이언트 레퍼런스로 실력 검증까지 겸비. 다만 매우 보수적인 대기업 채용 담당자에게는 다소 캐주얼하게 느껴질 여지도 있음

## 참고: 추출된 원문 콘텐츠

**Hero / About**
> "I'm a product designer based in sunny Sydney, Australia. Since 2005, I've enjoyed turning complex problems into simple, beautiful and intuitive designs."

**역할 설명**
- Product designer specialising in UI design and design systems.
- Front end developer who writes clean, elegant and efficient code.

**스킬 (일부)**
- Tea drinking: 95%
- Design Systems: 90%
- Figma: 95%
- Gardening: 75%
- Calisthenics: 40%

**네비게이션**: about / learn / portfolio / blog / contact

**프로젝트 목록**
1. My Figma design system — 디자인 시스템
2. My UI design book — 책
3. Creating a lean design system — 디자인 시스템
4. Interior design news feed — 사이드 프로젝트
5. Qantas map search — 제품 디자인
6. Qantas homepage refresh — 웹사이트 디자인
7. Rethinking flight search — 스피킹 이벤트
8. Monitor app design — iPhone 앱 디자인
9. Subscriber notification emails — 제품 디자인
10. Quest Research redesign — 브랜드 & 웹사이트 디자인
11. Segment builder design — 제품 디자인
12. Growth Giant website — 사이드 프로젝트
13. Growth Giant A/B testing tool — 사이드 프로젝트
14. Freelancer.com brand & UX design — 브랜드 & UX 디자인
15. HRHR brand & website design — 브랜드 & 웹사이트 디자인
16. Petra Capital brand & website design — 브랜드 & 웹사이트 디자인
