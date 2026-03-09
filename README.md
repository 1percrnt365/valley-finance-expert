# Valley Finance Expert (Gemini CLI Skill)

밸리 AI(Valley AI)의 핵심 글쓰기 원칙인 **'데이터 기반 분석(Evidence-based)'**과 **'양면적 시각(Bull vs Bear)'**을 완벽하게 구현하는 Gemini CLI 전용 금융 보고서 작성 서브에이전트입니다.

## 🚀 주요 기능
- **데이터 중심 분석**: 감정적인 의견 배제, 재무제표 및 TAM 등 객관적 수치 기반 리포팅
- **Bull vs Bear 프레임워크**: 상승 논리와 하락 위험을 균형 있게 제시하는 양면적 분석
- **실전 투자 전략**: 구체적인 티커($) 사용 및 포트폴리오 비중, RSI 매수 타점 등 액션 플랜 제공
- **커뮤니티 지향**: 독자의 피드백과 토론을 유도하는 밸리 AI 특유의 문체 적용

## 📂 파일 구조
- `SKILL.md`: 스킬의 핵심 정의 및 워크플로우
- `references/style-guide.md`: 밸리글 작성법 원칙 (데이터 우선, 양면성, 티커 사용)
- `references/report-template.md`: 표준 금융 보고서 템플릿 (서론-본론-결론)

## 🛠️ 설치 및 사용법

### 설치 (Installation)
이 리포지토리를 클론한 후 Gemini CLI에서 다음 명령어를 입력하세요.

```powershell
# 1. 스킬 링크 (심볼릭 링크)
gemini skills link [리포지토리_경로]

# 2. 스킬 목록 새로고침
/skills reload
```

### 사용 예시 (Usage)
Gemini CLI 프롬프트에서 다음과 같이 요청하세요.

> "밸리 스타일로 $TSLA 분석 보고서 써줘"
> "애플($AAPL)의 향후 전망을 밸리글 작성법에 맞춰서 작성해줘"

## 📝 라이선스
MIT License
