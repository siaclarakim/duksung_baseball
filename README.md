# 인터넷 기초[04] 과제2 - 나만의 인공지능 서비스
# ⚾ 나에게 어울리는 KBO 구단은?

이 웹페이지는 이름, 응원 스타일, 고향을 입력하면  
Google Gemini API를 활용하여 어울리는 **KBO 프로야구 구단**을 추천해주는 서비스입니다.

## 사용 방법

1. 아래 주소에 접속합니다:  
    https://siaclarakim.github.io/duksung_baseball/

2. 입력란에 다음 정보를 입력합니다:
   - 이름
   - 좋아하는 응원 스타일 (예: 신나는, 열정적인 등)
   - 고향

3. **[추천받기]** 버튼을 누르면, AI가 분석한 추천 구단과 응원 문구가 출력됩니다.

## 작동 원리

- 사용자가 입력한 정보를 바탕으로, 백엔드에서 Google Gemini API를 호출합니다.
- 시스템 프롬프트에는 **KBO 전문가 역할**을 부여하여 보다 현실성 있는 추천이 이루어지도록 하였습니다.

## 백엔드 API 주소

- https://assign2-rouge.vercel.app/api/duksungAI

## 사용 기술

- HTML / CSS / JavaScript
- GitHub Pages
- Google Gemini API
- Vercel

