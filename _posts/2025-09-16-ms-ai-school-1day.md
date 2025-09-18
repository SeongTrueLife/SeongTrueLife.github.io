---
layout: post
title: "Microsoft AI School 첫번째 날"
date: 2025-09-16
---

## GitHub Pages 블로그 처음으로 개설했습니다!

오늘 처음으로 GitHub 블로그를 개설했습니다. 
앞으로 AI 개발자가 되기 위해 공부한 내용들을 꾸준히 기록할 예정입니다.

### 오늘 MS AI School 에서 배운 것(Generative AI)
 #### Generative AI의 소개
 - Generative AI의 정의
  - 인공지능 분야의 하나로, 그림, 텍스트, 소리(음악), 영상 등을 새롭게 만드는 독창적인 인공지능
  - example : MyLens.ai
 - Generative AI의 기술적 배경 및 특징
  - 1. 머신러닝은 주로 인코딩(학습데이터등을 축약하는) 과정으로 이루어진 데 비해, Generative AI는 인코딩과 디코딩(콘텐츠를 출력하는) 두가지로 이루어져 있다.
    2. LLM/ Deep Learning : node, layer, weight 로 이루어진 인공신경망으로 이루어짐. 모델 성능은 구조보다는 크기(parameters)에 의존(Scaling law)
    3. Emergent Abilities : 특정 크기(parameters)를 기준으로 모델 성능이 급상승 하는 현상.
    4. SLM : Small Language Model : 휴대폰 등 사용 목적에 따라 좀더 가벼운 모델. 1500만개 미만의 parameters로 도 가능
 - Generative AI 의 문제점
   - 1. Hallucination(환각)
     2. Bais In, Bais out: 편견있는 데이터를 입력하면 편견있는 결과를 내뱉음. 데이터 의존성
     3. Copyright & IP infringement: 저작권 문제
     4. Data Privacy, Confidentiality: 개인정보 문제, 보안 문제.
     5. 그 밖에 수학적 추론을 잘 못한다는것, float(실수) 크기 비교를 잘 못한다는 점, 시각 추론(손가락 갯수) 공간 추론 문제 등을 잘 못한다는 문제점 존재. 단 최신 추론 모델의 경우 상대적으로 나음(gemini 2.5 pro의 경우 시각추론과 공간추론 문제는 다 틀린답 냈다.)
 
 #### Generative AI의 성장과 확산
 - 참고할 만한 site:
  - 1. https://app.dealroom.co/lists/33530 : Generative AI 분야의 스타트업 회사를 볼 수 있는 사이트. 투자액도 보여서, 최근 관심가는 AI기술이 뭔지 볼수 있을지도?
    2. https://www.futuretools.io/ : Generative AI 도구를 검색하고 사용해 볼 수 있음.(비슷한 사이트 https://topai.tools/)
    3. https://huggingface.co/
 - Generative AI 적용이 기대/예상되는 분야 : 헬스케어(특히 요즘 관심도 up), Manufacturing, ReTail & E-Commerce, BFSI(금융서비스), Midia, Legal, Government&Defense(국방), etc..
 - Azure 사이트에 들어가면 OpenAI를 이용해 서비스 제공하는 회사들의 스토리도 볼 수 있다.
 - AGI는 possible 할 것인가?
   - 최근에는 AGI(강인공지능, 혹은 일반 인공지능-Artificial General Intelligence-)이 가능할거라는데는 의견차이는 없다. 다만, Doomer VS Boomer의 의견대립이 있을뿐.
   - 인공지능 4대천왕(Goffrey Hinton, Yann LeCun, Yoshua Bengjio, Andrew Ng) 중 한명인 Yann LeCun은 현재 Transformer 형식의 LLM으론 한계가 있다 말함.
   - Yann LeCun 은 4가지 능력- 추론(reasoning), 계획(planning), 영구 기억(persistent memory), 실제 세계 이해(understanding physical world) 네 가지 인지적과제 지적.
   - 현재 AI에 대한 대안으로 World Model 을 개발하는걸 목적으로 하고있음, LWM(Large World Model)
 #### 챗봇 기반 Generative AI
 - 현재 LLM 들은 Transformer 구조로 이루어져 있음. Transformer 구조는 Encoder와 Decoder로 이루어짐(자세한건 딥러닝 강의에서)
 - 개인적으로 배운것 : Chat Gpt 혹은 Gemini 를 이용해서, AI 분야 최근 일주일 전 최신 CNN 등 기사 뽑아달라하고, 영어 번역 및 문법 설명, 단어 설명 등을 해주는 GPTs 나 Gems 만들기
 - 프롬프트 작성하기
  -
