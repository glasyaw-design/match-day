# FM 매치데이 저널

FM27(풋볼매니저 27) 세이브에 **이야기**를 덧씌우는 BepInEx 모드입니다. 경기마다 팬 반응, 감독 일기, 시즌 연대기, 회고록을 만들어 줍니다.

- 게임 파일과 세이브는 **읽기만** 합니다. 모든 기록은 내 PC에만 남습니다.
- Windows + Steam판 FM27, BepInEx 6 bleeding edge(Unity IL2CPP, win x64)가 필요합니다.

## 받기

👉 **[최신 버전 받기](../../releases/latest)** — `MatchdayJournal-v….zip`을 받으세요.

설치 방법은 zip 안의 `설치_가이드.md`에 그림 같은 폴더 구조와 함께 자세히 있습니다.

## 이 저장소의 파일

| 파일 | 용도 |
|---|---|
| `mj-update.json` | 최신 버전 번호. 모드가 게임을 켤 때 읽어 새 버전을 알려 줍니다. |
| `mj-builds.json`, `mj-builds.json.sig` | FM 빌드 정보(새 FM 버전에서 경기 함수를 찾는 데이터)와 제작자 서명. 서명이 맞을 때만 모드가 씁니다. |

## 문제 제보

`게임 폴더\BepInEx\LogOutput.log`와 화면 캡처를 [Issues](../../issues)에 올려 주세요. `config.json`(API 키가 들어 있을 수 있음)은 올리지 마세요.

---

메모리 해석 방식과 일부 코드는 [FMMatchLens](https://github.com/osnsyc/FMMatchLens)(osnsyc, MIT)를 고쳐 썼습니다. 이 모드는 Sports Interactive·SEGA와 관계없는 팬 제작물입니다.
