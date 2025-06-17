# 만능매크로 - 설명 <br>

## 조건 <br>
### 조건 사용 <br>
- 조건을 사용해 보다 복잡한 매크로를 구현할 수 있습니다. <br>
![Animation17](https://github.com/user-attachments/assets/0977d4f6-63c2-400e-ad64-3bc664ebc8e9) <br>
1. 공간 탭으로 이동해서 공간 종류를 **숫자 공간** 으로 설정하고 ```test``` 공간을 추가합니다. <br>
![image](https://github.com/user-attachments/assets/876d331c-445b-41ae-ac1f-a9ed98c97e1d) <br>
2. 연산 탭으로 이동해서 ```test```를 선택하고 ```test+1``` 을 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/50349922-86c2-485d-b586-1b822a65667e) <br>
3. 조건 탭으로 이동해서 ```test```를 선택하고 ```10```을 입력합니다. 그리고 추가 버튼을 누릅니다. <br>
  -  ```test```가 ```10```이 아니라면 거짓으로 이동합니다. <br>
![image](https://github.com/user-attachments/assets/744b0439-85d4-4294-b5fb-0aaf436d5d9d) <br>
4. 이동 탭으로 이동해서 ```0``` 입력 후 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/fca223dc-e171-4441-bfe9-e93674a8bdc6) <br>
5. 3번 라인의 "조건문을 실행합니다."를 클릭해 왼쪽의 빨간색 선을 드래그 해서 2번 라인 ```test+1```에 놓습니다. <br>
  - ```test```의 값이 ```10```일 때까지 계속 ```test+1```을 실행합니다. <br>
![Animation22](https://github.com/user-attachments/assets/0b2cfc5f-22bf-4d02-b861-ae9c151d6ac8) <br>
6. 일반 탭으로 이동해서 **실행중인 매크로를 추적 합니다.** 를 체크하고 완료 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/68c18bf4-5b6d-4cda-948c-60d0444ee9c5) <br>
7. 추적 창에서 ▼ 버튼을 클릭해 ```test```의 값이 ```10``` 까지 늘어나는 것을 확인합니다. <br>
![Animation23](https://github.com/user-attachments/assets/a053f37a-4dbe-4370-a03f-4f0a5ca3d0e8) <br>

### 이미지 검색 + 조건 사용 <br>
- 이미지 검색이 실패할 때 별도의 처리를 위한 로직을 설정합니다. <br>
![Animation18](https://github.com/user-attachments/assets/ceab6135-d409-46a7-aa46-617caa161dab) <br>
1. 이미지 탭으로 이동해서 이미지를 캡처한 다음 추가합니다. <br>
![Animation24](https://github.com/user-attachments/assets/1040a7df-709f-4750-ad55-d42a7942e0cd) <br>
2. 조건 탭으로 이동해서 **받은 성공과 실패** 를 선택하고 **성공** 을 선택합니다. 그다음 추가 버튼을 누릅니다. <br>
![image](https://github.com/user-attachments/assets/51da488f-2760-4311-a9a6-101834a5865a) <br>
3. 마우스 탭으로 이동해서 X, Y에 ```이미지 크기 / 2```를 입력하고 추가 버튼을 누릅니다. (추가한 "이미지 검색을 실행합니다"를 더블클릭하면 크기 알아내는 게 가능) <br>
![image](https://github.com/user-attachments/assets/326b1373-5402-4c74-9844-77deb52b4b2f) <br>
4. 1번 라인의 "이미지 검색을 실행합니다."를 클릭해 왼쪽의 분홍색 선을 드래그 해서 2번 라인 조건문에 놓습니다. <br>
![Animation25](https://github.com/user-attachments/assets/3fdc3d1f-0d9e-4c73-ba59-86c318b9320f) <br>
5. 2번 라인의 "조건문을 실행합니다."를 클릭해 왼쪽의 빨간색 선을 드래그 해서 1번 라인 이미지 검색에 놓습니다. <br>
  - 이미지 검색에 실패할 때 성공할 때까지 이미지 검색을 할 것입니다. <br>
![Animation26](https://github.com/user-attachments/assets/5b9db4ce-1983-4fb0-b567-717ac5967672) <br>
6. 2번 라인의 "조건문을 실행합니다."를 클릭해 왼쪽의 파란색 선을 드래그 해서 3번 라인 마우스 이동에 놓습니다. <br>
  - 이미지 검색에 성공할 때 3번 라인으로 이미지 좌푯값이 들어가 이미지가 있는 쪽으로 커서가 이동되고 X,Y 좌표가 ```29/2``` 만큼 추가로 이동될 것입니다. (가운데) <br>
![Animation27](https://github.com/user-attachments/assets/b46d3465-62fb-4b2e-a4b1-bc004aaee198) <br>
7. 일반 탭으로 이동해서 완료 버튼을 누르고 매크로를 실행합니다. <br>
![image](https://github.com/user-attachments/assets/becb478f-4b66-4385-ac75-3184b293d974) <br>
