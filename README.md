# 2019-2st-Algorithm
https://opensrcdesign.com/designDetail/3441 참조

# 목표 
C++ 프로그래밍 언어로 ncurses library 를 사용하여 push box game 을 구현한다.
단, 자동으로 수행될 수 있도록 알고리즘을 구현하는 것이 핵심임. 
팀 프로젝트로 수행한다.

# 1단계
ncurses library 함수들을 사용하여 아래와 같은 2 차원 배열로 표시된 push box
map 을 game 화면으로 표시하는 프로그램을 완성한다. 그림의 세부사항은 각자
정한다. 아래 보이는 예의 배열에서 1 은 벽을, 2 는 상자를, 3 은 목적지를 , 4 는
바깥부분을 나타내므로 각각 다른 색으로 화면에 구분이 되게 표시한다. 다음과 같은
map 은 오른쪽 그림과 유사한 모양으로 표시된다. (캐릭터 제외)

# 2단계
1 단계의 맵 위에 캐릭터를 표시하고 화살표를 입력받아 캐릭터가
움직이도록 프로그램을 완성한다. 프로그램은 캐릭터의 이동방향에 벽이 있거나
상자가 두개 이상 연속으로 있으면 캐릭터가 움직이지 않도록 해야하고, 이동 방향에
상자가 한 개 있으면서 그 상자 반대편이 또다른 상자나 벽으로 막혀있지 않으면
상자도 캐릭터와 함께 이동 방향으로 한 칸 이동해야 한다. (게임 방법은 실제
프로그램을 설치하여 배울 수 있다.)

# 3단계
2 단계 프로그램에서 step 횟수 (캐릭터가 이동한 횟수) 와 push 횟수 (상자가
움직인 횟수) 를 화면에 보여주고 모든 상자가 목적지에 도달하면 게임을 끝내고 다음
map 으로 넘어가서 다시 게임을 시작하는 프로그램을 완성하라. 샘플 게임 맵은
다음과 같다. 그 외의 기능을 추가해도 된다. 추가한 기능이 있으면 보고서에 설명을
포함하라.

# 4단계
위와 같은 작업을 자동으로 수행할 수 있도록 구현하시오. 세부적인
알고리즘은 보고서에서 기술하시오.
(3.1) Box 가 1 개인 경우를 해결할 수 있는 수준.
(3.2) Box 가 2 개인 경우를 해결할 수 있는 수준.
(3.3) Box 가 2 개 이상인 경우를 해결할 수 있는 수준.
(제한조건) 게임의 크기가 최대 8x8 으로 간주해도 됨.
