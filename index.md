---
layout: page
title: 자연어 처리 (NLP)
---

- [자연어처리 스터디](https://etherpad.net/p/nlp-study)
    - 장소 및 일시: 역삼역 인근 / 매주 혹은 격주 
    - [R/파이썬 분석환경 준비](nlp-toolchain.html)
    - [텐서플로우(tensorflow) 설치](nlp-tensorflow-install.html)
- [NLP 도구](nlp-tools.html)
- [다양한 텍스트 데이터 가져오기](regex-import-text.html)
    - [전자우편 텍스트 &rarr; CSV](nlp-ingest-text.html)
- [정규표현식](regex-index.html)
    - [정규표현식 소개](regex-intro.html)
    - [간단한 패턴](regex-simple-pattern.html)
    - [연산자](regex-operators.html)
    - [작동원리](regex-under-the-hood.html)
    - [추가 패턴](regex-more-pattern.html)
    - [참고문헌 사례](regex-last-wrinkle.html)
    - [요약](regex-wrapup.html)
    - [`regex` 나래를 펴라!!!](regex-ai-nlp.html)
    - [파이썬3 정규표현식](regex-python3.html)    
- 탐색적 데이터 분석(EDA)
    - [파이썬 자연어 처리 기초](nlp-python-basic.html)
    - [형태소 분석과 품사 태깅](nlp-pos-tagging.html)
    - [정보추출 - 개체명 인식(NER)](nlp-ner-python.html)
    - [텍스트 NLP 기술통계](nlp-twitter-describe.html)
- 모형
    - [기계학습 모형 배포: `flask` + `pickle`](nlp-ml-deployment.html) 
    - [파이썬 파이프라인(pipeline)](nlp-python-pipeline.html) 
    - [트위터 감성 예측](nlp-twitter-ml.html)
        - [`spaCy` 품사 태깅](nlp-twitter-ml-pos.html)
        - [BoW 예측모형](nlp-twitter-ml-bow.html)
    - [워드2벡(word2vec)](nlp-word2vec-python.html)
    - **자연어 처리 스터디 @삼정 KPMG**
        - [문서분류 - 헬로월드](nlp-classification.html)
- 제품과 서비스
    - [챗봇(chatbot)](nlp-chatbot.html)
    - [특허(patent)](nlp-patent.html)


`jupyter nbconvert --execute --to html nlp-.ipynb --ExecutePreprocessor.enabled=True --ExecutePreprocessor.timeout=300 --template toc2`