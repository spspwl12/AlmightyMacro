# 만능매크로 - 설명

## 이미지
### 이미지 캡처
- 이미지 검색하기 전 이미지를 준비하는 작업입니다. <br>
![Animation8](https://github.com/user-attachments/assets/57d18539-e748-42c2-8127-e88bdca1223c)
1. 이미지 탭으로 이동합니다.<br>
![image](https://github.com/user-attachments/assets/cc02cb33-1117-4fb7-8357-1434e1141eb0)
2. 이미지 선택 버튼을 누릅니다.<br>
![image](https://github.com/user-attachments/assets/2c9abcac-0595-4b0b-9054-5e3e3ff47b39)
3. 캡처하고 싶은 이미지를 드래그 드롭해서 잘라냅니다.<br>
![Animation1](https://github.com/user-attachments/assets/d8be460a-8f0e-409f-bc87-3a74c731cf6e)
4. 이미지 편집기가 뜨면 이미지 여백을 잘라내기 위해 자르기 메뉴를 누릅니다.<br>
![image](https://github.com/user-attachments/assets/29a3141c-62ad-4609-9fd1-f180a445eb5e)
5. 마우스 스크롤을 위 아래로 움직여 확대 설정이 가능하며, 마우스 왼쪽 버튼으로 드래그 드롭을 해 여백을 잘라냅니다. (여백이 있으면 이미지 검색이 느립니다.)<br>
![Animation2](https://github.com/user-attachments/assets/6fe41ca7-e8fb-4ba1-8c13-0ef9eed60506)
6. 저장을 누릅니다.<br>
![image](https://github.com/user-attachments/assets/144bc3b3-d06f-40a7-9771-dd33a3611f02)
7. 이미지 저장이 파일로 완료되어서 자동으로 사진 이름이 등록된 모습입니다.<br>
![image](https://github.com/user-attachments/assets/2205a060-3c26-4a13-aae2-b6228e1ed6fa)

### 이미지 캡처 ( base64 )
- 이미지를 사진이 아닌 이미지 정보가 들어간 문자열로 저장할 수도 있습니다. (이미지 파일이 필요 없기 때문에 간편합니다.)<br>
![Animation9](https://github.com/user-attachments/assets/c2eaab9f-13ed-4849-832c-c52d7b40a65c)
1. 메뉴 설정 -> 설정으로 들어갑니다. <br>
![Animation3](https://github.com/user-attachments/assets/4d81fd14-e00f-45f3-a66e-de31581ee3f2)
2. 캡처 타입을 base64 로 설정합니다.<br>
![image](https://github.com/user-attachments/assets/5bdc4c05-2aae-467e-a6db-4c8cbb99dc1f)
3. 설정 창을 닫고 이미지 탭으로 이동합니다.<br>
![image](https://github.com/user-attachments/assets/cc02cb33-1117-4fb7-8357-1434e1141eb0)
4. 이미지 선택 버튼을 누릅니다.<br>
![image](https://github.com/user-attachments/assets/2c9abcac-0595-4b0b-9054-5e3e3ff47b39)
5. 캡처하고 싶은 이미지를 드래그 드롭해서 잘라냅니다.<br>
![Animation1](https://github.com/user-attachments/assets/d8be460a-8f0e-409f-bc87-3a74c731cf6e)
6. 이미지 편집기가 뜨면 이미지 여백을 잘라내기 위해 자르기 메뉴를 누릅니다.<br>
![image](https://github.com/user-attachments/assets/29a3141c-62ad-4609-9fd1-f180a445eb5e)
7. 마우스 스크롤을 위 아래로 움직여 확대 설정이 가능하며, 마우스 왼쪽 버튼으로 드래그 드롭을 해 여백을 잘라냅니다. (여백이 있으면 이미지 검색이 느립니다.)<br>
![Animation2](https://github.com/user-attachments/assets/6fe41ca7-e8fb-4ba1-8c13-0ef9eed60506)
8. 저장을 누릅니다.<br>
![image](https://github.com/user-attachments/assets/144bc3b3-d06f-40a7-9771-dd33a3611f02)
9. 이미지 저장이 base64로 완료된 모습입니다.<br>
![image](https://github.com/user-attachments/assets/a79c8bb4-94b6-4057-af54-2f51080424ed)

### 이미지 캡처 (복수개)
- 같은 이미지를 여러개 검색도 할 수 있습니다.<br>
![Animation11](https://github.com/user-attachments/assets/d609a741-9615-450c-9c59-a977853081c2)
1. 이미지 탭으로 이동해 검색할 이미지를 선택합니다. (테스트 버튼을 눌러 이미지가 제대로 검색되는지 확인 필요)<br>
![Animation5](https://github.com/user-attachments/assets/ae2f1729-4993-4546-8f7c-cd02ea0a0de1)
2. **멀티** 를 체크합니다.<br>
![image](https://github.com/user-attachments/assets/e0cde0c1-b5ca-41e2-9fbc-51def630ae9e)
3. **테스트** 버튼을 눌러 이미지 개수가 올바른지 확인합니다.<br>
![Animation6](https://github.com/user-attachments/assets/a605206a-b5a1-48ee-9a39-a4d2b5e91d29)
4. 올바르지 않다면 민감도를 조절해 올바른 개수가 나올 때까지 시도합니다.<br>
![Animation7](https://github.com/user-attachments/assets/e7cc29a3-43fd-4030-98b1-3c504a3b12dc)

### 이미지 검색 후 행동 추가
- 이미지를 화면에서 검색 후 특정 명령을 내리는 작업을 할 수 있습니다.<br>
![Animation10](https://github.com/user-attachments/assets/06f3eaa1-64af-4a13-97cf-911a2d78dd80)
1. 이미지 탭으로 이동해 검색할 이미지를 선택합니다. (테스트 버튼을 눌러 이미지가 제대로 검색되는지 확인 필요)<br>
![Animation1](https://github.com/user-attachments/assets/3994bc78-6192-4102-ab9e-107388e6bf15)
2. 추가 버튼을 눌러 이미지 검색을 추가합니다.<br>
![image](https://github.com/user-attachments/assets/af46951e-061a-4131-baa4-1b6e681e750f)
3. 마우스 탭으로 가서 X, Y에 캡처한 ```이미지 크기 / 2```를 적습니다. (추가한 "이미지 검색을 실행합니다"를 더블클릭하면 크기 알아내는 게 가능)<br>
![Animation2](https://github.com/user-attachments/assets/6622ed5c-a793-431a-934b-8fd61f9f087e)
4. 추가 버튼을 눌러 마우스 이동을 추가합니다.<br>
![image](https://github.com/user-attachments/assets/06eb259d-915d-4db0-a536-723d9d09f982)
5. 첫 번째의 "이미지 검색을 실행합니다"를 클릭하면 분홍색 선이 나오는데 분홍색 선을 드래그해서 2번의 "마우스를 이동합니다"에 놓습니다.<br>
![Animation3](https://github.com/user-attachments/assets/ae40c6ff-d89e-4b27-b7d4-d341f25f0c71)
6. 일반 탭으로 이동해 완료 버튼을 눌러 실행합니다.<br>
![Animation4](https://github.com/user-attachments/assets/5ddc8e3a-ddfa-4015-b616-81dcc8405b9a)

### 이미지 검색 후 행동 추가 (복수개)
- 이미지를 화면에서 검색 후 특정 명령을 내리는 작업을 할 수 있습니다.<br>
![Animation12](https://github.com/user-attachments/assets/e0b34e2a-31fa-410f-8c14-615ed69b2e1f)
1. 이미지 탭을 이동해 검색할 이미지를 선택합니다. (테스트 버튼을 눌러 이미지가 제대로 검색되는지 확인 필요)<br>
![Animation8](https://github.com/user-attachments/assets/8ea2c157-ad11-4ab4-9018-f82f2ac3d98c)
2. 정렬을 체크하고 Y 기준으로 설정합니다.<br>
![Animation9](https://github.com/user-attachments/assets/92bf2f9b-b6c8-480d-8006-5efec2ceb88a)
3. 추가 버튼을 눌러 이미지 검색을 추가합니다.<br>
![image](https://github.com/user-attachments/assets/29ab02cb-8cd5-491b-bc60-ae3d597cf631)
4. 공간 탭으로 이동해서 공간 종류를 **연속 좌표 공간** 으로 설정하고 ```xy``` 공간을 추가합니다.<br>
![image](https://github.com/user-attachments/assets/e249ee84-d46d-4b7f-9887-89ef674a174c)
5. 공간 탭으로 이동해서 공간 종류를 **숫자 공간** 으로 설정하고 ```i``` 공간을 추가합니다.<br>
  - ```i```의 처음 값은 ```0```입니다.
![image](https://github.com/user-attachments/assets/6cf06e11-a175-4c95-ab88-ccbe267c3eae)
6. 연산 탭으로 이동해서 추가했던 공간 중 ```i``` 를 선택하고 ```i+1``` 를 입력 후 추가 버튼을 누릅니다.<br>
![image](https://github.com/user-attachments/assets/2449104c-5668-425c-98dc-df8d42b9e032)
7. 마우스 탭으로 이동해서 X에 ```xy(i)``` 또는 ```xy(i).x``` 라고 입력하고 Y에 ```xy(i)``` 또는 ```xy(i).y``` 라고 입력 후 추가 버튼을 누릅니다.<br>
  - ```xy```에는 검색한 이미지의 좌표가 들어가 있으며, ```xy(1)```은 첫 번째 이미지의 좌표,```xy(2)```는 두 번째 이미지의 좌표가 들어가 있습니다.
  - x 또는 y가 입력될 입력 칸에는 ```.x```, ```.y``` 가 생략이 가능합니다.<br>
![image](https://github.com/user-attachments/assets/cf131897-53a6-4dfa-aae8-520b7fd05f1b)
8. 딜레이 탭으로 이동해서 약간의 딜레이를 추가합니다.<br>
![image](https://github.com/user-attachments/assets/74e3236b-4edb-47e1-a1f6-eb3b95a8bb95)
9. 조건 탭으로 이동해서 ```i``` 를 선택한 다음 오른쪽에는 ```count(xy)```를 입력하고 추가 버튼을 누릅니다.<br>
  - ```count(xy)```는 검색된 이미지의 개수를 반환합니다.
  - ```i```는 현재 이미지의 번호를 나타내며, ```i```의 값이 이미지 개수와 같다 라는 조건을 충족할 때까지 반복해야 합니다.
![image](https://github.com/user-attachments/assets/82e97ca1-39d8-46d9-afed-a9c0959722dd)
10. 1번의 "이미지 검색을 실행합니다."를 클릭해 왼쪽의 분홍색 선을 드래그해서 2번의 ```xy``` 연속공간에 놓습니다.<br>
![Animation10](https://github.com/user-attachments/assets/4fc4a639-bbae-44b8-aefd-83ebf3c99e7e)
11. 7번의 "조건문을 실행합니다."를 클릭해 왼쪽의 빨간색 선을 드래그 해서 4번 ```i+1```에 놓습니다.
![Animation11](https://github.com/user-attachments/assets/2b872f75-9396-4101-acbe-d64ceffeb84e)
12. 일반 탭으로 이동해서 완료 버튼을 눌러 실행합니다.<br>
![Animation12](https://github.com/user-attachments/assets/23ea3c54-80b0-4842-8c14-e432e6e14731)





















