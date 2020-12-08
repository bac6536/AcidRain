# AcidRain

AcidRain 프로그램 설명

1. '난이도' 메뉴에서 게임의 난이도를 지정할 수 있습니다.

2. '게임 진행' 메뉴에서 '게임 시작' 메뉴를 눌러 게임을 시작합니다.

3. 게임이 진행되고 있는 도중에 게임을 포기하고 싶다면 '게임 진행' 메뉴에서 '게임 포기' 메뉴를 눌러 게임을 포기합니다.

4. 제한 시간(2분)이 소진되거나 체력이 0이 되면 게임이 종료됩니다.

5. 각 난이도에 따라 배경 이미지와 단어의 낙하 속도, 단어 1개 제거 시 점수, 단어 1개를 놓쳤을 경우에 입는 피해량이 다릅니다.

6. 체력이 일정 이하로 떨어질 경우에는 배경 이미지에 변화가 발생합니다.

7. 게임이 종료되거나 게임을 포기하면 현재 점수를 랭킹 데이터베이스에 등록할 수 있습니다.

8. '랭킹' 메뉴에서 '랭킹 보기' 메뉴를 눌러 랭킹 데이터베이스의 최상위 플레이어 10명의 정보를 볼 수 있습니다.

9. 플레이어의 순위는 점수에 의해 결정되며, 점수가 같을 경우 더 어려운 난이도로 플레이한 플레이어가 상위 순위로 기록됩니다.

10. 게임 구동 시 단어장 데이터베이스로부터 단어 정보들을 받아오며, 데이터베이스 서버와의 연결에 실패할 경우 동봉된 단어장 텍스트 파일(한글.txt)로부터 읽어들인 단어 데이터를 사용합니다.

11. 데이터베이스 서버와의 연결에 실패할 경우 랭킹 등록 및 조회가 불가능합니다.

12. 게임 구동 시 resx 문제가 발생할 경우 동봉된 'Form1.resx 문제.txt' 파일을 참조하여 문제를 해결할 수 있습니다.