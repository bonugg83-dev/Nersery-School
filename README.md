# 어린이집 아동별 하루 활동일지 작성 도우미

선생님이 아동별 활동 키워드만 입력하면, Claude가 명단 순서대로 아동을 안내하고 선생님 말투로 복사하기 쉬운 활동일지를 써 주는 프로젝트입니다.

## 파일 구성

| 파일 | 용도 | 선생님이 할 일 |
|---|---|---|
| [INSTRUCTIONS.md](INSTRUCTIONS.md) | Claude 프로젝트 Instructions에 붙여 넣을 지침 | 그대로 붙여 넣기 |
| [knowledge/01-roster.md](knowledge/01-roster.md) | 아동 명단 | 실제 명단 채우기 |
| [knowledge/02-tone-samples.md](knowledge/02-tone-samples.md) | 말투 참고 예시 | 실제 활동일지 예시 10~20개 넣기 |
| [knowledge/03-writing-rules.md](knowledge/03-writing-rules.md) | 작성 규칙 | 우리 반 규칙·금지 표현 다듬기 |
| [knowledge/04-keyword-template.md](knowledge/04-keyword-template.md) | 키워드 입력 양식 | 참고용 |
| [docs/project-plan.md](docs/project-plan.md) | 원본 계획서 | 참고용 |

## 사용 방법

1. `INSTRUCTIONS.md`의 코드 블록 내용을 Claude 프로젝트 Instructions에 붙여 넣습니다.
2. `knowledge/` 폴더의 파일을 채워 프로젝트 Knowledge에 올립니다.
3. 매일 대화창에 `오늘 활동일지 시작`이라고 입력합니다.
4. 안내된 아동의 키워드를 입력하고, 나온 결과를 복사 버튼(또는 Ctrl+C)으로 복사해 붙여 넣습니다.

Claude는 컴퓨터 클립보드에 직접 복사할 수 없으므로, 결과를 설명 없이 코드 블록 하나로만 내보내 복사 한 번이면 끝나도록 했습니다.
