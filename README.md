# oh-my-notebooks

블로그 글에 딸린 **바로 실행되는 노트북** 모음입니다. 글에서 다룬 걸 직접 돌려볼 수 있게 만들었습니다.

각 노트북은 Colab 배지를 누르면 설치 없이 열립니다. GPU 런타임을 켜면 더 빠릅니다.

## 노트북

| 노트북 | 내용 | 열기 |
|---|---|---|
| [판결문 LoRA와 RAG의 조문 인용 비교](notebooks/legal_citation_lora_rag.ipynb) | 같은 판시사항에 기본 모델, LoRA, RAG가 답한 조문을 원 판결의 참조조문과 대조합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/legal_citation_lora_rag.ipynb) |
| [ResNet 깊이와 잔차 연결](notebooks/resnet_depth_curves.ipynb) | CIFAR-10 부분집합에서 20층과 56층의 일반망 및 잔차망 학습 곡선을 비교합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/resnet_depth_curves.ipynb) |
| [한국어 Whisper 실행기 비교](notebooks/korean_asr_runtime_benchmark.ipynb) | 같은 한국어 공개 음성에서 네 구현의 WER, CER와 실시간 배율을 측정합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/korean_asr_runtime_benchmark.ipynb) |
| [판결문 RAG 검색 평가](notebooks/legal_rag_retrieval.ipynb) | 공개 판례 1,000건의 판시사항으로 원 판결을 검색하고 단어와 글자 TF-IDF의 Recall@k를 비교합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/legal_rag_retrieval.ipynb) |
| [PHP 보안 리뷰 검색식](notebooks/php_review_fixtures.ipynb) | PHP 단편 15개에 두 검색식을 적용해 검토 대상 적중과 오탐을 확인합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/php_review_fixtures.ipynb) |
| [Claude Code 권한 판정 집계](notebooks/claude_permission_decisions.ipynb) | 로컬 로그에서 얻은 익명 도수로 Bash 호출별 판정 출처와 비율을 계산합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/claude_permission_decisions.ipynb) |
| [서버 과부하 실측](notebooks/server_overload.ipynb) | 대기열 모형과 로컬 HTTP 응답 시간을 대조하고 재시도와 부하 차단이 처리량과 꼬리 지연에 미치는 영향을 측정합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/server_overload.ipynb) |
| [NIST P-256 시드 재현](notebooks/nist_p256_seed.ipynb) | lrand48로 공개 곡선 시드를 재현하고 표준 계수의 합동식과 후보 초기화 시각을 확인합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/nist_p256_seed.ipynb) |
| [Cloudflare BYOIP 장애 재구성](notebooks/cloudflare_byoip_outage.ipynb) | 합성 프리픽스와 가상 BGP 망에서 대량 철회 차단기가 피해 범위를 어떻게 바꾸고 광고 간격이 수렴에 어떤 영향을 주는지 살펴봅니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/cloudflare_byoip_outage.ipynb) |
| [프롬프트 인젝션 실측](notebooks/prompt_injection_demo.ipynb) | Qwen의 네 가지 방어 조건에서 직접 질문과 외부 문서 처리 중 합성 토큰이 노출되는 비율과 정상 응답 비율을 측정합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/prompt_injection_demo.ipynb) |
| [아폴로 11호 1202 경보 시뮬레이션](notebooks/apollo_1202_executive.ipynb) | 코어 세트 8개, VAC 5개인 실행 관리자 모형에 레이더 간섭 부하를 걸어 1202 경보와 재시작 보호를 재현합니다. 단순화한 교육용 모형입니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/apollo_1202_executive.ipynb) |
| [벤포드 법칙 검정](notebooks/benford_law_census.ipynb) | 2의 거듭제곱, 미국 카운티 인구, 단위 변환, 균등 난수로 첫자리 분포를 카이제곱과 MAD로 검정합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/benford_law_census.ipynb) |
| [프롬프트 캐싱 손익분기](notebooks/prompt_cache_breakeven.ipynb) | 캐시 쓰기, 읽기 배수로 손익분기 재사용 횟수를 계산하고, 호출 간격과 TTL에 따른 비용을 시뮬레이션합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/prompt_cache_breakeven.ipynb) |
| [비밀번호 유출 조회의 k-익명성](notebooks/hibp_k_anonymity.ipynb) | Pwned Passwords range API가 SHA-1 앞 5자리만 받는 구조를 직접 구현하고, 버킷 크기와 패딩을 재 봅니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/hibp_k_anonymity.ipynb) |
| [난수 생성기 직접 구현과 예측](notebooks/rng_from_scratch.ipynb) | LCG, RANDU, Mersenne Twister, ChaCha20을 표준 라이브러리로 구현하고, 통계 검정과 MT19937의 내부 상태를 저장한 뒤 출력이 재생되는지 확인합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/rng_from_scratch.ipynb) |
| [LLM VRAM 계산과 T4 실측](notebooks/llm_vram_calculator.ipynb) | 가중치와 KV 캐시 공식을 Hugging Face 저장 용량과 대조하고, Qwen2.5를 T4에서 올려 공식과 실제 할당을 비교합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/llm_vram_calculator.ipynb) |
| [한국어 STT 실측 비교](notebooks/korean_stt_comparison.ipynb) | Whisper · faster-whisper · WhisperX · CrisperWhisper 2.0 을 같은 음성으로 돌려 정확도·속도·라이선스를 비교합니다. 한국어는 직접 올린 음성으로 잽니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/korean_stt_comparison.ipynb) |
| [ResNet degradation 재현](notebooks/resnet_degradation.ipynb) | 잔차 연결이 없으면 56층이 20층보다 나빠지고(degradation), 잔차 연결을 넣으면 뒤집히는지 CIFAR-10 으로 직접 돌려 확인합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/resnet_degradation.ipynb) |
| [어텐션 KV 캐시 대 선형 순환](notebooks/mamba3_inference_cost.ipynb) | 시퀀스가 길어질 때 토큰 1개를 뽑는 시간과 들고 있어야 하는 크기가 어떻게 달라지는지 최소 구현 두 개로 잽니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/mamba3_inference_cost.ipynb) |
| [Mamba-3 세 가지 변경 재현](notebooks/mamba3_ssm_mechanisms.ipynb) | 지수-사다리꼴 이산화의 수렴 차수, 입력 의존 회전과 홀짝 과제, SISO 대 MIMO 산술 강도를 작은 독립 실험으로 확인합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/mamba3_ssm_mechanisms.ipynb) |
| [트랜스포머 어텐션 NumPy 재현](notebooks/transformer_attention_numpy.ipynb) | √d_k 스케일링, 디코더 마스크, 위치 인코딩, RNN과 어텐션 비용을 NumPy로 직접 확인합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/transformer_attention_numpy.ipynb) |
| [SynthID 워터마크 논문 읽기](notebooks/synthid_tournament_watermark.ipynb) | 토너먼트 워터마크의 분포 보존·길이별 탐지·토큰 치환·엔트로피·생성 속도를 Qwen2.5-0.5B로 확인합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/No1Joon/oh-my-notebooks/blob/main/notebooks/synthid_tournament_watermark.ipynb) |
| [초간단 RAG 1탄 — 판결서](notebooks/legal-rag-01.ipynb) | AI Hub 판결서 익명처리 데이터에 라벨을 적용해 가명 코퍼스를 만들고, bge-m3 검색과 Qwen3-4B 생성으로 쟁점에 맞는 참고 판결 3건과 가상 판결 이유 초안을 받습니다. 데이터는 AI Hub 에서 직접 신청해 받습니다. | 로컬 Jupyter (Colab 불가) |
| [판결 임베딩 3D 지도](https://no1joon.github.io/oh-my-notebooks/legal-rag-map/) | 위 노트북의 판결 16,800건 bge-m3 임베딩을 UMAP 으로 3차원에 놓은 지도입니다. 같은 법령을 참조한 판결이 모이는지 돌려 봅니다. 좌표와 사건 유형·주 법령만 담았고 판결문 원문은 없습니다. | 웹 페이지 |

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
