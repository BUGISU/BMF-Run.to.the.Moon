# 프로젝트 기술 설계서: Run to the Moon

## 📘 보자마자 피트니스 - 런 투 더 문(Run to the Moon)

![대표 이미지](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/77faf970-175c-4c4d-baed-6058399383a8)

달을 향해 날아가던 중 사고로 인해 소행성에 불시착하게 된 우주 소년 '미로'.
광활하고 몽환적인 우주의 길을 걸으며 달을 향해 걸어가는 '미로'의 스페이스 로드 무비.

**스토리 기반 플레이**, **다양한 맵 디자인**, **돌발 미션**, **산소 시스템**,
**운동량 조절 아이템**, **운동 데이터 확인**, **의문의 조각함**,
**달 도달 성취감**을 제공하는 **홈 피트니스 게임**.

> 앱과 센서를 블루투스로 연결해 달까지 걸어가는 컨셉.

![콘텐츠 이미지](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/e41e4c4e-2248-44ea-a75a-0aa90d4f3e28)

<details>
<summary>📂 브로슈어 보기</summary>

![브로슈어1](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/eed90aa4-c8c2-43fd-a453-1374a6638bfe)
![브로슈어2](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/5f26b618-d591-4aa7-b94c-ed3af235ebd2)
![브로슈어3](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/2b9c0d36-9c3c-47c1-a0dc-e52146acf74c)
![브로슈어4](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/fcb31e89-8098-48a8-ba50-e9e1468315c9)

</details>

