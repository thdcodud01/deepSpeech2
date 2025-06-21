# 🔊 **Deep Speech 2: End-to-End 음성 인식 시스템**

**End-to-End 음성 인식 시스템**을 구축하는 프로젝트입니다.  
**PyTorch**와 **CTC Loss**를 활용하여 **2D CNN → Residual CNN → Bidirectional GRU → CTC Loss** 아키텍처를 기반으로 음성 데이터를 처리하고 음성을 텍스트로 변환하는 모델을 학습합니다.

---

## 🚀 **프로젝트 목표**
- 음성 데이터를 **Mel-Spectrogram**으로 변환하여 모델을 학습합니다.
- **2D CNN**, **Residual CNN**, **Bidirectional GRU** 네트워크를 사용하여 **CTC Loss**를 기반으로 음성 인식 모델을 구축합니다.
- 모델 평가 지표로 **WER (Word Error Rate)**와 **CER (Character Error Rate)**를 사용하여 성능을 측정합니다.

---

## 🔗 **링크**
- 📄 **[Deep Speech 2 발표자료 (PDF)](https://drive.google.com/file/d/1UpiDfCTKK1yR_Tek64eCO_xwmyaJnOce/view?usp=sharing)**  
  발표 자료를 확인할 수 있습니다.

- 📁 **[GitHub Repository (Code only, with README)](https://github.com/thdcodud01/deepSpeech2)**  
  전체 코드와 **README** 파일을 제공하는 **GitHub 리포지토리**입니다.

- 📄 **[Google Drive (Full Colab notebook with results)](https://drive.google.com/file/d/1ntIFpVXYJZldKy-KjCPH3xKpmS_SM8ZQ/view?usp=sharing)**  
  Colab에서 실행할 수 있는 **전체 노트북**을 제공합니다.

---

## 📦 **Data Files**
- 🔗 **[deepSpeech2_infer_model.ipynb 다운로드](https://drive.google.com/file/d/1ntIFpVXYJZldKy-KjCPH3xKpmS_SM8ZQ/view?usp=sharing)**  
  **Inference**를 위한 Colab 노트북입니다. 모델을 불러와서 예측을 진행할 수 있습니다.

- 🔗 **[model_epoch_10.pth 다운로드](https://drive.google.com/file/d/185yeAjLpynS4DXrPZb4vxug5p7FKCskz/view?usp=sharing)**  
  학습된 **DeepSpeech2 모델** 파일입니다. 모델을 Colab에서 불러와 예측을 할 수 있습니다.

---

## 🚀 **실행 방법 (How to Run)**

본 프로젝트는 **deepSpeech2_infer_model.ipynb, model_eopch_10.pth 다운로드**가 필요합니다.

---

### 2️⃣ **Colab 노트북 열기**
- [Run in Colab (Open Notebook)](https://colab.research.google.com/github/thdcodud01/deepSpeech2/blob/main/DeepSpeech2_Inference.ipynb)

---

### 3️⃣ **실행**
1. Colab 노트북 첫 번째 **Cell에서 코드** 실행
2. 이후 **순서대로 코드 셀 실행**

---

## 📚 **기술 스택**
- **Python**
- **PyTorch**
- **CTC Loss**
- **Bidirectional RNN**
- **음성 인식 (Speech Recognition)**

---

## 📝 **참고**
- 본 프로젝트는 **AI융합학과 컴퓨터비전** 프로젝트로 진행되었습니다.

---
