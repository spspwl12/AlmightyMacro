# 만능매크로 - 설명 <br>

## 연산 <br>
### 간단한 연산 <br>
- 1씩 더하는 연산예제 입니다. <br>
![Animation15](https://github.com/user-attachments/assets/9a6cd041-d8fe-42e9-bdf4-47057910b37f) <br>
1. 공간 탭으로 이동해서 공간 종류를 **숫자 공간** 으로 설정하고 ```test``` 공간을 추가합니다. <br>
![image](https://github.com/user-attachments/assets/876d331c-445b-41ae-ac1f-a9ed98c97e1d) <br>
2. 연산 탭으로 이동해서 ```test```을 선택하고 ```test+1``` 을 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/50349922-86c2-485d-b586-1b822a65667e) <br>
3. 이동 탭으로 이동해서 ```0``` 입력 후 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/9e8aa1b0-bd4b-410a-ac64-071424ff52d3) <br>
4. 3번 라인 "이동 합니다"를 클릭해 왼쪽 검은색 선을 드래그 해서 2번 라인 ```test+1```에 놓습니다. <br>
![Animation18](https://github.com/user-attachments/assets/a546c5e8-fec3-4d6e-be22-d7ad0d8c9c59) <br>
5. 일반 탭으로 이동해서 **실행중인 매크로를 추적 합니다.** 를 체크하고 완료 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/bd763749-8491-4a14-8c49-ad78c59d0a44) <br>
6. 추적 창에서 ▼ 버튼을 클릭해 1씩 늘어나는 ```test```의 값을 확인합니다. <br>
![Animation19](https://github.com/user-attachments/assets/9a77ee25-f966-4ced-bf10-69fc03ff43f8) <br>

### 마우스 좌표 구하기 <br>
- 좌표 공간에 현재 마우스 커서 위치를 담을 수 있습니다. <br>
![Animation26](https://github.com/user-attachments/assets/859bf3d7-a968-4ede-b3a5-e7906f6bcf0e) <br>
1. 공간 탭으로 이동해서 공간 종류를 **좌표 공간** 으로 설정하고 ```test``` 공간을 추가합니다. <br>
![image](https://github.com/user-attachments/assets/6e648d23-76f0-443c-907e-8ba823f58632) <br>
2. 연산 탭으로 이동해서 ```test.X```을 선택하고 ```MOUSE_X``` 을 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
   - ```MOUSE_X``` : 현재 마우스 커서 X 좌표를 구하는 예약된 변수입니다. <br>
![image](https://github.com/user-attachments/assets/f619646c-54f1-43bd-a907-b6b3f464f1e7) <br>
3. 연산 탭으로 이동해서 ```test.Y```을 선택하고 ```MOUSE_Y``` 을 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
   - ```MOUSE_Y``` : 현재 마우스 커서 Y 좌표를 구하는 예약된 변수입니다. <br>
![image](https://github.com/user-attachments/assets/e419dd2e-7532-4b86-9308-6d50caefad6b) <br>
4. 이동 탭으로 이동해서 ```0``` 입력 후 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/7a426210-fd53-42bb-8e3f-8dcc27c4e079) <br>
5. 4번 라인 "이동 합니다"를 클릭해 왼쪽 검은색 선을 드래그 해서 2번 라인에 놓습니다. <br>
![Animation13](https://github.com/user-attachments/assets/11b6b8ea-8b6f-4aa8-ba92-8ac50445cf6d) <br>
6. 일반 탭으로 이동해서 **실행중인 매크로를 추적 합니다.** 를 체크하고 완료 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/97a743a5-e8b0-4a23-ba34-1b7c678b3dc5) <br>
7. 추적 창에서 ▼ 버튼을 1번 클릭하고 이후에는 설정된 실행키를 눌러서 ```test``` 값에 커서 위치가 담겨있는지 확인합니다. <br>
![Animation14](https://github.com/user-attachments/assets/48979000-51f2-453a-b1c2-c9168cbf6b4e) <br>

### 함수의 사용 <br>
- 함수를 사용하면 보다 복잡한 로직을 구현할 수 있습니다. <br>
![Animation16](https://github.com/user-attachments/assets/67f5116e-c995-4bfa-86ec-ef86ae593be1) <br>
1. 공간 탭으로 이동해서 공간 종류를 **숫자 공간** 으로 설정하고 ```a```, ```b```, ```c``` 공간을 생성합니다. <br>
![Animation20](https://github.com/user-attachments/assets/73a156c8-63a0-420c-aaf4-a5228f86f5ae) <br>
2. 연산 탭으로 이동해서 ```a```를 선택하고 ```10```을 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/71e9adaa-ea6b-4cda-8646-9c6ff1700ae2) <br>
3. 연산 탭으로 이동해서 ```b```를 선택하고 ```20```를 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/0e453d47-d3fb-4eff-86d8-e97d7fd1cf65) <br>
3. 연산 탭으로 이동해서 ```c```를 선택하고 ```min(a,b)```를 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
  - ```min``` 함수는 두 수를 비교해서 가장 작은 값을 반환하는 함수입니다. <br>
![image](https://github.com/user-attachments/assets/9e3a48b7-cc60-494b-8920-ed9dbf931de7) <br>
4. 연산 탭으로 이동해서 ```c```를 선택하고 ```max(a,b)```를 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
  - ```max``` 함수는 두 수를 비교해서 가장 큰 값을 반환하는 함수입니다. <br>
![image](https://github.com/user-attachments/assets/c4092dcd-21ad-4dc3-9918-801b891c7940) <br>
5. 이동 탭으로 이동해서 ```0``` 입력 후 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/1c768571-cb0b-4b1c-8e20-4c7fa35a30b0) <br>
6. 일반 탭으로 이동해서 **실행중인 매크로를 추적 합니다.** 를 체크하고 완료 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/072ce11e-779e-4b23-8dfa-fa288e3501a3) <br>
7. 추적 창에서 ▼ 버튼을 클릭해 min 함수 반환 값이 ```10```임을 확인하고 max 함수 반환 값이 ```20```임을 확인합니다.  <br>
![Animation21](https://github.com/user-attachments/assets/f353ce4d-5f91-40b4-823b-a28f8f4df13b) <br>
