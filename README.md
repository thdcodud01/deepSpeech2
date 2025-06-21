🔊 Deep Speech 2: End-to-End 음성 인식 시스템
End-to-End 음성 인식 시스템을 구축하는 프로젝트입니다.
PyTorch와 CTC Loss를 활용하여 2D CNN → Residual CNN → Bidirectional GRU → CTC Loss 아키텍처를 기반으로 음성 데이터를 처리하고 음성을 텍스트로 변환하는 모델을 학습합니다.

🔗 링크
📄 Deep Speech 2 발표자료 (PDF)

📁 GitHub Repository (Code Only, with README)

📄 Google Drive (Full Colab notebook with results)

📦 Data Files
🔗 deepSpeech2_infer_model.ipynb 다운로드

Inference를 위한 Colab 노트북입니다. 모델을 불러와서 예측을 진행할 수 있습니다.

🔗 model_epoch_10.pth 다운로드

학습된 DeepSpeech2 모델 파일입니다. 모델을 Colab에서 불러와 예측할 수 있습니다.

🚀 실행 방법 (How to Run)
본 프로젝트는 Google Drive와 연동된 데이터가 필요합니다.

1️⃣ Google Drive 준비
deepSpeech2_infer_model.ipynb → Google Drive에 업로드 후 /content/drive/MyDrive/deepSpeech2/ 경로에 업로드

model_epoch_10.pth → Google Drive에 업로드 후 /content/drive/MyDrive/deepSpeech2/ 경로에 업로드

2️⃣ Colab 노트북 열기
Run in Colab (Open Notebook)

3️⃣ 실행
Colab 노트북 첫 번째 Cell에서 Google Drive mount 코드 실행

이후 순서대로 코드 셀 실행

📚 기술 스택
Python

PyTorch

CTC Loss

Bidirectional RNN

음성 인식 (Speech Recognition)

