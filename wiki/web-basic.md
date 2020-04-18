서버: 제공자(Provider) 서비스를 제공하는 컴퓨터, 저장하고 있는 정보(데이터베이스)를 Client 에게 제공

클라이언트: 서비스 요청자

        mkvirtualenv <ENVNAME> 가상환경 생성
        rmvirtualenv <ENVNAME> 가상환경 삭제
        workon 만들어진 가상환경 목록 확인
        workon <ENVNAME> 가상환경 활성화
        deactivate 가상환경 비활성화

  현재 디렉터리 살펴보기 $ pwd
  
  현재 디렉터리에 어떤 파일이나 디렉터리가 있는지 확인할 때 $ ls
  
  현재 위치의 상위 디렉터리로 이동 $ cd ..
  
  하위 디렉터리로 이동 $ cd 이동할 디렉터리 이름
  
  홈 디렉터리 $ cd ~
  
  디렉터리 만들기 $ mkdir 이름
  
  $ vim 뒤에 입력한 파일 이름과 같은 파일이 없다면 그 이름으로 새로운 텍스트 문서를 만들고, 파일이 있다면 그 파일을 엶
  
  키보드에서 i를 눌러 입력 모드로 전환,
  텍스트 입력이 끝난 후 파일을 저장할 때에는 다시 ex모드로 돌아가야 함.
  
  :wq w는 저장, q는 종료
  
  터미널에서 간단히 텍스트 파일의 내용을 확인 $ cat
  
  $ git init
  
  $ git status
  
  커밋을 할 때에는 메세지를 함께 기록해야 함(변경사항 확인용)
  
  $ git commit -m "메시지"
  
  $ git log 버전이 제대로 만들어졌는지 확인(방금 커밋한 버전에 대한 설명)
  
  git commit에 -a 옵션을 붙이면 add와 commit을 한 번에 
  -m 옵션으로 커밋 메세지 
  두 옵션을 합쳐서 -am
  
  $ git reset HEAD^ 마지막에 한 커밋을 취소
  
        $ git reset HEAD 파일이름   <--add 후 commit 전인 파일 되돌리기
        $ git reset HEAD^  <-- 최신 커밋 되돌리기
        $ git reset 커밋해시 <-- 특정 커밋으로 되돌리기
        $ git revert 커밋해시 <-- 커밋 삭제하지 않고 되돌리기

$ git branch 브랜치 만들기

$ git checkout 이름 해당 브랜치로 이동

$ git merge 브랜치 병합하기
