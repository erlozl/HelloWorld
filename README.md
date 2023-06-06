# Git 명령어

## Git 로컬 컴퓨터에 사용자 등록하기

- git config --global user.name "rlozl"
- git config --global user.email "erlozl.0121@gmail.com"

## git 시작하기

- git init (ex 어느 해변에 숙소안에 있을 때 창문을 여는 것)
- get add . (ex 사진으로 치면 찍어놓는 것)
- git commit -m "최초 커밋" (영구적으로 보관하다 , ex 사진첩에 보관하는 것, 형상관리)

## github 업로드하기

- git remote add origin 주소
- git push origin master

## 다시 업로드하는 법

- 소스 코드 변경
- git add .
- git commit -m "변경 내용 적고"
- git push origin master

## 잘 안될 때 해결법

- git remote -v (remote 확인하는 법)
- git remote rm origin (주소가 이상할 때)
- git remote add origin 주소 (재연결)

## 깃헙 소스코드 다운로드 하는 법

-git clone 주소
