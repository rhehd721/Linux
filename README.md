# Bit_Linux

## Linux 명령어 정리

1. pwd == 지금 내가 어떤 경로에 있는지 확인 (/home/ubuntu/Downloads 이런식)

2. cd == 디렉토리(폴더) 이동

3. ls, ls -a, ls -F, ls -l, dir, vdir == 디렉토리(폴더) 안 내용 보기

4. mkdir, rmdir == 디렉토리(폴더) 생성과 삭제 (make, remove)
	폴더를 지울 땐 rm뒤에 -r을 붙여줘야 한다

5. cat, cat -n, more(화면단위), less, tail(꼬랑지), head(머리부분) == 파일의 내용 보기

6. cp, mv, rm == 파일 복사, 이동, 삭제

7. ln == 하드링크 심벌릭 링크 생성
	하드링크 = 둘중 하나만 수정해도 둘다 수정되지만 지우는건 둘다 지워야 지워진다(ln)
		link file -> filesystem
	심볼릭링크 = 지정한 파일이름에 바로가기 개념?? 참조의 개념(ln -s)
		link file -> link file

8. touch == 빈 파일 생성

9. grep == 파일 내용 검색
	잘못 눌렀을때 ctrl + c 하니깐 탈출됨

10. find, which, whereis == 파일검색

11. vi == 파일 편집하기

12. chsh == 사용자의 셸을 바꾼다 -> 셸이 뭘까? -> 라이브러리 같은걸까??

13. wget == 웹에서 다운로드

14. 명령 > 파일 == 덮어쓰기, 명령 >> 파일 == 추가하기

15. 명령 2> 파일 == 오류저장하기

16. set, env == set은 환경변수와 셸 변수를 env는 환경변수만 출력한다

17. alias 이름 == 줄임말 생성

18. unalias 이름 == 엘리어스 해제

19. file 파일 == 파일의 형식을 알려준다

20. less == vi와 비슷하지만 완전 다른 느낌(큰 파일을 열어볼때?)

21. sudo chown 이름:이름 파일 == 파일의 사용자 변경하기

22. find == 파일 위치 찾기

23. top == cpu정보와 메모리정보 확인

24. w, who == 지금 사용자가 누구인지

25. ps -ef == 지금 실행되고있는 리눅스 내에서 돌아가고 있는것들을 보여준다

26. man 3 명령어 == 개발언어의 도움말?

27. kill -9 process.id == 삭제

28. sudo adduser 이름 == 계정추가
	su -l 이름 == 다른계정으로 전환
	exit == 나가기

29. sudo deluser 이름 == 계정삭제

30. uname -a == 시스템정보 간단 확인

31. hostname == 별명 보기?

32. sudo reboot == 재부팅

33. sudo halt -p == 본체전원까지 종료
