# 삼성 DS-KAIST AI Expert 프로그램 
## Seq2Seq

실습 일시: 2019년 10월 11일 (금), 13:30 - 17:30

담당 조교: 박천복 (cb_park@korea.ac.kr)
	  태윤원 (tyj204@korea.ac.kr)

### Table of Contents

1. Preprocessing
2. Seq2Seq
3. LoungDecoder



### Restriction

- Seq2Seq_Assignment.ipynb 파일에 제공된 코드를 **수정 하지 않고**, 빈공간에 코드를 구현하시면 됩니다.
  - 구현이 필요한 부분은 (#기존 코드를 수정하지 않고 코드를 구현해 주세요!)로 주석 처리 하였습니다.
- 반드시 **Encoder에 Bidirectional을** 사용하여야 하며, Encoder, Decoder의 **layer수는 2개이상이여야** 합니다.

### Objective

- 코드 구현을 마친후 config에 제공된 hyperparameter를 조정하여 모델의 accuracy가 **99%** 이상 도달 하셔야 합니다.
  - End of evaluation : loss 0.030, **acc 99.9**, edits 0.001

### Submission
- 파일제출은 **1. (./config.pkl) 2. (./trained_model) 3. (./Seq2Seq_Assignment)** 해주시면 됩니다
- 모델제출란에서 저장된 **1. (./config.pkl) 2. (./trained_model)** 파일을 기반으로 체점을 하겠습니다.
