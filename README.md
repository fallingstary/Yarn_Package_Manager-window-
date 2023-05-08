<h1><img src="https://em-content.zobj.net/thumbs/160/microsoft/319/star_2b50.png" height="30px"/> yarn package manager for window</h1>

![yarn](https://img.shields.io/badge/Yarn-cbcbcc?style=for-the-badge&logo=Yarn&logoColor=2196f3)

<h3> Now, explain about yarn </h3>

* yarn 패키지 매니저
1. 윈도우 로컬 전역에 설치되기 때문에 프로젝트를 시작할 때 패키지를 한 번만 다운로드하면 된다.
2. 인터넷 속도가 느리거나 불안정한 환경에서도 프로젝트를 원활하게 진행할 수 있다는 장점이 있다.
3. 자체적으로 패키지를 병렬로 설치할 수 있어 설치 시간을 단축시킬 수 있다.

* yarn 설치 및 세팅, 사용법
1. nodejs 설치 (https://nodejs.org/ko)
2. cmd 활성화
3. node -v로 node 설치 여부(버전 확인)
4. cmd에서 다음 명령어로 yarn 전역에 설치 : $ npm install -g yarn
5. yarn --version으로 설치 여부(버전 확인)
6. yarn을 사용할 폴더 생성 후 vscode 활성화
7. vscode에서 터미널 활성화한 후 다음 명령어로 해당 폴더에 package.json파일 생성 : $ yarn init
-> 전부 enter
8. 다음 명령어로 yarn.lock 파일과 모듈 설치 : $ yarn install
-> 만약에 package.json 파일을 가지고 있더라면, package.json안에 있던 패키지들이 자동으로 설치
9. 끝

* yarn 명령어로 pakage.json 파일 사용법
1. yarn add 패키지명 : dependencies(개발 패키지) 추가(설치)
2. yarn global add 패키지명 : 다른 로컬에 있는 프로젝트에도 dependencies(개발 패키지) 추가(설치)
3. yarn remove : dependencies(개발 패키지) 삭제
4. yarn upgrade : dependencies(개발 패키지) 업데이트
