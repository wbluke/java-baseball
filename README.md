# Java-Baseball 구현 기능 목록

### main 메소드 구현 

- 무한 루프와 switch문을 사용하여 게임의 기본 틀 구현 (1번 - 게임, 2번 - 종료)
- 잘못된 입력에 대하여 예외 처리 (방어적 코딩)

### 컴퓨터(com)의 랜덤 숫자 생성

- 랜덤 함수를 이용하여 세 개의 숫자 생성
- 숫자 세 개가 서로 중복되지 않도록 체크하기
- 추후에 사용자의 숫자와 비교할 수 있도록 field에 보관

### 사용자(user)의 숫자 입력을 받기

- 사용자의 입력 받기
- 잘못된 입력에 대하여 예외 처리 (방어적 코딩)
- 게임 기준에 맞는 입력인지 검사해서 알려주기 (서로 다른 세 자리 숫자, 0 포함 여부)

### 사용자(user)의 입력과 컴퓨터(com)의 입력을 비교하여 결과 알려주기

- 별도의 메소드로 처리 후 정답이 나올 때까지 반복
- 컴퓨터(com)의 숫자와 비교하여 결과문 출력하기
- 3 스트라이크가 나오면 게임 종료