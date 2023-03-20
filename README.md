# day1 - github 구성 


### wsl란?
- WSL란 Windows Subsystem for Linux의 약자로, 윈도우 10에서 리눅스 환경을 구축하기 위한 가상화 기술입니다. 
- WSL을 사용하면 Windows 운영체제에서 리눅스 명령어를 실행할 수 있으며, 리눅스 응용 프로그램을 설치하고 실행할 수 있습니다. 

### wsl를 이용한 linux 환경설정 방법

1. window가 최신 업데이트 상태인지 확인합니다.

2. 제어판 - 프로그램 및 기능 - windows 기능 켜기/끄기로 들어가서 아래의 항목을 개별적으로 설치합니다.
- Linux용 Window 하위 시스템
- Windows 하이퍼 바이저 플랫폼
- 가상 머신 플랫폼

3. 혹은 PowerShell을 실행, wsl -l -o로 설치할 수 있는 linux 배포판을 확인합니다.
- 설치할 수 있는 linux 배포판들의 정보가 표시됩니다.

 ![우분타1](https://user-images.githubusercontent.com/122597068/226286548-d057b238-7bf4-4ecd-a42b-657438019f6c.png)
 
4. wsl -install로 기본적인 리눅스 배포판인 우분투를 설치합니다.
- 뒤에 -d 옵션을 변경해서 다른 버전도 설치가 가능합니다.

![우분타2](https://user-images.githubusercontent.com/122597068/226288295-8bc70790-b206-470e-bacc-8da7071fad8a.png)

5. 재부팅후, 우분투를 실행합니다.

6. username/password/retype password를 설정합니다.

7. wsl2를 이용한 linux가 설치됩니다.
