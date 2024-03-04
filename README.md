
  
# 🔉HankiPark

- 이름 : 박한기
- 생년월일 : 1993.07.07
- 학력 : 성균관대학교 (2020.02 졸업)
- 항상 배우는 자세로 임하는 개발자가 되겠습니다.

# 🔨Intro

안녕하세요. 박한기입니다.

국비지원교육으로 6개월간 Java를 위주로 한 개인, 팀 프로젝트를 진행하였고,

이후 1년간 C 개발자로 근무했습니다.

아직 작은 페이지이지만 곧 크게크게 키워나가도록 하겠습니다.

아래 티스토리는 코딩테스트를 풀고 풀이와 느낀점 등등을 정리한 사이트입니다.
  
[개인 티스토리](https://hanki0724.tistory.com/)


# ⚡프로젝트 소개

## Java project

### SolarSido
[View Code](https://github.com/HankiPark/solarSido)


국비교육과정 당시 MES(제조 실행 시스템)을 주제로 하여 만든 프로젝트입니다.

팀장으로 프로젝트를 진행하였으며, 맡은 역할은 

  - 개발 환경 구축
  - 일정 관리
  - 업무 분장
  - 클라이언트 UI 작업
  - DB 구축 및 관리
  - 로직 개발
  - 결과 통합

을 진행하였습니다.

<details>
  <summary>프로젝트 세부내역</summary>

  ## 개발 일정
  21.12.27-22.2.17
  <details>
    <summary>상세</summary>
    <img src="/pic/개발일정.png" width="800px" height="600px" title="개발일정.png" alt="개발일정.png"></img>
  </details>
  

  ## 주 사용 기술

  > javascript, java
  > 
  > Oracle, eGovFrame
  

  ## 구현 상세

  ### 업무 흐름도

<img width="800px" alt="업무흐름도" src="https://github.com/HankiPark/portfolio/assets/89247586/55101bf9-6e7c-4d8d-b2f5-de38eaf32ccb">



  ### DB 구현(생산)

<img width="800px" alt="db생산" src="https://github.com/HankiPark/portfolio/assets/89247586/1ac770df-2e2b-493d-812f-a2172dde9d67">



  ### 화면 구현

  <img src="/pic/화면구현 예시.png" width="800px" height="600px" title="화면구현 예시.png" alt="화면구현 예시.png"></img>

  <img src="/pic/화면구현 예시2.png" width="800px" height="600px" title="화면구현 예시2.png" alt="화면구현 예시2.png"></img>


</details>


---



## C project

### Merge 4 BMP File

[View Code](https://github.com/HankiPark/MergeBMP)


  > 개발 기간 : 2024.1.13-1.15
> 수정 일자 : 2024.3.4
>
  > 이 프로젝트는 같은 사이즈의 4개의 bmp파일을 합쳐
  >
  > 1개의 bmp파일로 변환해주는 프로젝트입니다.

---


## C++ project

### Rock Paper Scissors 

[View Code](https://github.com/HankiPark/Mini/blob/main/RockPaperScissors.cpp)

> 개발기간 : 24.2.21-2.21
>
> 개발언어 : C++
> 
> 간단한 가위바위보 게임을 구현해보았다.

<details> 
  <summary>고려 사항</summary>
  
  > 게임 종료 버튼 구현
> 
  > 가위바위보를 제외한 키를 눌렀을 때 어떻게 반응하게 할 것인지
> 
     이외의 키는 잘못된 input이라는 표기 후 다시 입력받도록 설정
> 
</details>

### Number Guess Game

[View Code](https://github.com/HankiPark/Mini/blob/main/NumberGuessGame.cpp)

> 개발기간 : 24.2.21-2.21
>
> 개발언어 : C++
>
> Casino Number Guessing Game으로
>
> 가장 먼저 원금을 지정하고, 돈을 배팅하고, 추측할 숫자(1-10)를 입력하면
>
> 결과에 따라 배팅금 * 3 의 수익이나, 배팅금만큼의 손해를 얻게되는 게임이다.

<details> 
  <summary>고려 사항</summary>

> 
  > 배팅금을 음수로 처리할 경우 추측이 맞을 경우 잃고, 틀릴 경우 돈을 얻게 되는 경우가 발생
>
    배당금이 음수이거나 0 일 경우 다시 입력하도록 설정

</details>

### Snake Game

[View Code](https://github.com/HankiPark/Mini/blob/main/SnakeGame.cpp)

> 개발기간 : 24.2.22-2.22
>
> 개발언어 : C++
>
> 뱀이 사과를 찾아 이동하고, 사과를 먹게 되면 뱀의 길이가 하나씩 늘어나는 게임이다.
>
> 뱀이 벽에 머리를 박거나, 뱀의 몸통을 물게 되면 게임이 종료된다.

<details> 
  <summary>고려 사항</summary>
  
  > 게임 종료 버튼 구현
> 
  > 사과가 화면에서 사라지는 경우 발생
> 
    사과와 뱀의 머리의 위치를 좌표로 찍어 화면 밖에 표기되도록 하여 추적함

    벽의 위치에 생성되는 경우가 있어 생성 좌표값을 재조정하고,

    뱀의 머리나 몸통에 사과가 생성된다면 사과가 다른 곳에 생길 때까지 사과를 rand로 재발생시킴

  > 맵의 크기 조정하기 위한 옵션과 아무 조작없을 경우 자동 이동하는 옵션을 생각중이다.
> 
</details>


---


