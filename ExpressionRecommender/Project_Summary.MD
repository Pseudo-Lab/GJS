# Problem: 발화 능력 개선, 어렵습니다!

### 저는 다음 상황에서 좌절감을 많이 느낍니다

- 면접에서 자신을 드러내기
- 발표하기
- 처음 만난 사람과 대화하다 말이 끊어지는 것
- 설득하기 (혹은 영업하기?!)
- 영어 문화권의 사람들과 스몰 토크를 나누기

### 개선하려면, 반복 훈련

- 조리있게 말하는 발화의 기본기를 갖추고
- 상황과 task별로 적절한 행동이 무엇인지 알고  **(= 심리학에서의 social skill)**
- 그것이 몸에 배도록 반복 훈련해야 합니다!

### 훈련과 피드백 파트너가 필요합니다.

상대가 없을 때 허공에 대화하는게 무척 어렵고, 그걸 듣고 누군가는 객관적으로 찾아줘야 개선이 가능하겠죠?  

1. 전문가의 피드백이 필요하지만, 비싸요 
2. 주변 사람들의 한계 - 단편적으로만 보고, 집중해서 들어주는 데 한계가 있고, 잔소리 같습니다 

# Solution : AI 튜터 Agent와 스파링

내가 말하는걸 들어주고, **정해진 패턴**들 내에서는 적확한 피드백을 줄 수 있습니다! 

AI가 잡아줄 수 있는 정해진 패턴을 정의해서, 롤플레잉 상황으로 만들어 주었습니다. 

ex) 면접 상황에서 흔히 저지르는 실수: 업무 관련 질문에 충분한 디테일이나 계량적 지표를 제시하지 않는 것. 

이렇게 미리 정의된 부분은 잘 잡아줍니다!

저렴하고 affordable한, 전문가 80% 성능의 객관적 선생님 만들기를 목표로 진행했습니다. 

# 특징

### 기본적 유저 흐름

1. 원하는 대화 상황을 고르고, AI와 롤 플레잉 합니다
2. DB의 “대화의 기술social skill” 지식들을 기반으로 AI가 피드백을 줍니다 (RAG)
3. 대화 내역이 저장되고. **자주 저지르는 실수**를 짚어주는데 쓰입니다!  

### 추가적 개선사항

- 다중 사용자 지원 : 한 방에 여러 명이 들어와서 대화할 수 있습니다.
- 실시간 처리 : “AI 대화, 녹음, 분석” 순서가 있었는데, 이제 대화 중 실시간으로 답을 줍니다

# 결과물!
![UI](https://github.com/Pseudo-Lab/GJS/blob/main/ExpressionRecommender/chat%20room%20interface.png?raw=true)

이런 형태로의 채팅방을 만들었습니다. 

1. 훈련을 위하는 유저들은 방 코드를 통해 접속이 가능합니다. 
2. 제가 학습시킨 에이전트도 접속하고, 채팅방에서 활동합니다 
3. 유저와 대화를 마치면 ai 에이전트가 상황에 맞는 피드백을 줍니다! 

# 향후 개선 사항

1. 적용 범위 확대 : 더 많은 social skill / role play 상황을 찾아 추가합니다
2. 데이터셋 확보: 1을 위한 대화 상황 데이터셋을 만들어 넣습니다