🔗 [공식 사이트 바로가기](https://bojamajafitness.com/article/%EB%B3%B4%EC%9E%90%EB%A7%88%EC%9E%90-%ED%94%BC%ED%8A%B8%EB%8B%88%EC%8A%A4-%EC%BD%98%ED%85%90%EC%B8%A0/8/13/)

---

## 📅 개발 기간

* **2021년 8월 \~ 2022년 12월** (1년 5개월)

## 🛠️ 기술 스택

* **엔진**: Unity3D (C#)
* **비주얼 연출**: Cinemachine, LineRenderer, Skybox 회전, TunnelEffect
* **데이터 관리**: PlayerPrefs, BLE 센서 연동 (ESP32 기반), Addressables
* **UI/UX**: Unity UI, Coroutine 기반 내러티브 및 튜토리얼 시스템

---

## 💼 기여도

### 🎨 콘텐츠 UI 디자인 적용 (2021.08\~)

| UI 화면 1                                                                                           | UI 화면 2                                                                                           | UI 화면 3                                                                                           |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| ![UI1](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/d7f8e7f3-cd81-42b7-b0bb-fbabfb022a69) | ![UI2](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/47903257-17ed-483c-bb57-fb0a336fc1df) | ![UI3](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/a7c3fec3-7cba-41ca-b018-4f49f8bf18f0) |

### 🗺️ 게임 콘텐츠 맵 20종 구현

![맵 전체](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/a2246b56-129b-4de2-9850-9ece14b8bf6c)

**구간별 거리**

```
1. 여정의 시작 (0~50km)
2. 목적없는 발걸음 (50~100km)
3. 달의 비밀 (100~150km)
4. 희망의 끈 (150~200km)
5. 수상한 빛 (200~250km)
6. 빛의 무리 (250~300km)
7. 맴도는 공허함 (300~350km)
8. 길을 잃은 아기별 (350~400km)
9. 나를 도와줘 (400~450km)
10. 불꽃놀이 (450~500km)
11. 소원석 (500~550km)
12. 발버둥 치는 마음 (550~600km)
13. 우주를 떠도는 영혼 (600~650km)
14. 함께 하는 여정 (650~700km)
15. 목걸이의 주인 (700~750km)
16. 안녕, 별자리 (750~800km)
17. 몽환의 세계 (800~850km)
18. 점점 더 가까이 (850~900km)
19. 색을 잃은 빛 (900~950km)
20. 달의 신전 (950~1000km)
21. 명예의 전당
```

### 🧩 맵 내 이벤트 시스템 구현

![이벤트](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/676159b2-bb26-44a1-89cc-da419694538b)

* 재미 요소 획득 시 이벤트 발생
* 튜토리얼은 1회만 제공되도록 설정
* 아이템은 우주정거장에서만 구매 가능
* 맵별 다양한 미션/스토리 연출 구성

### 🗣️ 스토리 나레이션 구현

![내러티브](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/443e51a8-af31-4205-ac7f-4871f87d525d)

* 각 맵마다 메인 내러티브 자동 출력
* 랜덤 등장 대사 시스템 구현

### 🌐 런 투 더 문 영문 버전 제작 (2022.05\~)

![영문](https://github.com/JISUSAMA/JISUSAMA/assets/38304918/cf6cbda5-a957-4c16-82e9-b84bd3683310)

🔗 [영문 버전 Google Play Store](https://play.google.com/store/apps/details?id=com.gateways.runtothemoon_en)

---

## 📺 유튜브 홍보 영상

[![Run to the moon 공식 홍보 영상](http://img.youtube.com/vi/6nW58Vrx-vE/0.jpg)](https://www.youtube.com/watch?v=6nW58Vrx-vE)

---

## 🧱 시스템 구조 및 핵심 스크립트 설명

### 1. 데이터 관리

* `Game_DataManager`: 거리, 칼로리, 시간, 걸음 수 등의 운동 데이터를 저장 및 서버 전송 처리
* `O2Timer`: 산소 시스템 구현 (기본 40분 기준, 아이템으로 보충 가능), 특정 구간에서 산소 소비 가속
* `PlayerAniCheckCtrl`: 발소리 효과 및 걸음 수 실시간 계산

### 2. 씬 로딩 및 UI

* `Loading_SceneManager`: Addressables 기반의 씬 로딩 처리 및 진행도 연출
* `Lobby_UIManager`: 메인 로비에서 유저 정보 및 조각함 UI 제어
* `Lobby_DataManager`: 닉네임 필터링, 접속일 관리, 튜토리얼 상태 관리

### 3. 튜토리얼 및 내러티브

* `Game_HelpManager`: 최초 10단계 튜토리얼 팝업 처리 및 일시정지 연출
* `Game_TypeWriterEffect`: 타자기 스타일의 내러티브 출력. 특정 아이템 또는 맵 구간 도달 시 텍스트 출력 제어

### 4. 게임 내 맵 및 이벤트

* `CameraViewPort`: Player 위치에 따라 Cinemachine Virtual Camera 우선순위 변경 (좌우 시점 전환)
* `AroundActiveObject`: 특정 구역 진입 시 오브젝트 자동 활성화
* `SpawnBoundingBox`: BoxCollider 내부에 Addressables 객체를 랜덤 위치에 스폰
* `ItemDescriptionManager`: 아이템 설명 팝업 표시, 시간 제한 후 자동 종료 처리

### 5. 센서 연동 및 이벤트

* `Game_SenesorEvent`: BLE 센서 연동 시작 트리거 (ESP32 BLE)
* `App_Manager`: 라운드 시작/종료 시 UI, 데이터, 애니메이션 동기화

### 6. 시각 효과 및 연출

* `RotateSkyBox`: Skybox 회전 효과 (우주 느낌 강조)
* `Rotation`: 객체에 흔들림/회전 애니메이션 추가
* `TunnelController`: TunnelEffect 시각 효과 적용 (특정 스테이지 전용)

### 7. 명예의 전당 시스템 (Hall of Fame)

* `HallofFame_UIManager`: 도달 기록 저장, 순위 리스트 생성, 페이지 전환, Bloom 연출 처리
* `HallofFame_RankDataManager`: 각 판넬의 랭킹 정보를 설정하고 Text UI에 적용
* `HallofFame_PlayerCtrl`: 플레이어 도착 연출 및 Victory 애니메이션, 대화 출력

### 8. 어드레서블 및 다운로드 시스템

* `AddressablesManager`: Addressables 기반의 씬 로딩과 다운로드 진행률 계산. 씬 인스턴스 관리 포함
* `DownloadProgress`: 외부에서 다운로드 진행률 값을 받아 UI에 반영
* `SetupBundle`: Addressables 라벨 기반으로 번들 다운로드. 완료 시 UI 갱신 및 처리

### 9. 유저 설정 및 초기 구성

* `Setup_Manager`: 사용자 정보, 알림, 센서 연결, 계정 관련 초기 설정 전반 제어
* `CameraResolution`: 화면 비율에 따라 LetterBox 형태로 카메라 뷰 조정

### 10. 사운드 및 미디어 재생

* `SoundManager`: BGM/SFX 통합 제어. AudioMixer로 볼륨 조절 및 페이드 처리
* `SoundFunction`: 버튼 클릭, 아이템 획득, 미션, 라디오 등 상황별 효과음 처리용 래퍼 함수
* `SoundMaixer`: 슬라이더를 통한 실시간 볼륨 조절 UI와 AudioMixer 연동
* `VideoHandler`: VideoPlayer와 RawImage를 활용한 영상 출력 처리

### 11. 시각 효과 및 파티클

* `BlurControl`: 블러 머티리얼 효과를 동적으로 조정
* `DepthTexture`: 카메라 DepthTextureMode 설정을 통해 후처리 쉐이더 사용 가능 상태로 설정
* `BlinkAnim`: UI 요소에 반복 깜빡임 효과를 부여
* `GainValueAnim`: 점수 상승 시 텍스트 상승 및 알파 페이드 아웃 애니메이션
* `DestroyParticle`: 자동 파괴되는 파티클 처리
* `Particle_Spwan`: 화면 상 입력 위치에 따라 파티클 생성 (마우스/터치 대응)

### 12. 물리 기반 연출 및 오브젝트 이동

* `RandomMoveDirection`: Rigidbody에 force를 부여하여 무작위 이동. 향후 방향 랜덤화 가능
* `EstimatedVelocity`: 오브젝트 위치/회전 변화량을 기반으로 속도 추정 (디버깅용)
* `GoalGateEvnet`: 특정 게이트 도달 시 SpaceStation 오브젝트 활성화 처리
* `PiceEvnet`: 조각 아이템 드롭 시 다양한 파티클 연출 동시 발생

---

## 🧩 게임 진행 구조

```
▶ 로비 진입 (Lobby)
   └ 튜토리얼 여부 체크 → 씬 로딩
       └ 거리 기반 씬 선택 (Game 1~20, HallofFame)
           └ 센서 연동 → 게임 진행
               ├ 거리/시간/걸음수 누적 기록
               ├ 특정 지점: 내러티브 출력 및 아이템 설명
               └ 산소 소모 → 보충 아이템 사용 가능
▶ 달 도착 시 명예의 전당 등록 및 랭킹 출력
```

---

## 🔖 기타 구현 요소

* 타이핑 내러티브와 라디오 멘트 출력 시스템 (랜덤 등장)
* 달 조각, 산소통, 간식 등 다양한 아이템 획득 연출
* 우주 공간과 분위기에 어울리는 시각 연출 및 사운드 동기화
* 명예의 전당은 최대 100인까지 기록, 개인 랭킹 강조 처리

---

## ✅ 정리

Run to the Moon은 운동 데이터를 게임화하여 몰입감 있게 소화할 수 있는 홈 피트니스 콘텐츠입니다. 스토리 중심의 구간 진행, 센서 연동, 다양한 시각적 요소, 유저 맞춤 랭킹 시스템을 통해 운동 지속성과 몰입을 함께 유도합니다.
