# 저항 컬러 코드 · Resistor color codes

[한국어](#한국어) · [English](#english)

파일 · File: [`register color study.html`](register%20color%20study.html)

## 한국어

저항 색띠를 읽고 값을 고르는 연습 페이지입니다. 참고표와 4지선다 100문제가 한 파일에 들어 있고, 서버나 빌드 없이 브라우저에서 바로 열 수 있습니다.

### 언어

한국어, English, 中文, 日本語. 오른쪽 위의 언어 메뉴에서 바꿉니다. 문제를 풀던 중에도 문항과 표가 그 언어로 바뀌고, 점수는 유지됩니다.

글꼴은 언어마다 따로 불러옵니다. 한글은 Noto Sans KR, 일본어는 Noto Sans JP, 중국어는 Noto Sans SC, 영어는 Noto Sans입니다. 글꼴을 받지 못하면 각 언어의 시스템 글꼴로 표시됩니다.

### 기능

- 색, 수치, 승수, 정밀도, 온도계수를 한 표로 봅니다. 표는 접을 수 있고, 좁은 화면에서는 표 안에서 가로로 스크롤합니다.
- 100문제를 풀고, 고르면 바로 맞았는지 표시됩니다.
- 점수, 정답률, 남은 문제, 진행 위치를 보여 줍니다.
- **새 문제**는 문항과 보기를 다시 뽑습니다. **다시 풀기**는 같은 문제를 처음 문항부터 다시 풉니다.
- 라이트와 다크를 바꿀 수 있습니다. 처음에는 시스템 설정을 따릅니다.

언어와 화면 모드만 이 브라우저에 저장됩니다. 점수는 새로고침하면 초기화됩니다.

### 사용 방법

1. `register color study.html`을 브라우저에서 엽니다.
2. 문제를 풀고, 필요할 때 색 코드 표를 펼칩니다.
3. 화면이 넓으면 문제가 왼쪽, 표가 오른쪽에 있습니다. 좁으면 문제 아래에 표가 붙습니다.

### 문제 구성

한 세트는 100문제이며, 만든 뒤 순서를 섞습니다.

| 유형 | 문항 수 | 묻는 내용 |
| --- | ---: | --- |
| 숫자 | 25 | 색띠 하나의 수치 (0–9) |
| 승수 | 25 | 색띠의 승수 (×0.01–×1G) |
| 정밀도 | 20 | 4색띠의 정밀도 |
| 온도계수 | 15 | 6색띠 마지막 띠의 온도계수 (ppm/K) |
| 색 조합 | 15 | 4색띠를 왼쪽부터 숫자, 숫자, 승수, 정밀도로 읽기 |

### 띠를 읽는 순서

- **4색띠.** 숫자, 숫자, 승수, 정밀도.
- **5색띠.** 숫자 세 개, 승수, 정밀도. 표 아래 설명에만 있습니다.
- **6색띠.** 5색띠에 온도계수가 더해집니다.

### 수록된 색

| 색 | 수치 | 승수 | 정밀도 | 온도계수 |
| --- | --- | --- | --- | --- |
| 검정 | 0 | ×1 | — | 250 ppm/K |
| 갈색 | 1 | ×10 | ±1% | 100 ppm/K |
| 빨강 | 2 | ×100 | ±2% | 50 ppm/K |
| 주황 | 3 | ×1k | — | 15 ppm/K |
| 노랑 | 4 | ×10k | — | 25 ppm/K |
| 초록 | 5 | ×100k | ±0.5% | 20 ppm/K |
| 파랑 | 6 | ×1M | ±0.25% | 10 ppm/K |
| 보라 | 7 | ×10M | ±0.1% | 5 ppm/K |
| 회색 | 8 | ×100M | ±0.05% | 1 ppm/K |
| 흰색 | 9 | ×1G | — | — |
| 금색 | — | ×0.1 | ±5% | — |
| 은색 | — | ×0.01 | ±10% | — |

### 올리기

설치와 빌드가 없습니다. HTML 파일과 이 README를 저장소에 두면 됩니다. 네트워크가 있으면 글꼴만 Google Fonts에서 받습니다. 문제와 점수는 서버로 보내지 않습니다.

GitHub Pages를 쓰면 위 HTML을 사이트의 엔트리로 지정합니다. 파일 이름에 공백이 있으므로 주소는 `register%20color%20study.html`입니다.

## English

A practice page for reading resistor color bands and choosing the value. One file holds a reference chart and 100 multiple-choice questions. Open it in a browser. There is no server and no build step.

### Languages

Korean, English, Chinese, and Japanese. Switch from the menu at the top right. The question and the chart change immediately, and the score stays.

Each language loads its own font: Noto Sans KR, Noto Sans JP, Noto Sans SC, or Noto Sans. If the font cannot be loaded, the page uses that language’s system font.

### Features

- One chart for color, digit, multiplier, tolerance, and temperature coefficient. It can be collapsed. On a narrow screen, scroll sideways inside the chart.
- One hundred questions. The result shows as soon as you choose an answer.
- Score, accuracy, questions left, and position in the set.
- **New set** draws new questions and choices. **Try again** keeps the same questions and starts from the first one.
- Light and dark themes. The first visit follows the system setting.

This browser saves only the language and the theme. Refreshing resets the score.

### How to use

1. Open `register color study.html` in a browser.
2. Answer the questions, and open the color chart when you need it.
3. On a wide screen the questions are on the left and the chart is on the right. On a narrow screen the chart follows the questions.

### Question set

Each set has 100 questions. The order is shuffled after the set is built.

| Type | Count | What it asks |
| --- | ---: | --- |
| Digit | 25 | The digit for one band (0–9) |
| Multiplier | 25 | The multiplier for one band (×0.01–×1G) |
| Tolerance | 20 | The tolerance band on a 4-band resistor |
| Temperature coefficient | 15 | The last band on a 6-band resistor, in ppm/K |
| Band order | 15 | Read a 4-band resistor from the left: digit, digit, multiplier, tolerance |

### How to read the bands

- **4-band.** Digit, digit, multiplier, tolerance.
- **5-band.** Three digits, multiplier, tolerance. This is explained under the chart only.
- **6-band.** A 5-band code plus a temperature coefficient.

### Colors in the chart

| Color | Digit | Multiplier | Tolerance | Temp. coefficient |
| --- | --- | --- | --- | --- |
| Black | 0 | ×1 | — | 250 ppm/K |
| Brown | 1 | ×10 | ±1% | 100 ppm/K |
| Red | 2 | ×100 | ±2% | 50 ppm/K |
| Orange | 3 | ×1k | — | 15 ppm/K |
| Yellow | 4 | ×10k | — | 25 ppm/K |
| Green | 5 | ×100k | ±0.5% | 20 ppm/K |
| Blue | 6 | ×1M | ±0.25% | 10 ppm/K |
| Violet | 7 | ×10M | ±0.1% | 5 ppm/K |
| Gray | 8 | ×100M | ±0.05% | 1 ppm/K |
| White | 9 | ×1G | — | — |
| Gold | — | ×0.1 | ±5% | — |
| Silver | — | ×0.01 | ±10% | — |

### Publishing

Nothing to install or build. Put the HTML file and this README in the repository. When the browser is online, it loads the fonts from Google Fonts. Questions and scores are not sent to a server.

On GitHub Pages, use the HTML file above as the site entry. The file name contains a space, so the address is `register%20color%20study.html`.
