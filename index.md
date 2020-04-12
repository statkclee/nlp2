---
layout: page
title: 자연어 처리 (NLP)
---

<style>
div.blue { background-color:#e6f0ff; border-radius: 5px; padding: 10px;}
</style>
<div class = "blue">

자연어처리 전에 텍스트 마이닝에 대해 궁금하신 분!!!

- [텍스트 마이닝(R)](https://statkclee.github.io/text/)

</div>

아래부터는 자연어처리(NLP)에 대해 다룹니다!!!

- [자연어처리 핵심개념](nlp-concept.html)
    - [R/파이썬 분석환경 준비](nlp-toolchain.html)
    - [파이썬 자연어 처리 기초](nlp-python-basic.html)
    - [텐서플로우(tensorflow) 설치](nlp-tensorflow-install.html) &larr; 추후... 
- [다양한 텍스트 데이터 가져오기](regex-import-text.html)
    - [전자우편 텍스트 &rarr; CSV](nlp-ingest-text.html)
    - [네이버 블로그 (feat. 나성호)](nlp-ingest-naver-blog.html) - 실행 오류!!!
    - [오디오 &rarr; 텍스트](nlp-audio-transcribe.html)
    - [MP3 음악 &rarr; 텍스트](nlp-mp3-transcribe.html)
- [정규표현식 - `R`](regex-index.html) &larr; 이것으로 끝내자!!!
    - [파이썬3 정규표현식](regex-python3.html)
    - 소프트웨어 카펜트리 
        - [정규표현식 소개](regex-intro.html)
        - [간단한 패턴](regex-simple-pattern.html)
        - [연산자](regex-operators.html)
        - [작동원리](regex-under-the-hood.html)
        - [추가 패턴](regex-more-pattern.html)
        - [참고문헌 사례](regex-last-wrinkle.html)
        - [요약](regex-wrapup.html) 
    - [AI 관련 `regex`](regex-ai-nlp.html) &larr; 작업중
- [텍스트 거리](nlp-text-distance.html)
- 탐색적 데이터 분석(EDA)
    - [정보추출 - 개체명 인식(NER)](nlp-ner-python.html)
        - [뉴스 &rarr; 크롤링 &rarr; NER](nlp-ner-python-crawling.html)
    - [텍스트 NLP 기술통계](nlp-twitter-describe.html)
    - [`textblob` - `NLTK` 도우미](nlp-textblob.html)
    - [텍스트 데이터 시각화](nlp-text-viz.html)
    - 한국어
        - [형태소 분석과 품사 태깅](nlp-pos-tagging.html)
- 모형
    - [기계학습 모형 배포: `flask` + `pickle`](nlp-ml-deployment.html) 
    - [파이썬 파이프라인(pipeline)](nlp-python-pipeline.html) 
    - [감성 분석: 빅픽처 + 규칙/어휘사전](nlp-sentiment.html)
        - [트위터 감성 예측: Feature Engineering](nlp-twitter-ml.html)
            - [`spaCy` 품사 태깅](nlp-twitter-ml-pos.html)
        - [BoW/TF-IDF기반 예측모형: M/L](nlp-twitter-ml-bow.html)
    - [워드2벡(word2vec)](nlp-word2vec-python.html)
    - **자연어 처리 스터디 @삼정 KPMG**
        - [문서분류 - 헬로월드](nlp-classification.html)
        - [문서분류 - 뉴스기사 분류 (M/L)](nlp-newsgroup-classification.html)
        - [문서분류 - 뉴스기사 분류 (D/L)](nlp-newsgroup-classification-dl.html)
- 제품과 서비스
    - [챗봇(chatbot)](nlp-chatbot.html)
    - [특허(patent)](nlp-patent.html)
    - [텍스트 삭제(text redaction)](nlp-text-redaction.html)


`jupyter nbconvert --execute --to html --ExecutePreprocessor.enabled=True --ExecutePreprocessor.timeout=300 --template toc2  nlp-` <br>

`jupyter notebook --notebook-dir='d:\docs\sw4ds'`