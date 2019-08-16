
# 딥러닝 안에서 일어나는 과정을 설명하는 인공지능 기술(PyCon Korea 2019 Tutorial)

## Introduction
설명가능인공지능 연구센터는 과학기술정보통신부에서 설립한 연구센터로, 인공지능 모델의 결정을 인간이 이해하고 해석할 수 있는 수준의 설명을 제공하는 설명가능 인공지능(XAI: Explainable Artificial Intelligence) 기술을 연구합니다. 본 센터는 2017년 9월 개소하여, 주관기관인 UNIST를 비롯해 KAIST, 고려대학교, 서울대학교, 연세대학교와 AITRICS 소속 200여명의 연구원들이 세계적 수준의 연구를 진행하고 있으며, 미국 DARPA, 독일 베를린 빅데이터 센터등 해외 기관과 활발하게 교류하고 있습니다. 

본 센터는 인공지능 시스템의 의사결정 이유 설명 및 인터페이스 개발, 금융/의료/경제 분석 등 실세계 응용에 대해 연구를 진행하고 있으며, 주요한 결과물을 오픈소스로 홈페이지(http://xai.unist.ac.kr)를  통하여 공개하고 있습니다. 

이번 파이콘 한국 2019에서 인공지능에 관심이 있는 참가자분들이 파이썬을 이용하여 설명가능인공지능을 직접 구현하면서 배울 수 있는 튜토리얼을 진행합니다. 파이썬 사용자분들의 많은 관심과 적극적인 참여 부탁드립니다.

## Contents
+ 14:00 ~ 15:00 : [설명가능인공지능(Explainable Artificial Intelligence, XAI)이란?](https://github.com/OpenXAIProject/PyConKorea2019-Tutorials/blob/master/PyConKorea2019-Introduction-presentation.pdf)
+ 15:00 ~ 15:20 : [실습 환경 세팅](https://github.com/OpenXAIProject/PyConKorea2019-Tutorials/blob/master/colab_setting.ipynb) 
+ 15:20 ~ 15:40 : 쉬는 시간
+ 15:40 ~ 16:30 : [레이어 단위 관련성 전파 모델 (LRP) 튜토리얼](https://github.com/OpenXAIProject/PyConKorea2019-Tutorials/blob/master/LRP/README.md)
+ 16:30 ~ 16:50 : 쉬는 시간
+ 16:50 ~ 17:40 : [모델 불가지론적 방법 모델 (SHAP) 튜토리얼](https://github.com/OpenXAIProject/PyConKorea2019-Tutorials/blob/master/SHAP/PyConKorea2019-SHAP-tutorial-presentation.pdf)
+ 17:40 ~ 18:00 : QnA

## Preliminary
실습을 위해서는 개인 노트북이 필요합니다.
실습은 구글 코랩에서 진행됩니다. 많은 인원이 동시에 인터넷을 사용할 경우 학습이 느려지기 때문에 개인적으로 딥러닝 학습이 가능한 실습환경 구축이 가능하신 경우 준비해오시는 것을 추천드립니다.
실습에서 사용될 소스 코드와 발표자료는 모두 XAI Github를 통해 공개할 예정입니다. 발표전까지 메일과 본 페이지에 공지 드리겠습니다. (Google과 Github에 미리 가입해주세요.)

## Reference
+ LRP: 
1. **"Explaining nonlinear classification decisions with deep taylor decomposition"**. Gregoire Montavon, Sebastian Bach, Alexander Binder, Wojciech Samek, and Klaus-Robert Muller (https://arxiv.org/abs/1512.02479)
2. Based on code by [Leila Arras](https://github.com/ArrasL/LRP_for_LSTM), [Cyc1am3n](https://cyc1am3n.github.io/2018/11/10/classifying_korean_movie_review.html) and [albermax](https://github.com/albermax/innvestigate)

+ SHAP:
1. Based on codes by [Scott Lundberg](https://github.com/slundberg/shap) and [Christophe Rigon](https://www.kaggle.com/datacog314/tutorial-machine-learning-interpretability)
2. **"A Unified Approach to Interpreting Model Predictions"**. Scott Lundberg, Su-In Lee (https://arxiv.org/abs/1705.07874)

## Futher Information
+ [XAI 센터 공식홈페이지](http://xai.unist.ac.kr/)
+ [XAI 센터 깃허브](https://github.com/openxaiProject)
+ [XAI 센터 Youtube 채널](https://www.youtube.com/channel/UCGxsfIsOry_LdBaPSet2p7g]


# XAI Project 

**This work was supported by Institute for Information & Communications Technology Promotion (IITP) grant funded by the Korea government (MSIT) (No.2017-0-01779, A machine learning and statistical inference framework for explainable artificial intelligence)**

+ Project Name : A machine learning and statistical inference framework for explainable artificial intelligence (의사결정 이유를 설명할 수 있는 인간 수준의 학습·추론 프레임워크 개발)

+ Managed by Ministry of Science and ICT/XAIC <img align="right" src="http://xai.unist.ac.kr/static/img/logos/XAIC_logo.png" width=300px>

+ Participated Affiliation : UNIST, Korea Univ., Yonsei Univ., KAIST, AItrics  

+ Web Site : <http://openXai.org>


