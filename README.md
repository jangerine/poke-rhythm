# ⚡ 포케리듬 — 프세카풍 리듬게임

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WebAudio](https://img.shields.io/badge/Web_Audio-API-ffcb05?style=flat-square)
![No-Dependency](https://img.shields.io/badge/dependency-zero-4ade80?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

프로젝트 세카이(프세카) 스타일의 **4키/6키 낙하형 리듬게임**입니다.
적녹·금은 원곡 스트리밍 15곡 + 내 MP3 업로드 플레이 지원. 설치 없이 브라우저에서 바로 실행됩니다.

## ▶️ 바로 플레이

### 🎮 [https://jangerine.github.io/poke-rhythm/](https://jangerine.github.io/poke-rhythm/) ← 클릭하면 바로 게임 시작!

📂 레포: [https://github.com/jangerine/poke-rhythm](https://github.com/jangerine/poke-rhythm)

---

## ✨ 주요 기능

- **4키/6키 낙하형 라이브** (프세카식, 시작 화면에서 선택)
- **3종 노트(네모 막대)**: 🟦 탭 / 🟢 홀드 / 🟥 플릭 (쓸어올리기·끊어치기 필수, 누르기만으론 MISS)
- **5단계 난이도 + 프세카식 수치** (곡 BPM·보면 밀도로 곡마다 자동 산정):
  `수치 = 기본치(E2/N7/H12/EX17/MA22) + round((BPM-100)/7) + 밀도가중(E0/N1/H2/EX3/MA4)`

| 난이도 | 140BPM 예시 | 특징 |
|--------|-------------|------|
| EASY | 8 | 탭+홀드 중심, 가끔 플릭+동시치기 |
| NORMAL | 14 | 빠른 템포, 동시치기+연타 맛보기 |
| HARD | 20 | 고속 동시치기+연타+클라이막스 러시 |
| EXPERT | 26 | 극악 광속 16분 연타+더블 점프 |
| MASTER | 32 | 초극악 쉴 틈 없는 광속 러시+연타 |
- **정밀 판정**: PERFECT ±45ms / GREAT ±90ms / GOOD ±130ms
- **스코어 시스템**: 1,000,000점 만점, 콤보, MAX COMBO, 정확도, 랭크 SSS~F, FULL COMBO 뱃지
- **라이프 바**: MISS/GOOD 감소, PERFECT 회복
- **원곡 스트리밍 15곡**: archive.org URL에서 바로 재생 (음원 미포함, 인터넷 필요, 학교망은 VPN 필요할 수 있음)
- **유튜브 재생 1곡**: 차단망에서도 되는 iframe 방식 (판정 여유 적용, 시작 안 되면 탭 버튼)
- **커스텀 MP3 플레이**: 본인 소장 포켓몬 BGM 업로드 → BPM 기준 채보 자동 생성
- **클라이막스 연타**: HARD+ 후반부 16분음표 러시 (타타타타!)
- **모바일 대응**: 터치 + 플릭 스와이프, 반응형 캔버스
- **가로 모드**: 낮은 화면 대응 레이아웃(노트 크기 상한·판정선 조정) + 전체화면 시 가로 고정 시도
- **일시정지 메뉴**: 플레이 중 ⏸(또는 Esc) → 계속하기 / 🔁 다시하기 / 🏠 로비로
- **옵션**: 슬라이드 속도 2~10 (등속 스크롤, px/sec 고정), 볼륨, 오토플레이(감상모드), 일시정지
- **부드러운 슬라이드**: 고해상도(DPR) 렌더링, 노트 잔상 트레일, 상단 페이드인, 접근 링·리셉터 애니메이션
- **음악 싱크 채보**: 파형 분석으로 실제 박자·음높이·서스테인에 노트 배치 (실패 시 박자 그리드 폴백), 밀도는 그대로 빡세게
- **원근감 3D 레인**: 위로 좁아지며 모이는 사다리꼴 레인, 노트가 커지며 내려옴 (프세카 3D 라이브풍)

## 🎵 수록곡 (원곡 스트리밍)

| 자켓 | 곡명 | 원곡 | BPM |
|------|------|------|-----|
| 🎺 | 1번도로 (적·녹) [원곡] | Route 1 Original | 140* |
| 🎺 | 3번도로 (적·녹) [원곡] | Route 3 Original | 140* |
| 🎺 | 11번도로 (적·녹) [원곡] | Route 11 Original | 140* |
| 🎺 | 챔피언로드 (적·녹) [원곡] | Victory Road Original | 150* |
| 🎺 | 24번도로 (적·녹) [원곡] | Route 24 Original | 140* |
| 🎺 | 26번도로 (금·은) [원곡] | Route 26 Original | 140* |
| 🏥 | 포켓몬센터 (적·녹) [원곡] | Pokemon Center Original | 100* |
| 🕶 | 로켓단 아지트 (적·녹) [원곡] | Rocket Hideout Original | 130* |
| ⚔️ | VS 트레이너 (적·녹) [원곡] | Vs Trainer Original | 152* |
| 🔥 | VS 체육관 관장 (적·녹) [원곡] | Vs Gym Leader Original | 158* |
| 👻 | 라벤더타운 (적·녹) [원곡] | Lavender Town Original | 90* |
| 🚲 | 자전거 (적·녹) [원곡] | Cycling Original | 150* |
| 🌙 | 달맞이산 (적·녹) [원곡] | Mt Moon Original | 100* |
| ⚡ | VS 라이벌 결전 (적·녹) [원곡] | Final Battle Rival Original | 165* |
| 🎺 | 타이틀 화면 (적·녹) [원곡] | Title Screen Original | 110* |
| ⚡ | 피카츄알 | 로컬 mp3 (30초) | 140* |
| 🎤 | 한 남자 이야기 | 로컬 mp3 (79초) | 110* |

> 🎺 * 표시 BPM은 추정치 — 게임 내 ⚙ 버튼으로 곡별 조절 가능. 음원 파일은 archive.org URL에서 스트리밍되며 레포에 포함되지 않습니다.
> ⚡🎤 로컬 mp3 2곡은 `music/` 폴더 전용이며 `.gitignore`로 푸시에서 제외됩니다. GitHub Pages에서는 재생 안 되고, 로컬(크롬북)에서 `index.html`을 직접 열어 플레이하세요.

## 🎮 조작법

### 키보드 (시작 화면에서 4키/6키 선택)

| 4키 레인 | 1 | 2 | 3 | 4 |
|------|---|---|---|---|
| 키 | `D` | `F` / `Space` | `J` | `K` |

| 6키 레인 | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 키 | `S` | `D` | `F` / `Space` | `J` | `K` | `L` |

### 모바일
- 레인 터치 = 탭
- 위로 쓸어올리기 = 플릭 (스치듯 빠르게! 그냥 탭하면 MISS)

### 노트 종류
- 🟦 **탭**: 판정선에 닿을 때 누르기
- 🟢 **홀드**: 끝까지 꾹 누르고 있기 (일찍 떼면 MISS), 떼는 타이밍도 판정
- 🟥 **플릭**: 모바일은 위로 쓸어올리기, 키보드는 짧게 끊어치듯 눌렀다 떼기 (그냥 누르기만 하면 MISS)

## 🎯 판정 테스트 & 오프셋 세팅

- 곡 선택 화면 → **🎯 판정 테스트**: 메트로놈 8박에 맞춰 패드 두드리기 → 평균 어긋남(ms) 측정 → 적용하면 이후 모든 판정에 자동 보정 (브라우저에 저장됨)
- **±2 버튼**으로 직접 미세 조정 가능

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
- Web Audio API: 스트리밍 곡은 `<audio>` 재생 + `AudioContext` 시계 동기화, 판정 오프셋 보정
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
- `Pokémon`, 포켓몬 관련 명칭·이미지·음원은 Nintendo / Creatures Inc. / GAME FREAK inc.의 자산입니다. 본 프로젝트는 비공식 팬 메이드이며, 음원은 archive.org URL 스트리밍으로만 재생하고 레포에 포함하지 않습니다.
- 실제 포켓몬 음원은 권리자의 허락 없이 배포하지 마세요. 커스텀 MP3 기능은 개인 소장용으로만 사용하세요.

---

Made with 💛⚡ — FULL COMBO 도전!
