# VM_Inatall_error

출처: https://elsainmac.tistory.com/545

* Mac에서 VirtualBox kext 권한 오류 해결방법

1. 인스톨 실패시 인스톨 창을 닫고 재부팅.
2. Command+R로 복구모드로 부팅.
3. 터미널 실행하여 Command를 실행 "spctl kext-consent add VB5E2TV963"
4. Mac 재부팅하면 정상적으로 사용 가능.
