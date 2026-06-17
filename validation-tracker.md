# DetentionPaid — Validation Tracker

Goal: decide GO / NO-GO **before writing any product code.**
Run for ~7 days, aim for 300-500 visitors.

> ⚠️ **측정 갭 (트래픽 붓기 전 수정 필요):** 현재 랜딩은 "$19" 버튼도 "Reserve" 버튼도
> 전부 이메일 폼(`#join`)으로만 보냄 → **무료 이메일 가입만 측정되고, 진짜 신호인
> "$19 사전예약 클릭"이 안 잡힘.** 별도 $19 의향 경로(intent 필드/2nd form)를 붙여야 함.

## Daily log (Day1 = 2026-06-17, ~7일)

| Date | Source posted | Visitors | Email signups | "$19 Pre-order" clicks | Notes / quotes |
|------|---------------|---------:|--------------:|----------------------:|----------------|
| 06-17 (D1) | Reddit story #1 (1개 서브레딧) |  |  |  |  |
| 06-18 (D2) | 기존 detention 스레드 댓글 ×2-3 |  |  |  |  |
| 06-19 (D3) | Facebook 그룹 (1개씩) |  |  |  |  |
| 06-20 (D4) | TikTok/YouTube 댓글 |  |  |  |  |
| 06-21 (D5) | TikTok/YouTube 댓글 |  |  |  |  |
| 06-22 (D6) | (여력 시 2번째 서브레딧) |  |  |  |  |
| 06-23 (D7) | 집계 + GO/NO-GO 판정 |  |  |  |  |

## Totals
- Visitors: ____
- Email signups: ____  → conversion = signups / visitors = ____%
- Pre-order clicks: ____  → = clicks / visitors = ____%

## Decision matrix

| Metric | 🟢 GO (build it) | 🟡 Hold (iterate copy) | 🔴 NO-GO (switch niche) |
|--------|------------------|------------------------|-------------------------|
| Email conversion | 8%+ | 3-8% | under 3% |
| "$19 Pre-order" click rate | 2%+ | 0.5-2% | ~0 |
| Qualitative | "when is this out?" DMs | lukewarm | silence / "already use X" |

## How to measure
- **Visitors**: enable analytics on the host (Carrd has it built in, or add a free Plausible/Umami snippet, or just use the click counts from Reddit/Bitly).
- **Email signups**: count from Formspree / Mailchimp dashboard.
- **Pre-order clicks**: make the "Reserve my spot" button go to a 2nd page (or a Stripe payment link) and count clicks there — this separates "sounds nice" from "I'd actually pay."

## Rule
Free signups lie. The real signal is someone clicking the **$19 pre-order**.
Even a handful of those from ~400 visitors = green light.
