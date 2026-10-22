### 안녕하세요 👋 I'm hoehyeon

Seoul 기반 개발자. TypeScript · Python으로 업무 자동화와 사내 시스템(CRM, 메시징 연동, AI 상담 도구)을 만들고,
개인정보를 다루면서 **보안·프라이버시 도구**를 직접 만들어 오픈소스로 공개합니다.
관심사: **CVE 대응 · AI로 나가는 데이터 비식별화 · 컨테이너 보안**.

🔗 [LinkedIn](https://www.linkedin.com/in/hoehyeon)

---

#### 📦 Open Source

**[php2shell-check](https://github.com/hoehyeonlab/php-cve-2026-109618-check)** — PHP 사전인증 RCE
**CVE-2026-109618 / CVE-2026-109619** (php2shell, CVSS 9.2) 점검 도구. 호스트뿐 아니라 실행 중인
**Docker 컨테이너 안의 PHP까지** 찾아내는 읽기 전용 스캐너 + 실전 패치 가이드.
→ [awesome-container-security](https://github.com/kai5263499/awesome-container-security) 목록 등재. `Shell` · CI 통과 · MIT.

**[korean-pii-redact](https://github.com/hoehyeonlab/korean-pii-redact)** — 한국 개인정보(주민등록번호·사업자등록번호·전화번호·카드번호·이메일)를
LLM·로그·서드파티로 보내기 전에 비식별화하는 **의존성 없는** TypeScript 라이브러리.

```ts
redactPii("대표 010-1234-5678, 사업자 123-45-67890");
// → "대표 [연락처 비식별], 사업자 [사업자등록번호 비식별]"
```

#### 🛠 Stack

`TypeScript` `Next.js` `React` `Drizzle ORM` `PostgreSQL` `SQLite` `Python` `Shell` `Vitest` `GitHub Actions` `Docker`

#### 🔐 Security

제가 관리하는 프로젝트의 취약점은 각 저장소의 `SECURITY.md` 절차(GitHub 비공개 취약점 신고)로 알려 주세요.
