# Valley Finance Expert (Gemini CLI Skill)

밸리 AI(Valley AI)의 핵심 글쓰기 원칙인 **'데이터 기반 분석(Evidence-based)'**과 **'양면적 시각(Bull vs Bear)'**을 완벽하게 구현하는 Gemini CLI 전용 금융 보고서 작성 서브에이전트입니다.

## 🚀 주요 기능
- **고품질 심층 분석**: 최소 3,000 ~ 5,000자 이상의 상세 보고서 작성 (요약 지양)
- **거점 분석 (Macro-Deep Dive)**: 산업 전반의 거시 경제 흐름(인플레이션, 금리, 지정학 등) 800자 이상 심층 분석
- **데이터 중심 5중 분석**: Bull/Bear 케이스별 각각 5가지 이상의 구체적인 데이터 기반 근거 제시
- **시나리오 기반 대응 (Bull/Neutral/Bear)**: 확률 기반 3대 시나리오 설계 및 각 상황별 포트폴리오 비중 제안
- **기술적 분석 통합**: RSI, 지지/저항선 등 실전 차트 분석 지표 포함
- **밸리 AI 특유의 문체**: 독자의 피드백과 토론을 유도하는 커뮤니티 지향적 서술 방식

## 📂 파일 구조
- `SKILL.md`: 스킬의 핵심 정의 및 워크플로우
- `references/style-guide.md`: 고품질 밸리글 작성 원칙 (3천자 이상, 5대 근거, 매크로 분석)
- `references/report-template.md`: 상세 금융 보고서 템플릿 (V2.0 - 시나리오 및 기술적 분석 포함)

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
