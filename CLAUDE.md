# claude-meeting-report

## hwpx 스킬 실행 환경

`.claude/skills/hwpx` 스크립트는 Python 3.12 이상이 필요하다. 시스템 python3(3.8)이 아니라
프로젝트 가상환경을 쓴다.

```bash
.venv/bin/python .claude/skills/hwpx/scripts/one_shot.py --example official-letter
```

의존성(lxml, jsonschema, Pillow, python-hwpx)은 `.venv`에 설치돼 있다.
