# 단어 팟캐스트 스튜디오 (Voca Podcast Studio)

이미지 업로드만으로 영어 단어장·테스트지 PDF와 엄마·아이 퀴즈 팟캐스트 대본 및 음성을 한 번에 만드는 모바일·PC 겸용 웹 앱입니다.

## 주요 기능
1. **단어 입력**: 단어장 사진 업로드 시 Gemini가 단어·품사·영영 정의·한국어 뜻을 모든 다의어 포함해 추출
2. **PDF 생성**: 2단 테스트지(랜덤 순서), Retest(순서 다시 섞기), 학습용 단어장 A4 PDF 저장
3. **퀴즈 대본**: 7가지 고정 규칙([Scene], [Sample Context], [Script], 스토리텔링, 평문 등)을 반영한 대본 생성
4. **음성 제작**: Google AI Studio(Gemini Multi-Speaker TTS) 기반 WAV/MP3 음성 생성 및 다운로드

## 사용 방법 (GitHub Pages)
1. 저장소의 `Settings` → `Pages` → `Branch`를 `main` / `/ (root)`로 설정해 배포합니다.
2. 생성된 `https://<아이디>.github.io/<저장소이름>/` 주소를 PC나 스마트폰 브라우저로 엽니다.
3. 우측 상단 **API 키 입력**에 본인의 Google AI Studio API 키를 입력합니다. (키는 현재 기기 브라우저에만 저장됩니다.)
