# oh-my-notebooks

블로그 글에 딸린 **바로 실행되는 노트북** 모음입니다. 글에서 다룬 걸 직접 돌려볼 수 있게 만들었습니다.

각 노트북은 Colab 배지를 누르면 설치 없이 열립니다. GPU 런타임을 켜면 더 빠릅니다.

## 노트북

| 노트북 | 내용 | 열기 |
|---|---|---|
| [한국어 STT 실측 비교](notebooks/korean_stt_comparison.ipynb) | Whisper · faster-whisper · WhisperX · CrisperWhisper 2.0 을 같은 음성으로 돌려 정확도·속도·라이선스를 비교합니다. 한국어는 직접 올린 음성으로 잽니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/korean_stt_comparison.ipynb) |

## 쓰는 법

1. 표에서 **Open in Colab** 배지를 누릅니다.
2. Colab 메뉴에서 `런타임 → 런타임 유형 변경 → GPU` 를 선택합니다.
3. 위에서부터 셀을 순서대로 실행합니다.

노트북은 필요한 샘플 데이터를 실행 시점에 직접 내려받습니다. 저장소에는 데이터가 들어 있지 않습니다.

## 데이터와 라이선스

- 샘플 데이터는 재배포가 허용된 것(CC0·CC BY 등)만 씁니다. 출처와 라이선스는 해당 셀에 적어 두었습니다.
- 모델 가중치의 라이선스는 노트북마다 다릅니다. **상업적 이용 전에 각 모델의 라이선스를 확인하세요** — 연구용으로만 허용된 것이 섞여 있습니다.
- 이 저장소의 코드는 MIT 라이선스입니다.

## 문의

노트북이 안 돌아가거나 결과가 다르게 나오면 이슈로 알려주세요. 실행 환경(Colab / 로컬, GPU 종류)을 함께 적어주시면 도움이 됩니다.
