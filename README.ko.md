# TRIZ 모순 해결 엔진

**TRIZ 기반 모순 엔진: 40개 발명원리를 통한 기술적·전략적 트레이드오프 해결.**

> 🇺🇸 [English README](./README.md)

## 사전 요구사항

- **Claude Cowork 또는 Claude Code** 환경

## 목적

두 요구사항이 충돌할 때 — A를 개선하면 B가 악화됨 — 체계적 방법 없이는 막힙니다. triz는 모순을 구조화하고 입증된 발명원리를 적용하여 명백하지 않은 해결안을 찾습니다. 40개 발명원리, 4개 분리원칙, 시스템 진화법칙을 5단계 파이프라인으로 통합합니다.

## 사용 시점 및 방법

진정한 트레이드오프가 진행을 막을 때 호출하세요. 기존 접근이 실패했을 때 가장 효과적입니다. 입력: 충돌하는 요구사항. 산출: TRIZ 원리에 매핑된 순위 해결안 방향, 더하기 시스템 진화 예측.

## 사용 예시

| 상황 | 프롬프트 | 결과 |
|---|---|---|
| 속도 vs. 품질 | `"3배 빠르게 출시하되 품질 지표 저하"` | 기술적 모순→발명원리→비용/타임라인 기준 순위 해결안 |
| 비용 vs. 품질 | `"비용 30% 감축하면서 프리미엄 사양 유지"` | 분리원칙→발명원리→진화 예측 |
| 확장 vs. 커스터마이징 | `"100개 고객 수요를 100개 구현 없이 커버하는 플랫폼"` | 모듈성 + 범용성→S-Curve 예측 |

## 핵심 기능

- 5단계 파이프라인: 정의 → 분류 → 매칭 → 생성 → 검증
- 도메인 어댑터가 있는 40개 발명원리
- 4개 분리원칙: 공간, 시간, 조건 기반, 규모 기반
- 다음 단계 예측을 위한 시스템 진화법칙
- 이상적 최종 결과 대비 이데알성 점수

## 연관 스킬

- **[planning-skill](https://github.com/jasonnamii/planning-skill)** — 창의적 점프 단계에서 모순 해결
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — 전략적 모순 구조화
- **[trigger-dictionary](https://github.com/jasonnamii/trigger-dictionary)** — 구조화된 프로토콜로 접근
## 설치

```bash
git clone https://github.com/jasonnamii/triz.git ~/.claude/skills/triz
```

## 업데이트

```bash
cd ~/.claude/skills/triz && git pull
```

`~/.claude/skills/`에 배치된 스킬은 Claude Code 및 Cowork 세션에서 자동으로 사용할 수 있습니다.

## Cowork 스킬 생태계

25개 이상의 커스텀 스킬 중 하나입니다. 전체 카탈로그: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## 라이선스

MIT 라이선스 — 자유롭게 사용, 수정, 공유하세요.
