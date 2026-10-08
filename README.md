### 안녕하세요 👋

TypeScript · Python으로 업무 자동화와 사내 시스템(CRM, 메시징 연동, AI 상담 도구)을 만듭니다.
개인정보를 다루는 서비스를 만들면서 **AI로 나가는 데이터의 비식별화**와 **자격증명 암호화** 같은 보안 설계에 관심을 두고 있습니다.

#### 📦 Open Source

**[korean-pii-redact](https://github.com/hoehyeonlab/korean-pii-redact)** — 한국 개인정보(주민등록번호·사업자등록번호·전화번호·카드번호·이메일)를
LLM·로그·서드파티로 보내기 전에 비식별화하는 의존성 없는 TypeScript 라이브러리. (Security Maintainer)

```ts
redactPii("대표 010-1234-5678, 사업자 123-45-67890");
// → "대표 [연락처 비식별], 사업자 [사업자등록번호 비식별]"
```

#### 🛠 Stack

`TypeScript` `Next.js` `React` `Drizzle ORM` `PostgreSQL` `SQLite` `Python` `Vitest` `GitHub Actions` `Docker`

#### 🔐 Security

제가 관리하는 프로젝트의 취약점은 각 저장소의 `SECURITY.md` 절차(GitHub 비공개 취약점 신고)로 알려 주세요.
