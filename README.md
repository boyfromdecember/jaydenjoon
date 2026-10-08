# 논문 작성 / 심사 도구 모음

오픈소스 AI 논문 작성·심사 도구를 `git submodule`로 받아 둔 저장소입니다.

```bash
git clone --recurse-submodules <this-repo>
# 이미 클론했다면
git submodule update --init --depth 1
```

## 논문 작성 (`tools/writing/`)

| 도구 | 설명 |
|---|---|
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | Sakana AI. 아이디어 → 실험 → LaTeX 논문 작성까지 자동화. 내장 리뷰어 포함 |
| [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) | 문헌조사·실험·보고서(논문) 작성 에이전트 파이프라인 |
| [STORM](https://github.com/stanford-oval/storm) | Stanford. 주제 조사 후 인용 포함 장문 서베이/아티클 작성 |

## 논문 심사 (`tools/review/`)

| 도구 | 설명 |
|---|---|
| [OpenAIReview](https://github.com/ChicagoHAI/OpenAIReview) | UChicago. 섹션 단위로 논문을 읽고 상세 피드백 생성 |
| [OpenReviewer](https://github.com/maxidl/openreviewer) | ML 학회 리뷰로 파인튜닝한 8B 리뷰 모델 (NAACL 2025 demo) |
| [PaperJury](https://github.com/u7079256/paperjury) | 투고 전 리뷰 스트레스 테스트용 Claude Code 스킬 (review → verdict → revise → verify) |

각 도구의 설치·API 키 설정은 해당 폴더의 README를 참고하세요.
