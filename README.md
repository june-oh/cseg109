# LAB for Audio Recognition and Audio Synthesis

> 서강대학교 **CSE5109 / CSEG109 / AIE5109 / AIEG109** — 오디오인식 및 합성변환 (Fall 2023)  
> Teaching Assistant: **Junseok Oh (오준석)**  
> Instructor: **Prof. Ji-Hwan Kim**

---

## 실습 내용

### LAB 1: 기초 오디오 파일 처리
- Python & torchaudio를 이용한 오디오 파일 다루기
- 기초 신호 처리 및 특징 추출 (Mel-spectrogram, MFCC)

### LAB 2: 딥러닝 기초 & 언어 모델
- PyTorch & PyTorch Lightning 기초 (Feed Forward Neural Network)
- XOR 문제 실습
- 간단한 언어 모델 구현 및 학습

### LAB 3: 순환 신경망 (RNN)
- RNN 구조 이해 및 구현
- 시퀀스 데이터 처리 실습

### LAB 4: 합성곱 신경망 (CNN)
- CNN 구조 이해 및 구현
- 오디오 분류 실습

### LAB 5: Sequence-to-Sequence (Seq2Seq)
- Attention 유/무 Seq2Seq 모델
- 음성 인식 기초 이해

### LAB 6: 신경망 음성 합성 (Neural TTS)
- **FastSpeech2** 모델 학습 및 추론
- **VocGAN** vocoder를 이용한 파형 생성

---

## 실습 노트북

| LAB | 주제 | 노트북 |
|-----|------|--------|
| 1 | 오디오 파일 처리 | `lab_1.ipynb` |
| 2 | PyTorch 기초 + LM | `Lab2_XOR.ipynb`, `Lab2_LM_Exercise.ipynb` |
| 3 | RNN | `LAB3_RNN_Exercise.ipynb` |
| 4 | CNN | `LAB4_CNN_Exercise.ipynb` |
| 5 | Seq2Seq | `LAB5_Seq2Seq.ipynb` |
| 6 | FastSpeech2 TTS | `LAB6_Fastspeech2_Train.ipynb`, `LAB6_FastSpeech2_Inferene.ipynb` |

---

## 실습 환경

- Google Colab (GPU 사용 권장)
- Python 3.8+

## 필요 라이브러리

```bash
pip install torch torchaudio numpy matplotlib
```

- `PyTorch` — pytorch/pytorch
- `NeMo` — NVIDIA/NeMo
- `TorchAudio` — pytorch/audio
- `NumPy` — numpy/numpy
- `matplotlib` — matplotlib/matplotlib

---

## 관련 자료

- 2023 Samsung AI Academy ASR Tutorial → [2023_AI_Academy_ASR](https://github.com/june-oh/2023_AI_Academy_ASR)
- 2024 버전 (FastSpeech2 + LM 개선) → [2024_cseg109](https://github.com/june-oh/2024_cseg109)
- 포트폴리오 → [june-oh.github.io/june-oh](https://june-oh.github.io/june-oh/)
