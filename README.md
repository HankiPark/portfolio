
  
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
> 
> 수정 일자 : 2024.3.4
>
  > 이 프로젝트는 같은 사이즈의 4개의 bmp파일을 합쳐
  >
  > 1개의 bmp파일로 변환해주는 프로젝트입니다.

---


## C++ project


### 🍒Tetris 

[View Codes](https://github.com/HankiPark/Tetris-Win32)

- 개발기간 : 24.3.7 - 3.25

- 개발언어 : C++

> winapi를 사용하여 Tetris를 구현했습니다.
>
> 이동 키 (a, s, d)와 회전키 (r), 줄낙하(w)에 따라 블록의 진행방향이 결정됩니다.
>
> 한줄이 완성되면 그 줄이 제거되는 형식입니다.
>
> 혼자서 플레이 하는 것과 컴퓨터와 붙도록하는 두가지 모드를 구현하였고,
>
> 이는 실행 시 첫 메세지박스의 응답값에 따라 모드가 변경됩니다.
>
> 컴퓨터는 유전알고리즘에 따라 블록의 위치를 결정합니다.
>
> 컴퓨터와 플레이어의 블록이 다른속도로 내려오도록
>
> 스레드를 분리해 서로 다른 속도를 가지게끔했습니다.




### New Snake Game

[View Code](https://github.com/HankiPark/Mini/blob/main/NewSnake.cpp)

[View Video](https://www.youtube.com/watch?v=esDoLWXBmeY)

<img src="https://github.com/HankiPark/portfolio/assets/89247586/5f7f02d0-eb34-4d81-b63c-d0a3a5aa9d84"> </img>

- 개발기간 : 24.3.4-3.5

- 개발언어 : C++

> winapi를 사용하여 snake game을 재구현했습니다.
>
> 게임 시작 시 화면을 클릭하면 시작되며, 누르는 키 (w, a, s, d)에 따라 뱀의 진행방향이 결정됩니다.
>
> 사과를 먹으면 점수가 상승하며, 속도도 점차 빨라집니다.
>
> 뱀의 머리가 벽에 박거나, 몸통에 닿게 되면 게임 종료 팝업이 뜨며,
>
> 팝업창을 종료할 경우 게임판이 리셋됩니다.


### Omok

[View Code](https://github.com/HankiPark/Mini/blob/main/Omok.cpp)

[View Video](https://www.youtube.com/shorts/7D92rjbNsmQ)

<img src="https://github.com/HankiPark/portfolio/assets/89247586/4542c500-428c-4ad4-998f-6a928265c962"> </img>

- 개발기간 : 24.2.26-3.4

- 개발언어 : C++

> winapi를 사용하여 제약사항이 없는 오목을 구현했습니다.
>
> 게임 시작 시 1 vs 1 모드와 vs computer 모드를 묻는 팝업이 있으며, 선택에 따라 게임의 모드가 결정됩니다.
>
> vs 컴퓨터를 선택한 경우 시작(흑돌)은 무조건 플레이어이며
>
> 컴퓨터는 각 칸에 대해 정해진 로직으로 점수를 계산하여 가장 높은 칸 중 하나에 백돌을 배치합니다.
>
> 정확히 5칸을 연속으로 배치할 경우, 성공 이펙트 (완성된 5개의 돌이 커지며, 빨간 선으로 연결됩니다)와 함께 팝업창이 등장하며
>
> 팝업창을 종료할 경우 게임판이 리셋됩니다.

### Rock Paper Scissors 

[View Code](https://github.com/HankiPark/Mini/blob/main/RockPaperScissors.cpp)

- 개발기간 : 24.2.21-2.21

- 개발언어 : C++
 
> 간단한 가위바위보 게임을 구현했습니다.
>
> 잘못된 input에 대한 결과값과, 원하는 input에 대한 반응을 따로 구현했습니다.


### Number Guess Game

[View Code](https://github.com/HankiPark/Mini/blob/main/NumberGuessGame.cpp)

- 개발기간 : 24.2.21-2.21

- 개발언어 : C++

> Casino Number Guessing Game으로
>
> 가장 먼저 원금을 지정하고, 돈을 배팅하고, 추측할 숫자(1-10)를 입력하면
>
> 결과에 따라 배팅금 * 3 의 수익이나, 배팅금만큼의 손해를 얻게되는 게임입니다.
>
> 배팅금을 음수로 처리할 경우 추측이 맞을 경우 잃고, 틀릴 경우 돈을 얻게 되는 경우가 발생하였기에
>
> 배당금이 음수이거나 0 일 경우 다시 입력하도록 설정했습니다.

### Snake Game

[View Code](https://github.com/HankiPark/Mini/blob/main/SnakeGame.cpp)

[View Video](https://www.youtube.com/shorts/5xOzTOC4hDk)

<img src="https://github.com/HankiPark/Mini/assets/89247586/88ef687f-ae1f-456a-8f76-bfb6fbf4fa51"> </img>

- 개발기간 : 24.2.22-2.22

- 개발언어 : C++

> 뱀이 사과를 찾아 이동하고, 사과를 먹게 되면 뱀의 길이가 하나씩 늘어나는 게임입니다.
>
> 뱀이 벽에 머리를 박거나, 뱀의 몸통을 물게 되면 게임이 종료됩니다.
>
 - 수정 사항

> 사과가 화면에서 사라지는 경우가 발생
> 
>> 사과와 뱀의 머리의 위치를 좌표로 찍어 화면밖에 표기되게 하여 추적하였고,
>> 
>> 이후에 벽의 위치에 생성되는 경우가 있음을 파악하여 생성 좌표값을 재조정하였습니다.
>>
> 맵의 크기를 조정하는 옵션과 아무 조작 없을 경우 자동 이동하는 옵션을 생각중입니다.




---


