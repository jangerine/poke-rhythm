# ⚡ Pokémon Rhythm Stage! — 프세카풍 리듬게임

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WebAudio](https://img.shields.io/badge/Web_Audio-API-ffcb05?style=flat-square)
![No-Dependency](https://img.shields.io/badge/dependency-zero-4ade80?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

프로젝트 세카이(프세카) 스타일의 **5레인 낙하형 리듬게임**입니다.
실제 BGM 곡명 오마주 9곡 내장 + 내 MP3 업로드 플레이 지원. 설치 없이 브라우저에서 바로 실행됩니다.

## ▶️ 바로 플레이

### 🎮 [https://jangerine.github.io/pokemon-rhythm-stage/](https://jangerine.github.io/pokemon-rhythm-stage/) ← 클릭하면 바로 게임 시작!

📂 레포: [https://github.com/jangerine/pokemon-rhythm-stage](https://github.com/jangerine/pokemon-rhythm-stage)

---

## ✨ 주요 기능

- **5레인 낙하형 라이브** (프세카식)
- **3종 노트(네모 막대)**: 🟦 탭 / 🟢 홀드 / 🟥 플릭 (쓸어올리기·끊어치기 필수, 누르기만으론 MISS)
- **4단계 난이도** (레벨·밀도·기믹 차별화, 최소 노트 간격 보장):

| 난이도 | 레벨 | 특징 |
|--------|------|------|
| EASY | Lv.5 | 탭+홀드 중심, 가끔 플릭+동시치기 |
| NORMAL | Lv.8 | 빠른 템포, 동시치기+연타 맛보기 |
| HARD | Lv.11 | 고속 동시치기+연타+클라이막스 러시 |
| EXPERT | Lv.15 | 극악 광속 16분 연타+더블 점프 |
- **정밀 판정**: PERFECT ±45ms / GREAT ±90ms / GOOD ±130ms
- **스코어 시스템**: 1,000,000점 만점, 콤보, MAX COMBO, 정확도, 랭크 SSS~F, FULL COMBO 뱃지
- **라이프 바**: MISS/GOOD 감소, PERFECT 회복
- **WebAudio 실시간 합성 BGM**: 외부 음원 파일 없이 lead/bass/drum 합성
- **커스텀 MP3 플레이**: 본인 소장 포켓몬 BGM 업로드 → BPM 기준 채보 자동 생성
- **원곡 스트리밍**: 🎺 곡은 archive.org URL에서 바로 재생 (음원 미포함, 인터넷 필요)
- **클라이막스 연타**: HARD+ 후반부 16분음표 러시 (타타타타!)
- **모바일 대응**: 터치 + 플릭 스와이프, 반응형 캔버스
- **가로 모드**: 낮은 화면 대응 레이아웃(노트 크기 상한·판정선 조정) + 전체화면 시 가로 고정 시도
- **옵션**: 슬라이드 속도 2~10 (등속 스크롤, px/sec 고정), 볼륨, 오토플레이(감상모드), 일시정지
- **부드러운 슬라이드**: 고해상도(DPR) 렌더링, 노트 잔상 트레일, 상단 페이드인, 접근 링·리셉터 애니메이션

## 🎵 수록곡 (오리지널 칩튠)

| 자켓 | 곡명 | 분위기 | BPM |
|------|------|--------|-----|
| 🌿 | 1번도로 (적·녹) | Route 1 | 142 |
| 💤 | 포켓몬센터 (적·녹) | Heal | 112 |
| 🔥 | VS 체육관 관장 (적·녹) | Gym Leader | 176 |
| ⚡ | VS 라이벌 (적·녹) | Rival | 162 |
| 🌊 | 19번수로 파도타기 (적·녹) | Surf | 152 |
| 🌙 | 달맞이산 (적·녹) | Mt. Moon | 104 |
| 🏆 | VS 챔피언 (적·녹) | Champion | 186 |
| 🕶 | 로켓단 아지트 (적·녹) | Rocket Hideout | 166 |
| 🌆 | 금빛시티 (금·은) | Goldenrod | 156 |
| 🎺 | 1번도로 (적·녹) [원곡] | Route 1 Original (스트리밍) | 140* |
| 🎺 | 3번도로 (적·녹) [원곡] | Route 3 Original (스트리밍) | 140* |
| 🎺 | 11번도로 (적·녹) [원곡] | Route 11 Original (스트리밍) | 140* |

> ⚠️ 곡명은 나무위키 등에서 확인되는 실제 BGM을 오마주한 것으로, 멜로디는 저작권 회피를 위한 오리지널입니다(원곡 음원 아님).
> 🎺 원곡 스트리밍 곡(* BPM 140은 추정치, 게임 내 ⚙ 버튼으로 조절 가능)은 archive.org URL에서 바로 재생되며, 음원 파일은 레포에 포함되지 않습니다.

> ⚠️ 저작권 회피를 위해 내장곡은 포켓몬풍 오리지널 멜로디입니다.
> 실제 포켓몬 음원을 쓰고 싶으면 **커스텀 MP3 업로드 기능**을 사용하세요 (개인 소장용에 한함).

## 🎮 조작법

### 키보드 (5레인)

| 레인 | 1 | 2 | 3 | 4 | 5 |
|------|---|---|---|---|---|
| 키 | `S` | `D` | `F` / `Space` | `J` | `K` |

### 모바일
- 레인 터치 = 탭
- 위로 쓸어올리기 = 플릭 (스치듯 빠르게! 그냥 탭하면 MISS)

### 노트 종류
- 🟦 **탭**: 판정선에 닿을 때 누르기
- 🟢 **홀드**: 끝까지 꾹 누르고 있기 (일찍 떼면 MISS), 떼는 타이밍도 판정
- 🟥 **플릭**: 모바일은 위로 쓸어올리기, 키보드는 짧게 끊어치듯 눌렀다 떼기 (그냥 누르기만 하면 MISS)

## 🚀 실행 방법

### 1. 로컬 실행 (가장 빠름)
```bash
# 파일 더블클릭
open index.html
# 또는 로컬 서버 (권장)
cd pokemon-rhythm
python3 -m http.server 8000
# → http://localhost:8000 접속
```

### 2. GitHub Pages 배포
```bash
cd pokemon-rhythm
git init
git add index.html README.md
git commit -m "feat: pokemon rhythm stage v1.0"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```
이후 GitHub repo → **Settings → Pages → Deploy from branch → main / root** 선택하면 플레이 링크 생성.

## 📁 프로젝트 구조

```
pokemon-rhythm/
├── index.html   # 게임 전체 (HTML + CSS + JS 단일 파일, 의존성 0)
└── README.md    # 이 문서
```

단일 파일이라 포크·수정·배포가 쉽습니다.

## ⚙️ 커스텀 MP3로 플레이

1. 곡 선택 화면 → **📁 내 포켓몬 mp3로 플레이** 클릭
2. mp3 파일 선택 (브라우저 내에서만 처리, 업로드 안 됨)
3. **⚙ 커스텀 BPM** 버튼으로 BPM 입력 (모르면 120~150)
4. START → BPM 기준 채보 자동 생성 (EXPERT는 동시치기 포함)

## 🏆 스코어 / 랭크

- 만점 1,000,000점, 노트 수로 균등 배분
- PERFECT 100% / GREAT 70% / GOOD 30% / MISS 콤보 끊김
- 정확도 = (P + G×0.7 + Good×0.3) / 전체노트 × 100
- 랭크: SSS ≥98 / SS ≥95 / S ≥92 / A ≥85 / B ≥70 / C ≥50 / F 그 이하
- MISS·GOOD 0개면 FULL COMBO, GREAT까지 0개면 PERFECT FULL COMBO

## 🛠 기술 스택

- Vanilla HTML / CSS / JavaScript (CDN·빌드 없음)
- Canvas 렌더링 (`requestAnimationFrame`)
- Web Audio API: Oscillator + NoiseBuffer로 lead / bass / kick / snare / hat 합성, lookahead 스케줄링
- 판정은 `AudioContext.currentTime` 기준, 오디오-채보 동기화

## 🗺 로드맵

- [ ] 7레인 모드
- [ ] 슬라이드 노트
- [ ] 홀드 중간틱
- [ ] 키음 / 클랩 음 변경
- [ ] 로컬 하이스코어 저장 (localStorage)
- [ ] 채보 에디터

PR·이슈 환영합니다!

## 📄 라이선스 / 고지

- 이 프로젝트 코드는 **MIT License**로 자유롭게 사용·수정·배포할 수 있습니다.
- `Pokémon`, 포켓몬 관련 명칭·이미지는 Nintendo / Creatures Inc. / GAME FREAK inc.의 상표입니다. 본 프로젝트는 비공식 팬 메이드이며, 내장 BGM은 오리지널입니다.
- 실제 포켓몬 음원은 권리자의 허락 없이 배포하지 마세요. 커스텀 MP3 기능은 개인 소장용으로만 사용하세요.

---

Made with 💛⚡ — FULL COMBO 도전!
