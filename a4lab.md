## Git 초기 셋팅 안내

```
git clone https://github.com/A4LAB-INTERN/ragflow-agent.git
cd ragflow-agent
git remote add upstream https://github.com/infiniflow/ragflow.git
git remote set-url --push upstream DISABLE
git remote -v
```

아래처럼 보여야 됨

```
origin  https://github.com/A4LAB-INTERN/ragflow-agent.git (fetch)
origin  https://github.com/A4LAB-INTERN/ragflow-agent.git (push)
upstream        https://github.com/infiniflow/ragflow.git (fetch)
upstream        DISABLE (push)
```

- origin: 회사 공식 저장소 (push 가능)
- upstream: RAGFlow 원본 저장소 (fetch only)

⚠️ upstream push는 금지됩니다.

---

