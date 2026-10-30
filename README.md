# probe-harness

SK하이닉스 AI 해커톤 2026 2차 예선에서 Codex와 작업할 때 쓰는 개인 작업 지침입니다. 정답이나 결과물 코드는 없습니다.

- `AGENTS.md`: 작업 지침 (Codex가 자동으로 읽음)
- `AGREEMENTS.md`: 내가 정하거나 승인한 요구사항·가정·미결·진행 상황 (현재 상태)

## 사용

clone한 폴더를 그대로 작업 폴더로 씁니다. 결과물이 이 저장소로 올라가지 않도록 원격 연결을 먼저 끊습니다.

```bash
git clone https://github.com/Chiman2937/probe-harness ~/app
cd ~/app && git remote remove origin
codex
```

Codex를 켜면 `/model`에서 **6.1 Sol**, 추론 강도 **medium**을 고르고 `/status`로 확인합니다.
