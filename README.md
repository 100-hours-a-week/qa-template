# QA 템플릿 및 프로세스

## QA하는 방법

1. **오가니제이션 초대 및 팀 포함**
   - 나의 계정이 오가니제이션에 초대되어 [100-hours-a-week 팀](https://github.com/organizations/kakao-cloud-edu-5)에 포함된다.

## 이슈 템플릿 세팅

1. **레포지토리 생성**
   - 나의 이름으로 레포지토리를 생성한다.
2. **레포지토리로 이동**
   - 생성한 레포지토리로 이동하여 이슈 템플릿을 적용한다.

<details>
  <summary>이슈 템플릿 적용하는 방법</summary>

  ### 이미지를 따라 선택해주세요.

  #### 내 레포지토리에 가서 세팅으로 이동합니다.
  ![설정화면](https://github.com/kakao-cloud-edu-5/qa-template/assets/98660440/6d2ff739-b19c-45fe-afc1-d4171ed39939)
  1. Setting 클릭
  2. General 클릭
  3. Issues 체크
  4. Set up templates

  #### 커스텀 템플릿을 선택합니다.
  ![템플릿 선택](https://github.com/kakao-cloud-edu-5/qa-template/assets/98660440/41b70eab-e06b-4d44-872f-e0fb5eec28ab)
  1. Add template 버튼 클릭
  2. Custom template 선택

  #### 프리뷰를 수정합니다.
  ![프리뷰 수정](https://github.com/kakao-cloud-edu-5/qa-template/assets/98660440/a7f715f6-155b-472e-9cf1-a8ee58c72d78)
  1. Preview and edit 선택

  #### 템플릿을 수정합니다.
  ![템플릿 수정](https://github.com/kakao-cloud-edu-5/qa-template/assets/98660440/191f8ec6-fe62-405d-8712-7b4ae074c294)
  1. 템플릿 수정 버튼 클릭

  #### 템플릿을 생성합니다.
  ![템플릿 생성](https://github.com/kakao-cloud-edu-5/qa-template/assets/98660440/e4f7e4a8-4be6-4f06-84d6-bc98acf81b0f)
  1. 내용을 작성합니다.

  #### 저장합니다.
  ![저장](https://github.com/kakao-cloud-edu-5/qa-template/assets/98660440/35b717fe-5dd6-4551-925e-5523f5b2c274)
  1. Purpose changes 버튼 클릭
</details>

## 이슈 업로드

### 이슈 게시 방법

1. **새 이슈 작성**
   - Issues 탭에서 New Issue를 누른다.
   ![이슈 생성](https://user-images.githubusercontent.com/17779284/197138458-ba9c796d-2b3d-4d81-b047-a6372f636d30.png)
2. **템플릿 선택**
   - 해당하는 템플릿을 선택한다.
   ![템플릿 선택](https://user-images.githubusercontent.com/17779284/197138623-8560c63f-ad4a-473c-8d4e-bb233af8926d.png)
3. **이슈 제목 작성**
   - 제목은 [기기명-브라우저명-가로사이즈-페이지명] 형태로 작성
     예: `[mac-chrome-414px-메인] 게시글 아이템의 태그에서 #이 두개가 보여지는 현상`
4. **이슈 내용 작성**
   - 이슈 내용, 이미지 및 영상, 링크 등을 첨부
   - 필수: 링크
   - 선택: 이미지 및 영상 (권장)
5. **라벨링**
   - Assignees, Labels, Milestone 설정
   ![라벨 설정](https://user-images.githubusercontent.com/17779284/197138857-edcc0df6-ef86-460a-9587-72e4d51c3018.png)
6. **이슈 게시**
   - Submit New Issue 버튼 클릭하여 이슈를 게시
7. **Git Commit**
   - 이슈 해결 후, git commit 시 이슈 ID로 close
     예: `git commit -m "[closed #1] 해결된 이슈 내용"`

