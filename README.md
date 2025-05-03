# AlmightyMacro

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

## 작동 화면 ( 클릭하면 빛번짐 사라집니다 )
### 1to50 ( https://zzzscore.com/1to50 )
![1to50](https://github.com/user-attachments/assets/ee0657a9-0fad-4cb5-828a-c4e998962f9d)
### ApmTest ( https://www.arealme.com/apm-actions-per-minute-test/en )
![apmtest](https://github.com/user-attachments/assets/2bccd767-d590-4aa8-9464-2b62b0eb2ca0)

### AimTest ( https://www.arealme.com/aim-test/en )
