<div align="center">

<a href="https://carryon-app.pages.dev"><img src="https://carryon-app.pages.dev/img/icon.png" width="96" alt="CarryOn app icon, a sea otter" /></a>

# CarryOn

### Keep every AI coding session going.

A free macOS menu-bar app for people who run many **Claude Code, Codex and Aside** sessions at once.  
See how full each session's context is, then back it up and compact it in place, so the work carries on.

**[⬇ Download for macOS](https://github.com/morningverse67-wq/carryon-app/releases/latest)** &nbsp;·&nbsp; [Website](https://carryon-app.pages.dev) &nbsp;·&nbsp; v1.4.0 &nbsp;·&nbsp; macOS 14+ · Apple silicon & Intel · Free

```sh
curl -fsSL https://carryon-app.pages.dev/install.sh | sh
```

<a href="https://carryon-app.pages.dev">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/morningverse67-wq/carryon-app/main/docs/img/en-wide-dark.webp" />
    <img src="https://raw.githubusercontent.com/morningverse67-wq/carryon-app/main/docs/img/en-wide-light.webp" width="760" alt="CarryOn window listing sessions as Waiting for you, Needs continuing and Running, with how full each context is" />
  </picture>
</a>

</div>

### What it does

- **One list of what needs you.** Sessions are grouped as *Waiting for you*, *Needs continuing* (context 60%+, orange from 85%) and *Running*. You get a notification when one is almost full.
- **Back up & compact in place.** CarryOn saves the session log first, then compacts it: Claude Code with its own `/compact`, Codex through its app server. Aside sessions continue in a fresh session.
- **Clean up idle sessions.** Close idle Claude Code sessions after you confirm (they stay resumable), and see which sessions read the most tokens in the last 24 hours.
- **To-dos that survive compaction.** Per-session to-dos carry over after a compact.
- **Local only.** The app itself makes no network requests. Compaction runs through your own `claude` / `codex` as usual. English, 한국어, 日本語, 简体中文.

<details>
<summary><b>한국어로 보기</b></summary>

<br />

**CarryOn — AI 코딩 세션이 멈추지 않게.**  
Claude Code·Codex·Aside 세션을 여러 개 동시에 돌리는 사람을 위한 무료 macOS 메뉴바 앱이에요. 세션마다 컨텍스트가 얼마나 찼는지 보여 주고, 무거운 세션은 백업한 뒤 그 자리에서 압축해 작업이 이어지게 해요.

- **나를 기다리는 것만 한 목록에:** '나를 기다림 / 이어 가야 함(컨텍스트 60% 이상, 85%부터 주황) / 실행 중'으로 나눠 보여 주고, 거의 찬 세션은 알림으로 알려요.
- **백업하고 그 자리에서 압축:** 세션 기록을 먼저 백업한 뒤 압축해요. Claude Code는 자체 `/compact`, Codex는 앱 서버로 해요. Aside 세션은 새 세션으로 이어 가요.
- **쉬는 세션 정리:** 확인을 받은 뒤 쉬고 있는 Claude Code 세션을 닫아요(나중에 다시 이어 갈 수 있음). 지난 24시간 동안 토큰을 가장 많이 읽은 세션도 보여 줘요.
- **압축해도 남는 할 일:** 세션별 할 일이 압축 뒤에도 그대로 남아요.
- **내 맥에서만:** 앱 자체는 네트워크 요청을 하지 않아요. 압축은 평소처럼 내 `claude`·`codex`로 돌아가요. 영어·한국어·일본어·중국어(간체).

[macOS용 받기](https://github.com/morningverse67-wq/carryon-app/releases/latest) · [웹사이트](https://carryon-app.pages.dev) · macOS 14 이상, Apple silicon·Intel, 무료

</details>

<br />

---

<sub>Made by morningverse. I also build and measure backend systems — [backend-lab](https://github.com/morningverse67-wq/backend-lab) · [backend-interview-lab](https://github.com/morningverse67-wq/backend-interview-lab) · [Velog](https://velog.io/@morningverse)</sub>
