# 三國志 II 웹 플레이어

KOEI 삼국지 II (1989) DOS 버전을 브라우저에서 플레이할 수 있는 웹 에뮬레이터입니다.  
[js-dos](https://js-dos.com/) (DOSBox WebAssembly) 기반으로 동작합니다.

---

## 🚀 GitHub Pages 배포 방법

### 1단계 — 게임 파일 업로드

아래 파일들을 저장소 **루트(/)** 에 모두 올려주세요.

```
sam2/
├── index.html        ← 이미 있음
├── dosbox.conf       ← 이미 있음
├── README.md         ← 이미 있음
├── RTK2.COM
├── MAIN.EXE
├── OPEN.EXE
├── END.EXE
├── SOUND.EXE
├── FMDRV.COM
├── GRPDATA.DAT
├── HEXDATA.DAT
├── KAODATA.DAT
├── SCENARIO.DAT
├── PACKDATA.DAT
├── OPMSG.DAT
├── TAIKI.DAT
├── MONTAGE.DAT
├── OPENING.DAT
├── ENDING.DAT
├── RTK2MAIN.16P
└── KOEI.BAT
```

> GitHub 저장소 페이지에서 **Add file → Upload files** 로 드래그앤드롭 하면 됩니다.

---

### 2단계 — GitHub Pages 활성화

1. 저장소 상단 **Settings** 탭 클릭
2. 왼쪽 메뉴에서 **Pages** 클릭
3. **Source** → `Deploy from a branch` 선택
4. **Branch** → `main` / `/ (root)` 선택 후 **Save**
5. 1~2분 후 `https://bin780823-prog.github.io/sam2/` 에서 플레이 가능

---

## 🎮 조작법

| 키 | 기능 |
|---|---|
| 방향키 | 커서 이동 |
| Enter | 선택/확인 |
| ESC | 취소/뒤로 |
| Space | 다음 |
| F5 | 저장 |
| F7 | 불러오기 |

---

## ⚙️ 기술 스택

- [js-dos 7.x](https://github.com/caiiiycuk/js-dos) — DOSBox WebAssembly 포트
- GitHub Pages — 정적 호스팅

---

## ⚠️ 저작권 안내

삼국지 II는 KOEI Co., Ltd.의 저작물입니다.  
이 저장소는 개인 소장 복사본의 개인 이용 목적으로만 사용하시기 바랍니다.
