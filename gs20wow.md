# START

* **깃과 깃허브...왜 해?**

깃 - 분산 버전 관리 프로그램

구글독스 - 버전관리 - 과거이력 확인 가능

​    

* "버전 관리 프로그램"

변경의 이유와 목적을 손쉽게 파악가능한 툴

​    

* **"분산"의 의의**

시간적 분산, 내용적 분산

중앙집중직 버전관리 - legacy의 변경점이 사라질 수 있다. (management적 관점에선 좋다) → 깃으로 해결 (클라우드서비스 : 깃헙, 깃랩, 빅버켓 - 깃 기반의 저장소 서비스)

깃헙 : 법인이 가입할 땐 비용이 랩보다 더 많이 들어간다. 

개발자들이 잔디를 심는다 : 1일 1commit(버전을 기록하다)

​    

* **CLI**

Graphic User Interface : 폴더는 폴더답게 나타내는 것(그래픽)

개발자는 CLI에 익숙해져야 한다. → 명령어를 통해 사용자와 컴퓨터가 상호작용하는 방식

깃과 리눅스 다 한 사람이 개발

리눅스명령어와 친해질 필요가 있다. 

​    

touch : 파일을 생성하는 명령어

Mkdir : make directory 새 폴더를 생성하는 명령어

Ls : 현재 작업중인 디텍토리의 폴더, 파일을 보여주는 명령어

cd : 속한 파일을 변경

start . open :  파일을 여는 명령어(맥에선 open)

rm : 파일을 삭제하는 명령어

​    

ls –a 

./ : 현재 위치한 폴더

../ : 상위 위치한 폴더

​    

* **절대경로 vs 상대경로 (웹 – html -> css)**

절대경로 : 루트 디렉토리부터 목적 지점까지 거치는 모든 경로를 전부 작성

상대경로 : 현재 작업하고 있는 디텍토리를 기준으로 계산된 상대적 위치를 작성한 것.

​    

​    

* **Markdown(마크다운)** 

텍스트기반의 가벼운 마크업언어, 문서의 구조와 내용을 쉽고 빠르게 적고자 탄생

(API – 정의서, 설명, 디자인 /// 프론트엔드?)

우리가 쓴 코드를 문서에서도 코드처럼 보일 수 있도록 하는 툴

​    

* **깃허브 문서의 시작과 끝**

  readme.md파일 (repository를 통해 설명글을 작성할 수 있다)을 통해 오픈소스의 공식 문서 작성 -> 개인 프로젝트의 소개문서작성 -> 매일 학습한 내용 정리 -> 마크다운을 이용한 블로그 운영  문장에 각각의 속성을 부여해서 문서가 구조화됨 readme.md파일만 넣는다면 자동으로 repository 하단에 설명글이 생김 -> 1일 1commit 만들때도 readme.md(모두 대문자로 기입)를 만들어 사용 

​    

Typora : 실시간 마크다운 변환 제공 / 이미지 또는 표 삽입 시 매우 편한 ui적용

vs코드 등의 프로그램도 마크다운을 지원하지만 전용 프로그램을 사용하면 더 편하게 사용이 가능하다. 

​    

* **헤딩(Heading) -> 타이포라를 이용한 여러 가지 표현방식** 

\#의 개수에 따라 제목의 수준을 구별

문서구조의 기본 / 글자 크기를 키우기 위해 사용하면 안된다.

여러 가지 표현이 가능하다. 코드블럭표현, 링크, 이미지, 텍스트강조 등등

​    

repository : 저장소

​    

**깃 기본기** 

working directory  : 내가 작업하고 있는 실제 디렉토리

staging area : 커밋으로 남기고 싶은,  특정 버전으로 관리하고 싶은 파일이 있는 곳

(git add . or 파일명 : 파일 안에 있는 모든 파일을 git으로 관리하겠다)

git commit –m(massage) ‘123(ex)’ : staged된 파일을 버전으로써 남긴다

git log : 123 출력

repository : 커밋들이 저장되는 곳

****

/// git init -> 최상위 폴더에서 사용하면 안된다  (로컬 저장소로 만들겠다)

​    

ctrl + “~” VS code 

자격증명 

​    

git config —global user.email

git config —global user.name

​    

수정사항을 commit가 기록하고 있다. 

실습 : commit 만들기 

명령어에 익숙해지기 

​    

git log

git diff 

​    

repository에는 로컬과 원결(remote)가 있다. 

​    

깃헙 repository 생성하기 

cir 마크다운으로 만드는게 시간절약에 도움이 될 것 



git remote odd origin 별명

git push -u 별명 master(local branch)