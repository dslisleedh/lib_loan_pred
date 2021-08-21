# lib_loan_pred

수집 및 전처리된 파일과 제작된 모델이 너무 커서 깃허브상에 안올라감. 

모델 및 사용파일 : https://drive.google.com/drive/folders/18YzfzxA_J2TvyMyxRAllZWfdmptR_AYr?usp=sharing

해당 서비스 주소 : http://dslisleedh.duckdns.org:5000/index.html
  - 1. HTTPS로 접속시 오류발생
  - 2. 뒤에 index.html 빼먹으면 안됨. 

더 나은 예측성능을 위해 추가작업중
  - 1. GP 알고리즘이아닌 TPE알고리즘을 사용하는 Hyperopt로 최적화
  - 2. 워드임베딩을 그냥넣는것이 아니라 UMAP을 이용, 3차원으로 축소한뒤 사용.

