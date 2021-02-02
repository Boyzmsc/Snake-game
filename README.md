# Snake Game

Program snake-game using C++

## 1. Manual

1. zip파일을 Download 받는다.

2. Terminal에 make run을 입력한다.

3. 게임화면이 나오면 y를 눌러 시작한다.

4. 게임을 진행하면서 4개의 Stage의 Mission을 Clear하도록 한다. 

5. 벽에 충돌하거나 Snake의 길이가 3미만이면 게임이 종료된다.

6. Stage 4까지 모든 Mission을 Clear한다면 성공한다.



## 2. Run Screen

<div style="text-align: center"><table><tr>
  <td style="text-align: center">
    <img src="https://user-images.githubusercontent.com/28584213/85833738-30047a80-b7cd-11ea-8b76-34ffaab23e32.png" width="400"/>
</td>
  <td style="text-align: center">
    <img src="https://user-images.githubusercontent.com/28584213/85833755-3692f200-b7cd-11ea-9fd2-36eeeeb275a7.png" width="400"/>
</td>
</tr>
  <tr>
  <td style="text-align: center">
<img src="https://user-images.githubusercontent.com/28584213/85833756-38f54c00-b7cd-11ea-993b-1050f11055b0.png" width="400"/>
</td>
<td style="text-align: center">
<img src="https://user-images.githubusercontent.com/28584213/85833763-3abf0f80-b7cd-11ea-8462-acf2c125639b.png" width="400"/>
</td></tr>
</table></div>



## 3. Implementation

#### 1단계

- [X] Ncurses Library 함수들을 사용하여 2차원 배열로 된 Snake Map을 Game 화면으로 출력한다.

#### 2단계

- [X] 맵 위에 Snake를 표시하고, 방향키를 입력받아 Snake가 움직이도록 프로그램을 구현한다.

#### 3단계

- [X] Map 위에 Growth Item와 Poison Item을 출현하도록 구현한다.
- [X] 화면상에 출력 시 색이나 기호를 달리하여 구분할 수 있도록 한다.

#### 4단계

- [X] 벽 내부에 임의의 위치에 한 쌍의 Gate가 출현할 수 있도록 구현하고 Gate에 Snake가 통과할 수 있도록 한다.

#### 5단계

- [X] 우측에 게임 점수를 표시하는 화면을 출력한다.
- [X] Mission을 완료하면 다음 Map으로 넘어가도록 구현한다. 
- [X] Stage는 최소 4개로 구성하고 각 Stage의 Map을 다르게 구현한다.

