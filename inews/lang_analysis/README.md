
#============================================================
# 자료구조 : 테이블 구조
#============================================================

# 뉴스제목본문_ETRI언어분석_원본

1. 뉴스id : 뉴스TBL의 id
2. 뉴스XXsrl_res 뉴스제목/분석에 대한 ETRI-언어분석srl에 의한 응답 JSON-dicli
3. 수집일시 : ETRI_AI_API 호출일시


# 뉴스제목본문_ETRI언어분석

- 뉴스id :
- 뉴스XX_요약 : 뉴스XX_명사li 를 sklearn-cluster 하기 위해 중복제거 후 문자열화.
- 뉴스XX_명사li : 언어분석morp로부터 파싱

#============================================================
# 단축용어 가이드
#============================================================

LangAnalysis 모듈/클래스? 에서 다음과 같이 사용하자.
뉴스제목본문_ETRI언어분석_원본TBL -> RD_TBL
뉴스제목본문_ETRI언어분석TBL -> TBL
분석수집타겟col명 -> 타겟col명