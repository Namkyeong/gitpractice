깃허브 공부

팀개발을 위한 Git Github 시작하기

<로컬 저장소 만들기>
해당 경로에 들어가서 'git bash here'
git init
git config --global user.email "namkyeong96@naver.com"
git config --global user.name "Namkyeong"

커밋에 추가할 파일 선택
git add README.txt
git commit -m "사이트 설명 추가" ==> [-m]은 message의 약자

<원격 저장소 만들기>
git remote add origin https://github.com/Namkyeong/gitpractice.git ==> 로컬저장소에 원격저장소 주소를 알려줌
git push origin master

<원격 저장소 커밋 내려받기>
