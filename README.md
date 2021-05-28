# GIT 연결 방법 및 사용법   
(지금 까지 공부한 내용 ..)

## 깃을 통해서 버전 관리를 시작한다고 하면  
+ git init 을 적는다.  
   1. (.gitignore)무시할 파일을 명시한다 적는법  
      + 파일명 적고 /
   1. 초록색으로 올라갈 파일이 색깔이 생기고  u도 뜸
   1. git status 를 누르면 터미널 내에서 빨간색으로 뜸 
+ 버전을 만들기 위해서 git add .

  1. git status 를 누르면 터미널 색 초록색으로 변환
  1. git commit -m '메세지' (버전을 생성)
  1. 버전이 잘 생성되었는지 확인을 위해서 git log

+ Git 헙에서 저장소 생성 하기  
  1.  주소 복사

+ git remote add origin 주소 복사 
  1. 원격의 저장소와 연결!!
  1. git push origin master 

+ 이후 저장소 확인 

# 만약 저장소 연결을 했고   
 ### 수정된것만을 보내고 싶다면 어떻게 해야할까요?

 1. git add .
 1. 확인 git status 
 1. 버전 생성   git commit -m '메세지'
 1. git log 확인
 1. git push origin master 
 1. 깃 허브 확인!


# 깃허브를 사용하여 푸쉬를 했는데 안될경우!!! 중요 !!

1. git config --global user.email 을 이용하여 확인한다.  
만약 아무것도 뜨지 않는다면 

1. git config --local user.email  메일 주소(깃허브에 등록되어 있는 메일 주소를 입력해야한다!!!!)

1. 다시한번 git config --global user.email 을 하여 자기 주소가 뜬다면  push 를 사용해서 잔디를 꾸밀수 있다!!!


