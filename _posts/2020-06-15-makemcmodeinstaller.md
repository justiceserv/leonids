---
layout: post
title:  "마인크래프트 모드 자동 설치기 만드는 방법"
excerpt: "HM NIS Edit과 NSIS를 이용한 자동 설치기 만드는 방법입니다."
date:   2020-06-15 9:47:00
categories: [Helping Documents]
comments: true
---
# (NSIS) 마인크래프트 모드 자동 설치기 만드는 법

요번에 마인크래프트 모드 자동 설치기를 만들다 보면서 (사실 처음에 C++로 뻘짓을 하긴 했지만)</br>
자동 설치기는 NSIS로 만드는게 최고인것 같아서 어떻게 만드는지 올려봅니다.

## 개요

1. 개발(?)에 필요한 프로그램들 설치
2. 개발
3. ???: Profit!

## 1. 프로그램들 설치

NSIS(Nullsoft Scriptable Install System) 을 이용해서 자동 설치기를 만들려면 역시 컴퓨터에 NSIS가 있어야합니다. </br>
NSIS 설치 링크: [https://sourceforge.net/projects/nsis/](https://sourceforge.net/projects/nsis/)</br>
HM NIS Edit 설치링크: [[https://sourceforge.net/projects/hmne/](https://sourceforge.net/projects/hmne/)</br>
여기까지는 그냥 생각없이 동의-동의 누르면 됩니다.
#### 잠깐!

만약 HM NIS Edit을 까는데 무슨 에러가 (ex. 언어를 열수 없습니다 등등) 뜬다면 가뿐히 무시해주세요.

## 2. 개발(?)

개발이라 하기에도 뭐할 정도로 쉽습니다.
<p align="center">
<img align ="center" src = "https://i.ibb.co/7rZTRpK/1.png">
</p>

HM NIS Edit을 실행한 후, 노란색 하이라이트 되어있는 지팡이를 클릭합니다.

<p align="center">
<img align ="center" src = "https://i.ibb.co/cQV9vnX/2.png">
</p>

다음 클릭

<p align="center">
<img align ="center" src = "https://i.ibb.co/nnV4MZS/3.png">
</p>

프로그램 이름 등, 자신이 원하는 것을 입력하세요. (여기선 뭘 하셔도 상관 없음)

<p align="center">
<img align ="center" src = "https://i.ibb.co/LNfKZGn/4.png">
</p>

GUI는 왠만하면 Classic으로 선택해주시고, 압축은 LZMA로 선택해주세요. (Modern은 에러가 뜰 가능성 있음)

<p align="center">
<img align ="center" src = "https://i.ibb.co/1fxVhxc/5.png">
</p>

프로그램 기본 디렉터리는 그대로 냅두시고, 라이선스 파일은 원하시면 만드셔도 됩니다만,
메모장으로 만드실 경우에는 인코딩을 ANSI로 해주셔야합니다. (아니면 한글 깨짐)

<p align="center">
<img align ="center" src = "https://i.ibb.co/rH55VgH/6.png">
</p>

원래 파일에 example이 두개 있을텐데 전부 지워주시고, 원하시는 프로그램들로 선택해주세요.
단, 설치 프로그램이 들어갈 파일과 같은 곳에 넣어주세요.

<p align="center">
<img align ="center" src = "https://i.ibb.co/44vNBGx/7.png">
</p>

#### 여기서 중요 : 설치 다이렉터리를 %APPDATA%\.minecraft\mods 로 설정해주셔야합니다.

<p align="center">
<img align ="center" src = "https://i.ibb.co/j3ZKg5h/8.png">
</p>

체크박스 3개 전부 다 해제해줍니다.

<p align="center">
<img align ="center" src = "https://i.ibb.co/ftvkKJp/9.png">
</p>

언인스톨러 사용 해제해줍니다.

<p align="center">
<img align ="center" src = "https://i.ibb.co/Z1Tcyww/10.png">
</p>

완성.

## ???: Profit.

저기서 컴파일 에러가 뜨지 않는다면 성공입니다.  

그리고 인스톨러를 넣을 파일을 하나 만드셔서 거기 안에 모드와 다른 것들을 넣으시는 것을 추천드립니다.

진짜 끝.
