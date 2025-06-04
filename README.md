# 만능매크로

## 프로젝트 소개
이 프로그램은 마비노기 매크로 프로그램으로 유명한 스크립트 메이커를 모방하여 개발되었습니다. <br>
기존 스크립트 메이커에 없었지만 있었으면 더욱 유용했을 기능들을 추가하여, 보다 편리하게 사용할 수 있도록 만들었습니다.

이 프로그램에 사용된 Third-Party Program 은 다음과 같습니다.
- OpenCV ( https://opencv.org ) => 정적 라이브러리, 불필요한 코드는 주석처리해서 EXE 파일 용량 최적화
- Scintilla ( https://www.scintilla.org ) => char 형식으로 짜여진 코드를 wchar_t로 전부 변환, 불필요한 코드는 주석처리해서 EXE 파일 용량 최적화

이 프로그램에 사용된 외부 코드는 다음과 같습니다.
- Human-like cursor movement ( https://github.com/RandomGuy1520/FlorrHelper ) => 파이썬 코드를 LLM 을 이용하여 C++ 코드로 변환

## 주요 특징
- 이미지 서치 ( SIMD + 멀티스레딩을 이용해 보다 빠른 이미지 서치 가능 )
- 템플릿 서치 ( OpenCV )
- 픽셀 서치 ( SIMD 를 이용해 보다 빠른 픽셀 서치 가능 )
- 멀티 이미지 서치 ( 여러개의 이미지를 동시에 서치 가능 )
- 커서 서치 
- 가상 마우스, 가상 키보드 기능
- 아두이노 키보드, 마우스 연동 기능 ( 시리얼 통신 )
- 간단한 이미지 캡처 후 편집 기능
- 매크로 추적 기능
- 마우스, 키보드 녹화 기능

## 컴파일 및 실행 방법
해당 프로그램은 소스코드를 공개하지 않습니다.

## 설명서
[마우스](introduce_mouse.md) | [키보드](introduce_keyboard.md) | [이미지](introduce_image.md) | [연산](introduce_operation.md) | [디버깅](introduce_debug.md)

## 작동 화면 ( 클릭하면 빛번짐 사라집니다 )
### 1to50 ( https://zzzscore.com/1to50 )
![Animation1](https://github.com/user-attachments/assets/bf4f812e-3868-477d-acb1-cceb7cc0b038)
### ApmTest ( https://www.arealme.com/apm-actions-per-minute-test/en )
![apmtest](https://github.com/user-attachments/assets/2bccd767-d590-4aa8-9464-2b62b0eb2ca0)
### Checkboxrace ( https://checkboxrace.com )
![checkboxrace](https://github.com/user-attachments/assets/c26070fd-5b87-4f1a-9cba-e9bf4100a600)
### Draw A Perfect Circle ( https://www.arealme.com/draw-a-circle/en )
![draw-a-circle](https://github.com/user-attachments/assets/aa1641c7-f64b-4dc6-a3f6-6f222e880cb0)
### Draw a Perfect Circle ⭕️💯 ( https://neal.fun/perfect-circle )
![perfect-circle](https://github.com/user-attachments/assets/8e0fd9e8-3c77-429e-984d-75c04bdeb29a)
### Mouse Test ( https://www.arealme.com/mouse-test/en )
![mouse-test](https://github.com/user-attachments/assets/2b4197d7-2e74-418a-aa3f-db6f870e745b)
### 두더지 잡기 ( https://www.gamen.com/game10 )
![mole](https://github.com/user-attachments/assets/8a3e2013-b129-4954-a6c1-3c2a80410d57)
![mole (1)](https://github.com/user-attachments/assets/f6165d9d-3246-49e1-b248-8e33e976bd09)
### Aim Test ( https://www.arealme.com/aim-test/en )
![aimtest](https://github.com/user-attachments/assets/89dafe9f-f5d6-4310-9258-7ce835fdfc47)
### 드래그 앤 드롭
![draganddrop](https://github.com/user-attachments/assets/4fb88702-02c0-4f6f-8483-2b15d2fae787)
### 점 찍기
※ 화상키보드는 사용중인 키보드가 텐키리스라서 실행한 것입니다.
![drawdot](https://github.com/user-attachments/assets/7a6297a6-e200-43f1-b4e5-ddd11f21f164)
### 시계 그리기
![analogclock](https://github.com/user-attachments/assets/43dc64c1-04b5-4741-a9b8-ab8039bf0026)
### 따라 그리기
![Animation7](https://github.com/user-attachments/assets/9eefdc09-178c-4fe7-a02c-4f2016e9eab9)



