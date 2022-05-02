# test
https://drive.google.com/file/d/1K3nW8Wcpqk1bfYfMblV7nRzHSvg-3ddm/view?usp=sharing


## ------------------------------------------


install\USB Driver Setup\IntelEdisonDriverSetup1.2.1.exe 설치
install\USB Driver Setup\CDM21226_Setup\CDM21226_Setup.exe 설치
장비 연결 후 장치관리자에서 USB Serial Port 확인
Putty 설치
Putty에서 Serial로 접속(장치관리자에서 포트번호 확인) 속도 : 115200 
접속 후 enter 누르면 접속 완료
root 계정으로 접속 했을 때 비밀번호가 걸려있으면 초기화 진행해야함
edison 폴더 내용을 전부 지우고 source 폴더의 edison-image-ww18-15 폴더의 파일을 붙여넣기
Putty가 연결되어있는 상태에서 장비의 전원버튼을 껐다 킨 뒤에 putty에서 esc를 몇번 누르면
boot 모드로 들어온다. 
boot 모드로 들어오면 run do_ota 명령어 입력
초기화 진행 후 root로 다시 로그인

아두이노 설치
장비를 연결한 뒤 아두이노를 킨다
포트를 serial 포트 번호로 연결
보드매니저에 edison 입력 하여 설치
intel>edison으로 보드 변경 
https://iotmaker.kr/iotbook-aim-install 로 접속
스케치>라이브러리 포함하기>라이브러리 관리
상단에 pubsubclient 입력 하여 pubsubclient 2.7 설치
상단에 ArduinoJson 입력하여 ArduinoJson 설치
상단에 AESLib 입력하여 AESLib 설치
사이트에서 AIM 다운받은 뒤 라이브러리 포함하기>.zip 라이브러리 추가 를 눌러서 
다운받은 AIM 라이브러리 추가 

파일>환경설정에서 IDE 환경 설정
추천 : font 18, 컴파일 및 업로드 출력 보이기 체크, 줄 번호 표시 체크, 외부 에디터 사용 체크해제
스케치북 위치가 Arduino인지 확인

 
