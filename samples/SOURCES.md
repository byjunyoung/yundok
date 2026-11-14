# 도서관 책 출처

모두 저작권 보호 기간이 끝난 작품이다. 목록과 분류는 `index.json`, 받는 방법은 `scripts/library/`에 있다.

- 영어 98권: Project Gutenberg (https://www.gutenberg.org). 그림 없는 ePub을 받았고, 파일 안의 Project Gutenberg 라이선스 문서를 그대로 두었다.
  - 처음 6권: The Prince 1232, Meditations 2680, Walden 205, The Republic 1497, Frankenstein 84, Pride and Prejudice 1342
  - 더한 92권의 번호는 `scripts/library/gutenberg.py`에 있다. 받은 뒤 파일 안의 제목을 기대한 책과 대조했다.
- 한국어 47편: 한국어 위키문헌 (https://ko.wikisource.org) 의 ePub 내보내기(ws-export). 파일 안의 "정보" 쪽에 출처와 기여자 표시가 있다.
  - 용량을 줄이려고 파일에 들어 있던 글꼴만 뺐다. 본문과 출처 표시는 그대로다.
  - 더한 40편의 문서 이름은 `scripts/library/wikisource.py`에 있다. 저자가 세상을 떠난 해를 보고 골랐다(가장 늦은 해: 계용묵 1961).
  - 받았지만 넣지 않은 것: 영랑시집·육사시집(본문이 거의 비어 있음), 인간문제·젊은 그들·백범일지·유정·구운몽(책 전체가 한 챕터로 묶여 멤버가 읽기에 너무 김)

받은 날: 2026-11-11(처음 13권), 2026-11-12(나머지)
