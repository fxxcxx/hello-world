#### 맥북에서 c
~~~
$ g++ -o 파일명 컴파일할파일명.확장자
./ 실행파일명
~~~

#### git commit & push
~~~
cd desktop
cd c++ //폴더로 이동하느 단계
git init // 폴더를 git master로 설정
git remote add origin(=설정하려느 이름) URL(깃헙 URL) //로컬 저장소와 내부 저장소 연결
git add 폴더이름
git commit -m "commit msg"
git push origin +master
~~~

#### git pull
~~~
git pull origin +master
git stash // pull 충돌시, 로컬과 원격의 내용 달라지면 충돌 일어남
~~~

#### 그 외
~~~
git status //git 상태보기

git remote -v //로컬-내부 연결 상태 확인

git remote  rm origin //origin 삭제, 추가느 위와 같이 하면 됨
git rm -r binary //binary는 폴더 이름
git commit -m "remove"
git push origin +master //원격, 로컬 폴더 삭제 3단계
~~~

