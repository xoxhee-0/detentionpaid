# CLAUDE.md — detentionpaid (방: 마이크로 SaaS 수요 검증)

> 🏠 허브: `mission-control`. **새 세션은 허브를 먼저 읽고** 이 방으로 라우팅된다.
> 이 파일 = 이 방의 "기억". 작업 후 [현재 상태]/[의사결정 로그]를 갱신하고 허브의 `rooms/detentionpaid.md`도 동기화한다.

## 0. 운영 루프 (매 세션)
1. **읽기**: 이 파일 + `README.md` + `validation-tracker.md`
2. **실행**: 랜딩(`index.html`)/카피/게시글 수정 → git commit/push
3. **검증**: 트래픽 유입 → `validation-tracker.md`에 일일 기록
4. **기억 갱신**: 이 파일 + 허브 동기화 후 push

## 1. 정체 / 가설
- **아이디어**: 오너오퍼레이터/소형 운송사(미국)용 **detention-pay 청구 앱**.
  $19/월 폰 전용 — GPS 타임스탬프 자동 기록 → 원탭으로 브로커 제출용 청구서 생성
- **웨지**: 90%+ 운송사가 detention 청구하지만 50% 미만만 받음 (도착/출발 시각 *증명* 불가).
  기존 도구는 $5,000/년 엔터프라이즈거나 무거운 TMS 번들 → 1~3트럭 사업자 소외
- ⚠️ **제품 코드는 아직 0줄.** 지금은 **fake-door 수요 검증 단계** (만들기 전에 검증)

## 2. 자산 (현재)
- `index.html` — 랜딩(정적 단일 파일). **Formspree 연동 완료**: `https://formspree.io/f/mbdebjbp`
- `community-posts.md` — Reddit/Facebook/TikTok 유입 게시글 (광고 아닌 동료 드라이버 톤)
- `validation-tracker.md` — 일일 로그 + GO/NO-GO 결정 매트릭스
- 라이브: `https://xoxhee-0.github.io/detentionpaid/` (Settings→Pages 활성화 필요)

## 3. 검증 방법 / 합격선
1. `index.html` 호스팅 → 2. 이메일 캡처(Formspree 완료) → 3. `community-posts.md`로 300~500명 유입 → 4. tracker 기록 → 5. GO/NO-GO
- **진짜 신호 = "$19 사전예약" 버튼 클릭** (무료 이메일 가입 아님)

| 지표 | 🟢 GO | 🟡 Hold | 🔴 NO-GO |
|---|---|---|---|
| 이메일 전환 | 8%+ | 3-8% | <3% |
| $19 사전예약 클릭률 | 2%+ | 0.5-2% | ~0 |
| 정성 | "언제 나와요?" DM | 미지근 | 침묵/"이미 X 씀" |

## 4. 미해결 / 다음 (open loops)
- [ ] GitHub Pages 활성화 + 랜딩 라이브 확인
- [ ] `community-posts.md`로 300~500명 유입 (7일 운영)
- [ ] `validation-tracker.md` 일일 기록
- [ ] 7일 후 GO/NO-GO 판정 — NO-GO면 니치 전환

## 5. 핵심 원칙
- **제품 코드 짜기 전에 검증.** 매몰비용 만들지 말 것
- 무료 가입 ≠ 수요. **돈 낼 의향(사전예약 클릭)**만 진짜 신호
- 게시글은 광고 아닌 동료 톤 (계정 밴/거부감 회피)

## 6. 의사결정 로그
- 초기: 랜딩 + 게시글 + 트래커 검증 키트 구축, Formspree 연동
- 2026-06-16: 생태계 허브(mission-control)에 편입. CLAUDE.md 메모리 생성
- 2026-06-18: Competitor intel: freightproof.com appears pre-launch/waitlist, priced at $24.99/mo, with no visible traffic signal.
- 2026-06-18: Market demand signal is still lukewarm: Reddit validation signal around 3 comments, so do not overbuild before $19 preorder clicks.
- 2026-06-18: Positioning: DetentionPaid stays cheaper at $19/mo, validates first, and emphasizes no factoring lock-in/no $5k TMS/built by an owner-op.
