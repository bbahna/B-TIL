# B-TIL 활동 가이드

> 💡 B-TIL 참가신청 후 Github 멤버 초대가 되면 승인 후 이용 해주세요.

<br>

## ⚙️ B-TIL 프로젝트 로컬 환경 구성

> 👉🏻 아래의 가이드는 원 저장소를 Clone 하여 작업 하는 방식입니다. 선호 방식에 따라 **원 저장소 Fork 후 작업 및 PR 요청 하는 방식**도 가능합니다.

<br>

### 1. B-TIL 저장소 프로젝트를 로컬 환경에 복제 해주세요.
<img src="https://user-images.githubusercontent.com/69684005/232305837-cd3ae01d-3e86-4b6a-b137-c1f6b4c99507.png" width="700"/>


### 2. Github clone 명령어 혹은 에디터 환경에 따라 로컬 환경에 프로젝트를 구성해주세요.

```
// mac 환경 명령어 예시

// 1. 프로젝트 복제할 위치로 이동
$ cd /My/dev/projects

// 2. git clone 명령어 통해 B-TIL 프로젝트 복제
$ git clone https://github.com/bside-dev-club/B-TIL.git
```

### 3. 프로젝트 셋팅 완료

<img width="282" alt="image" src="https://user-images.githubusercontent.com/26621325/235136058-8ada7d60-0c32-4f86-8a6e-b8c3b348f504.png">

<br>

## ✍🏻 TIL 작성 및 반영 방법

### 1. 개인 브랜치를 생성해주세요.
- `main` 하위 브랜치 생성
- 브랜치 명칭 규칙 : `비틸기수th/이름영문명`
  - 예) `1th/parkseojoon`

### 2. 주차 별 폴더에 TIL 내용을 아래 형식에 맞춰 작성해주세요.
- MD파일의 형식으로 작성
- 파일명 규칙 : 이름_작성일자(YYMMDD).md
- 내용 : 자유롭게 작성 (기본 작성 템플릿 제공)<br>
  [👉 TIL 작성 템플릿 보기](./til-template.md)

<img width="700" alt="image" src="https://user-images.githubusercontent.com/26621325/235136840-0fb7287f-0912-4a96-bc06-43324d8ec1b4.png">


### 3. 작성한 TIL을 개인 브랜치에 commit 해주세요. <br>
> ✅ 커밋 전, 개인 브랜치를 main 브랜치의 최신 상태로 맞춘 후 커밋 해주세요.
- commit 메세지 규칙 : [비틸 기수] n주차 이름 - 넘버<br>
  - 예)
  - [1기] 1주차 박서준 - 1,
  - [1기] 1주차 박서준 - 2,
  - [1기] 2주차 박서준 - 1, ..

<img width="252" alt="image" src="https://user-images.githubusercontent.com/26621325/235139394-4b20502b-3d05-4c16-a2da-bb1ec233881c.png">


### 4. 매 주, 작성한 커밋을 모아서 PR(Pull Request) 해주세요.
> **📆 TIL 작성 & 반영 주기**<br>
> 월~일 : TIL을 작성 해주시고 일요일까지 PR을 생성 해주세요. (오후 6시 까지)<br>
> 일 : 운영자가 PR 을 확인하고 Merge 해요. (오후 6시 이후)

- B-TIL Github 페이지에서 개인 브랜치를 main 브랜치로 PR 요청
- 라벨 설정(총 2개) : `비틸-기수`, `참가중인프로그램명-기수`
  - ex) `btil-1`, `bside-15`
- PR 제목 규칙 : [비틸기수] n주차 이름

<img width="1355" alt="image" src="https://user-images.githubusercontent.com/26621325/235141385-58949a13-cf7e-4ecd-9822-d9103486b5d4.png">
<img width="401" alt="image" src="https://user-images.githubusercontent.com/26621325/235141433-a8116563-6c6b-4cfc-8f24-98741c45ae5e.png">

<br>

## 👀 다른 TIL 구경하고 반응하기

### 다른 비사이더의 TIL을 구경하고 코멘트로 반응해주세요.
- 응원의 한마디도 good !
- 작업에 참고할만한 내용을 공유해주어도 좋아요~

<img src="https://user-images.githubusercontent.com/69684005/232313446-ea5dc78f-dbc4-4e30-ae1a-69fbe63ae3f5.png" width="700"/>

<br>

## 💪🏻 개발 미션 시도하기

매 주, 프로젝트 진행에 도움이 될 수 있는 미션을 제공해드려요. (슬랙으로 안내)<br>
미션을 시도하며 프로젝트를 개발하고 TIL도 작성하여 작업 내용을 기록 해보세요.

<br>

***

<br>

궁금하신 점은 비사이드 슬랙 채널 `4_스터디_비틸` 에 남겨 주세요. 🙌🏻

<br>