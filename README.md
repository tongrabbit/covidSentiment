# Covid19 Tweet Sentiment Analysis
딥러닝 기반 코로나19 관련 트위터 감정분석 성능 비교
 
본 연구에서는 전세계적인 소셜 미디어 '트위터'에서 수집한 데이터를 가지고 코로나19 관련 감정분석을 수행하고자 한다.  트위터가 가지는 구조적 특징을 유지하면서도 불필요한 문자, 기호 등을 제거하기 위한 전처리 방식을 제시하였다. 텍스트를 컴퓨터가 이해할 수 있는 언어로 변환하기 위해서 통계적 기반의 임베딩 기법과 문장 수준의 임베딩 기법을 적용하였다. 자연어 처리 분야에서 대표적으로 사용되는 머신러닝과 딥러닝기법을 사용하여 감정분석을 수행하고 각 성능을 비교분석하였다.

트위터는 소셜미디어 중 마이크로 블로그에 해당한다. 140자의 단문 소통, 다자간의 대화, 실시간성이라는 구조적 특징을 지니고 있다(Hur and Choi, 2012). 트위터 메세지인 '트윗'은 통신언어에서 나타나는 언어적 특징을 가지며, 이는 이모티콘의 사용, 축약어, 불필요한 자음 첨가 등이 있다. 또한 실시간적인 다자 소통을 위해 '멘션'이나 '해시태그'가 다수 포함되어 있다. 
본 연구에서는 코로나19를 키워드로 하여 2020년 3월부터 4월 까지 검색된 44,955개의 트위터 메세지 기반으로 단어들을 추출한 데이터(이하 트위터 데이터)를 사용하였다. 이는 예측모델 및 분석대회 플랫폼의 일종인 ‘캐글(Kaggle)’에 공개된 데이터셋으로부터 수집하였다. 

본 연구에서 사용하는 데이터는 사용자 이름, 해당 트윗이 작성된 지역, 시간, 메세지 원문과 감정구분 컬럼을 포함한 csv 파일이다. 각 이름은 개인정보 보호를 위해 코드화되었고, 감정 구분 컬럼은 해당 데이터셋의 공유자가 수동으로 태깅하여 작성되었다. 


1. machine learning


2. LSTM

3. GRU

4. BERT
