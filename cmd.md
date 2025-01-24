파일 및 디렉터리 관리
dir

디렉터리의 파일 및 폴더 목록을 표시.
예: dir C:\Windows
copy

파일 복사.
예: copy file1.txt C:\backup
xcopy

디렉터리와 하위 디렉터리를 복사.
예: xcopy C:\source C:\destination /E
robocopy

고급 파일 및 디렉터리 복사 도구.
예: robocopy C:\source C:\destination /MIR
move

파일 또는 디렉터리를 이동.
예: move file1.txt D:\
del / rmdir

파일 및 디렉터리를 삭제.
예: del file1.txt / rmdir /S C:\folder
시스템 관리
tasklist

실행 중인 프로세스 목록을 표시.
예: tasklist
taskkill

실행 중인 프로세스를 종료.
예: taskkill /PID 1234
systeminfo

시스템 정보(운영 체제 버전, 메모리 등)를 표시.
예: systeminfo
msconfig

시스템 구성 유틸리티를 실행 (GUI).
예: msconfig
chkdsk

디스크의 파일 시스템 및 오류를 검사/복구.
예: chkdsk C: /F
sfc

시스템 파일 검사 및 복구.
예: sfc /scannow
dism

Windows 이미지 관리 도구. 시스템 복구 및 업데이트.
예: dism /online /cleanup-image /restorehealth
shutdown

시스템 종료, 재부팅, 예약.
예: shutdown /s /t 60 (60초 후 종료)
wmic

Windows Management Instrumentation을 통해 시스템 관리.
예: wmic process list
네트워크 관리
ipconfig

네트워크 구성 확인 및 관리.
예: ipconfig /all
ping

네트워크 연결 상태 확인.
예: ping google.com
tracert

경로 추적을 통해 네트워크 문제 분석.
예: tracert google.com
netstat

네트워크 연결, 포트 상태 확인.
예: netstat -an
nslookup

DNS 정보 확인.
예: nslookup google.com
netsh

네트워크 설정 및 관리 도구.
예: netsh wlan show profiles
ftp

파일 전송 프로토콜 클라이언트.
예: ftp ftp.example.com
arp

ARP(주소 확인 프로토콜) 테이블 확인 및 수정.
예: arp -a
telnet

원격 서버 연결 도구 (기본적으로 비활성화됨).
예: telnet server.example.com
디스크 및 저장소 관리
diskpart

디스크 파티션 관리.
예: diskpart 실행 후 명령어 입력.
format

드라이브 포맷.
예: format D: /FS:NTFS
mountvol

볼륨 마운트 및 해제.
예: mountvol D: /D
fsutil

파일 시스템 관리 도구.
예: fsutil volume query C:
사용자 관리
net user

사용자 계정 생성, 수정, 삭제.
예: net user username password /add
whoami

현재 로그인한 사용자 정보.
예: whoami
runas

특정 사용자 계정으로 프로그램 실행.
예: runas /user:admin cmd
프로그램 실행 및 설정
assoc

파일 확장자와 프로그램 연결 확인 및 수정.
예: assoc .txt
start

프로그램 실행.
예: start notepad
reg

레지스트리 관리.
예: reg query HKEY_LOCAL_MACHINE\Software
msiexec

Windows 설치 관리자 실행.
예: msiexec /i setup.msi
기타 도구
echo

메시지 출력.
예: echo Hello, World!
tree

디렉터리 구조를 트리 형태로 표시.
예: tree C:\
clip

명령 출력 결과를 클립보드로 복사.
예: dir | clip
cls

명령 프롬프트 화면 지우기.
예: cls
timeout

일정 시간 대기.
예: timeout 10 (10초 대기)
