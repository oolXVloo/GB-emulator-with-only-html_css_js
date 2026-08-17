
# <Game Boy Emulator>

🇰🇷 [한국어](#한국어) | 🇺🇸 [English](#english)

---

## 한국어

브라우저에서 실행할 수 있는 간단한 Game Boy 에뮬레이터입니다.

별도의 설치 없이 HTML 파일을 브라우저에서 실행하여 Game Boy ROM을 불러올 수 있습니다.

### 주요 기능

- `.gb`, `.gbc` ROM 파일 불러오기
- 브라우저에서 직접 실행
- Game Boy 화면 출력
- D-Pad 방향키
- A / B 버튼
- START / SELECT 버튼
- 키보드 입력 지원
- 상태 정보 표시
- 디버그 로그 표시
- MBC 기반 ROM 뱅킹 지원
- 타이머 및 PPU 처리
- Game Boy CPU 명령어 처리

### 조작법

| Game Boy | 키보드 |
|---|---|
| ↑ | `ArrowUp` |
| ↓ | `ArrowDown` |
| ← | `ArrowLeft` |
| → | `ArrowRight` |
| A | `A` |
| B | `B` |
| SELECT | `Shift` |
| START | `Enter` |

모바일에서는 화면에 표시되는 버튼을 직접 터치할 수 있습니다.

### 실행 방법

1. 저장소를 다운로드하거나 Clone합니다.
2. HTML 파일을 브라우저로 엽니다.
3. `ROM 선택` 버튼을 누릅니다.
4. Game Boy ROM 파일을 선택합니다.
5. 게임을 실행합니다.

기본 ROM 경로를 사용하는 경우 `./gbemul/mario.gb`에 ROM을 배치할 수도 있습니다.

### 기술

이 프로젝트는 외부 에뮬레이터 라이브러리를 사용하지 않고 JavaScript로 Game Boy의 주요 구성 요소를 구현합니다.

- HTML
- CSS
- JavaScript
- Canvas API

### 주의사항

이 프로젝트는 학습 및 실험 목적으로 제작된 에뮬레이터입니다.

ROM 파일은 직접 준비해야 하며, 저작권이 있는 ROM을 배포하거나 공유하지 마세요.

---

## English

A simple Game Boy emulator that runs directly in a web browser.

You can open the HTML file in a browser and load a Game Boy ROM without installing a separate application.

### Features

- Load `.gb` and `.gbc` ROM files
- Run directly in the browser
- Game Boy screen rendering
- D-Pad controls
- A / B buttons
- START / SELECT buttons
- Keyboard input
- CPU status display
- Debug log
- MBC-based ROM banking
- Timer emulation
- PPU emulation
- Game Boy CPU instruction handling

### Controls

| Game Boy | Keyboard |
|---|---|
| ↑ | `ArrowUp` |
| ↓ | `ArrowDown` |
| ← | `ArrowLeft` |
| → | `ArrowRight` |
| A | `A` |
| B | `B` |
| SELECT | `Shift` |
| START | `Enter` |

On mobile devices, you can use the on-screen buttons.

### How to Run

1. Download or clone this repository.
2. Open the HTML file in a web browser.
3. Click the `ROM 선택` / ROM selection button.
4. Select a Game Boy ROM.
5. Start playing.

You can also place a ROM at `./gbemul/mario.gb` if you want to use the built-in ROM loading button.

### Technology

This project implements major parts of a Game Boy emulator using JavaScript without relying on an external emulator library.

- HTML
- CSS
- JavaScript
- Canvas API

### Disclaimer

This project is intended for learning and experimentation.

You must provide your own ROM files. Do not distribute or share copyrighted ROMs.

---

## License

Add your preferred license here.

For example:

`MIT License`
