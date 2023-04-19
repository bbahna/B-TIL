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

<img src="https://user-images.githubusercontent.com/69684005/232306403-00f30685-5624-426a-a12d-607607b8830c.png" />

<br>

## ✍🏻 TIL 작성 및 반영 방법

### 1. 개인 브랜치를 생성해주세요.
- `main` 하위 브랜치 생성
- 브랜치 명칭 규칙 : `프로그램영문명/기수th/이름영문명`
  - 예) `bside/15th/parkseojoon`

### 2. 주차 별 폴더에 TIL 내용을 아래 형식에 맞춰 작성해주세요.
- MD파일의 형식으로 작성
- 파일명 규칙 : 이름_작성일자(YYMMDD).md
- 내용 : 자유롭게 작성 (기본 작성 템플릿 제공)<br>
  [👉 TIL 작성 템플릿 보기](./til-template.md)

<img src="https://user-images.githubusercontent.com/69684005/232313011-1cb58534-83a8-4246-a9fd-0519eb863334.png" width="700"/>


### 3. 작성한 TIL을 개인 브랜치에 commit 해주세요. <br>
> ✅ 커밋 전, 개인 브랜치를 main 브랜치의 최신 상태로 맞춘 후 커밋 해주세요.
- commit 메세지 규칙 : 프로그램명 n주차 이름<br>
  - 예) 비사이드 1주차 박서준

<img src="https://user-images.githubusercontent.com/69684005/232313184-286b9b63-d44e-4873-acef-541c45e5a05b.png" />

### 4. 매 주, 작성한 커밋을 모아서 PR(Pull Request) 해주세요.
> **📆 TIL 작성 & 반영 주기**<br>
> 월~일 : TIL을 작성 해주시고 일요일까지 PR을 생성 해주세요. (오후 6시 까지)<br>
> 일 : 운영자가 PR 을 확인하고 Merge 해요. (오후 6시 이후)

- B-TIL Github 페이지에서 개인 브랜치를 main 브랜치로 PR 요청
- 라벨 설정 : `프로그램명-기수`
  - ex) `bside-15`
- PR 제목 규칙 : 프로그램명 TIL n주차 이름
  - commit 메시지와 동일

<img src="https://user-images.githubusercontent.com/69684005/232313265-0ef0c70a-002c-4ff8-bcb0-c2f12c131931.png" width="700"/> <br>
<img src="https://user-images.githubusercontent.com/69684005/232313465-2db71465-1961-48c6-9f7d-9865d9c5ef28.png" />

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

궁금하신 점은 비사이드 슬랙 채널 `B-TIL` 에 남겨 주세요. 🙌🏻

<br>