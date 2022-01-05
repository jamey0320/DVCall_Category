# DVCall_Category
#### DeveloveCall 프로젝트에서 제가 맡았던 카테고리 추출 모델링 부분에 대한 저장소입니다.

```
📁 model // 학습한 모델 가중치 h5파일로 저장. tokenize 한거 pickle파일로 저장.

📄 cat_process.ipynb // 카테고리 추출 모델링 전체 파트
                        -> 요약 모델, 인코더, 디코더 모델을 h5형태로 저장, tokenizer를 pickle 파일로 저장

📄 dlmodel.py // 들어온 통화 데이터를 전처리 후 인코딩 - 패딩 - 학습된 모델 거쳐 카테고리 예측 결과 리턴

📄 flaskcode.py // 서버로부터 tts된 통화 데이터를 받아서 dlmodel의 main함수에 전달, 결과를 리턴
```
