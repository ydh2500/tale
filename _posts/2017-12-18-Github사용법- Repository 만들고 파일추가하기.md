---
layout: post
title:  "Github 사용법 - Repository를 만들고 파일을 추가하기"
author: "윤두현"
---

**상황 및 배경**<br/>
Github를 설치 한 후 Repository를 만들었는데, 이제 어떻게 활용해야 할지 모르는 상황. 

**Clone을 활용하여 내 컴퓨터와 연동시키자**<br/>
먼저 Git bash를 이용하여 원하는 폴더로 들어가자.<br/>
나는 G드라이브에 있는 Optics_github 폴더를 이용하고 싶다.<br/>
<br/>
cd g:<br/>
cd Optics_github<br/>
를 입력하면 원하는 폴더로 들어갈 수 있다. <br/>
<br/>
여기서, 이미 github에 생성되어 있는 Repository를 끌어 들여오자.<br/>
$ git clone "https:// 주소"   를 치면 복제를 한다.<br/>
<img src="1.jpg"><br/>
<br/>
복제 후, 원하는 파일을 본 폴더안에 집어넣는다. <br/>
<img src="2.jpg"><br/>
<br/>
$git status를 입력하여 본다.<br/>
<img src="3.jpg"><br/>
이런 식으로 붉은 글자로 표시된 것이 변경된 사항이다. <br/>
<br/>
$git add *<br/>
$git commit -m "수정 및 업데이트 참고사항을 입력"<br/>
$git push<br/>
이렇게 세 명령어를 연달아 넣어주면 업데이트가 완료가 된다. <br/>
<img src="4.jpg"><br/>

