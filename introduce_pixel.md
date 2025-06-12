# 만능매크로 - 설명 <br>

## 픽셀 <br>
### 픽셀값 대입 <br>
- 특정 좌표의 픽셀 색깔을 숫자 공간에 대입할 수 있으며, RGB값으로 나눌 수 있습니다. <br>
![Animation27](https://github.com/user-attachments/assets/9d52f91c-3b51-46ba-840b-57d72a704c9f) <br>
1. 공간 탭으로 이동해서 공간 종류를 **숫자 공간** 으로 설정하고 ```a``` 공간을 추가합니다. <br>
![image](https://github.com/user-attachments/assets/a403875c-2737-4563-9c7b-de09209a69cd) <br>
2. 공간 탭으로 이동해서 공간 종류를 **숫자 공간** 으로 설정하고 ```r``` 공간을 추가합니다. <br>
![image](https://github.com/user-attachments/assets/61f47c3a-45e3-4a65-8319-18785e245505) <br>
3. 공간 탭으로 이동해서 공간 종류를 **숫자 공간** 으로 설정하고 ```g``` 공간을 추가합니다. <br>
![image](https://github.com/user-attachments/assets/cf172eac-548f-41f4-aabf-9df511d1f2ea) <br>
4. 공간 탭으로 이동해서 공간 종류를 **숫자 공간** 으로 설정하고 ```b``` 공간을 추가합니다. <br>
![image](https://github.com/user-attachments/assets/622739ee-28e6-4df1-b6cc-b581b61e8cee) <br>
5. 픽셀 탭으로 이동해서 픽셀값 대입에 X: ```MOUSE_X```, Y: ```MOUSE_Y``` 라고 입력 후, 숫자 공간 a를 선택한 다음 **추가**를 누릅니다. <br>
  - ```MOUSE_X``` 는 현재 커서가 위치한 X 좌푯값을 의미합니다. <br>
  - ```MOUSE_Y``` 는 현재 커서가 위치한 Y 좌푯값을 의미합니다. <br>
![image](https://github.com/user-attachments/assets/71fc5ef1-33f9-4f29-8828-d50c9fb752c4) <br>
6. 연산 탭으로 이동해서 ```r```을 선택하고 ```rgb_r(a)``` 을 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
  - ```rgb_r``` 는 픽셀값 대입에서 받아온 숫자에서 빨간색 수치를 가져오는데 쓰이는 함수입니다. <br>
![image](https://github.com/user-attachments/assets/ccb06d82-f5b1-42c6-945c-64ec24b7d865) <br>
7. 연산 탭으로 이동해서 ```g```을 선택하고 ```rgb_g(a)``` 을 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
  - ```rgb_g``` 는 픽셀값 대입에서 받아온 숫자에서 초록색 수치를 가져오는데 쓰이는 함수입니다. <br>
![image](https://github.com/user-attachments/assets/7fad10a4-a92d-4865-b62d-2eae416bd6b8) <br>
8. 연산 탭으로 이동해서 ```b```을 선택하고 ```rgb_b(a)``` 을 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
  - ```rgb_b``` 는 픽셀값 대입에서 받아온 숫자에서 파란색 수치를 가져오는데 쓰이는 함수입니다. <br>
![image](https://github.com/user-attachments/assets/4a97f18d-1b31-42a0-931b-f800648ff92c) <br>
9. 이동 탭으로 이동해서 ```0``` 입력 후 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/f8d2d243-8047-4fe1-85c6-383cf95267e2) <br>
10. 9번 라인 "이동 합니다"를 클릭해 왼쪽 검은색 선을 드래그 해서 5번 라인에 놓습니다. <br>
![Animation15](https://github.com/user-attachments/assets/ac9c02ed-418d-4df4-a881-876b14f09d81) <br>
11. 일반 탭으로 이동해서 **실행중인 매크로를 추적 합니다.** 를 체크하고 완료 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/96705cce-c593-47c8-aa91-751e3d5d1ff9) <br>
12. 추적 창에서 ▼ 버튼을 1번 클릭하고 이후에는 설정된 실행키를 눌러서 test 값에 커서 위치가 담겨있는지 확인합니다. <br>
![Animation16](https://github.com/user-attachments/assets/08b4e18b-ebd8-4e0f-8713-be0816e4a9f9) <br>
