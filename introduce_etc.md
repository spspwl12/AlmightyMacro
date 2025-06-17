# 만능매크로 - 설명 <br>

## 기타 <br>
### 부드러운 마우스 움직임 <br>
- 마우스 움직임을 사람처럼 부드럽게 설정할 수 있습니다. <br>
![Animation29](https://github.com/user-attachments/assets/fb60ffc0-164d-4088-af67-1b37a6382e85) <br>
1. 다음 매크로를 복사 붙여넣기 합니다. <br>
```
Space,0,xy
Calculate,xy.X,MOUSE_X
Calculate,xy.Y,MOUSE_Y
MouseMove,xy,xy
MouseClick,0
MouseMove,xy+600,xy
MouseClick,1
Calculate,xy.Y,xy.y+30
PauseDelay,300
MovePos,4
```
![Animation18](https://github.com/user-attachments/assets/3899c917-b739-45c5-933a-82a8485304ae) <br>
2. 메뉴의 설정 -> **설정**을 클릭합니다. <br>
![image](https://github.com/user-attachments/assets/a3fe8e02-2a4f-4347-8606-eb104a7a8e73) <br>
3. **조작**을 클릭합니다. <br>
![{31B315FA-6141-410E-BAA4-3A90DA64BC59}](https://github.com/user-attachments/assets/8dd3c6bb-59b1-43ff-8b1b-1ccbf7b4f1eb) <br>
4. **마우스 커서를 이동할 때, 사람이 움직이는 것처럼 이동합니다.** 를 체크합니다. 그리고 설정창을 닫습니다. <br>
![image](https://github.com/user-attachments/assets/041877bf-5c65-45be-8feb-ec2a534058f2) <br>
5. 일반 탭으로 이동해서 완료 버튼을 누르고 매크로를 실행해봅니다. <br>
![Animation20](https://github.com/user-attachments/assets/daa6c2f1-9f1b-4b09-b14e-a1aa55624699) <br>
