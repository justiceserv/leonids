---
layout: post
title:  "내 가족 지킴이 개발 향후계획"
excerpt: "내 가족 지킴이 향후 개발 계획 및 UI 디자인"
date:   2020-06-13 20:00:00
categories: [Projects]
comments: true
---

# 내 가족 지킴이 현재 개발 현황
궁금하신 분들은 다운로드 링크: https://short.mcx.kr/download
## 현재 클라이언트 개발 현황
개발된 기능들:

- 현재 위치가 안전한가 / 안전하지 않은가
- 진동으로 안전하지 않을시 알리는 기능 & 화면 표시
- 하단 지도에 사용자 위치 표시
## 현재 서버 개발 현황
개발된 기능들:

- 강남 CCTV 공공데이터에서 db 내려받기
- 서버 클라이언트 소켓 통신
## 미래에 개발할 것들
### 서버
- 클라이언트가 신고한 위도 경도 받아서 서울시 또는 정부기관에 전송
### 클라이언트
- 현재 웹 기반인 플레이어를 네이티브 기반으로 변경
- 긴급 신고 기능 생성 (112에 직접)
- 일반 신고 기능 생성 (서버에 위도 경도 및 cctv 대수 전송)

## 현재 UI (개발 중)
### 클라이언트 메인 페이지
<p align="center">
<img align = "center" src="https://i.ibb.co/tMQ2fKv/androidui.png">
</p>

### 서버 메인 페이지
<p align="center">
<img align ="center" src = "https://i.ibb.co/QNFbjsn/ggcctvui.png">
</p>

# 마지막으로
강남구 CCTV mdb 데이터베이스:

https://www.dropbox.com/s/i0qefipnh9f7j4f/CCTV_Location.mdb?dl=0
