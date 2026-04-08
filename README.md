## 🤝 협업 규칙 (Collaboration Rules)

### 1. 작업 흐름 (Workflow)
우리 프로젝트는 다음 단계를 엄격히 준수합니다.
1. **학습 및 기획**: Notion 팀 스페이스에 공부한 내용이나 구현할 기능을 정리합니다.
2. **AI 검토**: 정리된 내용을 AI(Gemini/ChatGPT 등)에게 공유하여 Spring 핵심 로직, 주의사항, 테스트 케이스를 분석받습니다.
3. **이슈 생성**: 분석된 내용을 바탕으로 GitHub Issue를 발행합니다.
4. **브랜치 생성**: `feature/#이슈번호` 형식으로 브랜치를 생성합니다.
5. **코드 작성 및 PR**: 작업 완료 후 `develop` 브랜치로 Pull Request를 보냅니다. (최소 1명 이상의 승인 필요)

### 2. 브랜치 전략 (Branch Strategy)
- `main`: 제품 배포용 (가장 안정적인 상태)
- `develop`: 다음 출시 버전을 위한 개발 브랜치
- `feature/#123`: 기능 구현 브랜치 (Issue 번호와 연동)

### 3. 커밋 메시지 규약 (Commit Convention)
- `Feat`: 새로운 기능 추가
- `Fix`: 버그 수정
- `Docs`: 문서 수정 (README, Wiki 등)
- `Refactor`: 코드 리팩토링
- `Study`: 학습 내용 기록 및 배포용 코드 작업


