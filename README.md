# probe-harness

SK하이닉스 AI 해커톤 2026 2차 예선에서 Codex와 작업할 때 쓰는 개인 작업 지침입니다. 정답이나 결과물 코드는 없습니다.

- `AGENTS.md`: 작업 지침 (Codex가 자동으로 읽음)
- `AGREEMENTS.md`: 내가 정하거나 승인한 요구사항·가정·미결·진행 상황 (현재 상태)

## 사용

과제 파일이 있는 작업 폴더 루트에서 두 파일만 받습니다. 과제 `README.md`를 덮어쓰지 않도록 이 저장소의 README는 받지 않습니다.

```bash
curl -fsSO https://raw.githubusercontent.com/Chiman2937/probe-harness/main/AGENTS.md
curl -fsSO https://raw.githubusercontent.com/Chiman2937/probe-harness/main/AGREEMENTS.md
```

`git status`로 확인해 git 저장소가 아니면 만들고 첫 커밋을 남긴 뒤 Codex를 켭니다.

```bash
git init && git add -A && git commit -m "chore: 과제 파일과 작업 지침"
codex
```

Codex를 켜면 `/model`에서 **6.1 Sol**, 추론 강도 **medium**을 고르고 `/status`로 확인합니다.
