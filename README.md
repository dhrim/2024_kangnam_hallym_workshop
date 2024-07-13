# 2024 강남성심병원 AI 워크샾

의료 연구를 위한 딥러닝과 생성형AI 워크샾

<br>

# 목표

의학 연구자 혹은 임상의가 딥러닝과 생성형AI를 파악하여 실제 연구에 활용할 수 있는 기반을 마련한다.

<br>

# 교육 내용

첫 날은 AI와 딥러닝의 실체를 데이터와 코드 실습으로 파악합니다. 
연구에 사용되는 AI가 어떠한 데이터가 어떻게 준비되어 어떠한 과정으로 결과라 나오는지를 파악하여 AI를 사용한 연구 실체에 대한 기반 개념을 잡습니다.

<br>

둘 째 날은 생성형AI에 대한 개념과 그 활용 예들을 파악합니다.
그리고 ChatGPT의 활용 실습과 ChatGPT를 프로그래밍적으로 접근하여 활용하는 OpenAI API를 실습합니다.
ChatGPT와 같은 생성형 AI는 아직 연구에 직접 활용은 어렵지만, 제대로 파악해 두어야 할 사항입니다.

<br>

# 진행 일정

## 1일차

- AI의 이해, 딥러닝의 이해 [AI_intro.pptx](AI_intro.pptx)
- 실습 환경 셋업과 소개
- 딥러닝 실습 [dnn_intro.ipynb](material/dnn_intro.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/dnn_intro.ipynb)
    - 최소 DNN 코드 실습
    - 영상 데이터의 이해
    - 영상 데이터 분류, 컬러영상 데이터 분류
    - 영상 데이터 회귀
- 딥러닝 활용 실습 [dnn_application.ipynb](material/dnn_application.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/dnn_application.ipynb)
    - AutoEncoder 실습
    - AutoEncoder를 사용한 노이즈 제거 실습
    - AutoEncoder를 사용한 해상도 증대 실습
    - U-Net을 사용한 영상분할 실습


<br>

## 2일차
- 생성형 AI 이해 [generative_AI_intro.pptx](generative_AI_intro.pptx)
- ChatGPT, OpenAI API 소개 [generative_AI_intro.pptx](generative_AI_intro.pptx)
- ChatGPT 실습 [generative_AI_intro.pptx](generative_AI_intro.pptx)
- OpenAI API 실습
    - 호출 방법과 Prompt 실습 [openai_api_intro.ipynb](material/openai_api_intro.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/openai_api_intro.ipynb)
    - 파인 튜닝 실습 [how_to_fine_tuning.ipynb](material/how_to_fine_tuning.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/how_to_fine_tuning.ipynb)
    - image 태그달기 실습 [openai_api_image.ipynb](material/openai_api_image.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/openai_api_image.ipynb)
    - image 생성 실습 [openai_api_image_generation.ipynb](material/openai_api_image_generation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/openai_api_image_generation.ipynb)
    - 동영상 학습 확인을 위한 퀴즈 생성 실습 : [movie_2_quiz.ipynb](material/movie_2_quiz.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/movie_2_quiz.ipynb)
    - 동영상에서 음성 네레이션 생성 : [movie_2_voice_narration.ipynb](material/movie_2_voice_narration.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/movie_2_voice_narration.ipynb)
    - 임베딩
        - OpenAI의 임베딩 소개글 : https://openai.com/index/introducing-text-and-code-embeddings/
        - 임베딩 실습 : [how_to_embedding.ipynb](material/how_to_embedding.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/how_to_embedding.ipynb)
    - 임베딩을 사용한 커스텀 QnA 엔진 실습 : [customer_qna_engine.ipynb](material/customer_qna_engine.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/2024_kangnam_hallym_workshop/blob/main/material/customer_qna_engine.ipynb)

<br>

# 참가자 사전 요구 사항
프로그래밍에 대한 경험이 전혀 없는 분들을 대상으로 합니다.
프로그래밍이나 python, 데이터 처리에 대한 사전 지식을 요구하지 않습니다.
하지만 크롬과 같은 웹브라우저 사용이나 엑셀에서의 데이터 처리에 낯설지 않아야 합니다.
<br>
실습은 python으로 진행되지만, 실제 프로그래밍 입력은 하지 않고, python 프로그램을 읽고 해석하며 어떻게 데이터가 처리되고 어떻게 딥러닝이 수행되는지 이해하는 실습입니다.

<br>

# 참가자 준비 사항

설명과 실습으로 진행합니다. 실습하기 위한 개인 별 컴퓨터 혹은 노트북이 필요합니다. 구글 계정으로 로그인해야 하기에 개인 노트북을 지참하시는 것을 권장합니다. 
설치되어 있어야할 프로그램은 크롬 웹브라우저 뿐입니다.
<br>
더불어 딥러닝 학습과 실습을 위한 클라우드 서비스를 사용할 예정이며, 이 서비스 등록을 위한 카드 정보가 필요합니다.
하지만 카드로 결제되는 실습 비용은 1000원 미만입니다.

<br>

# 참고 자료

- Awesome Generative AI : https://github.com/steven2358/awesome-generative-ai
- Awesome ChatGPT Prompt : https://github.com/f/awesome-chatgpt-prompts
- 단계별로 딥러닝 적용한 논문 사례 : https://docs.google.com/presentation/d/1SZ-m4XVepS94jzXDL8VFMN2dh9s6jaN5fVsNhQ1qwEU/edit 중 리뷰5
- 알파고 이해하기 [understanding_alphago.pptx](understanding_alphago.pptx)

