# Week2 릴레이 노트

작성 그룹: 35번

## 퀘스트 목록

### 퀘스트 1 (개선 후)

오늘 학습한 내용을 바탕으로 LLM을 이용해 ***N지 선택 객관식 문제 N개 만들고*** 풀어보기 (tip: gemini)

### 퀘스트 2 (개선 후)

LLM을 이용해 지금까지 ***수행해온 미션의 학습 내용*과 관련해** 오늘 기준으로 제일 Star를 많이 받은 git 레포지토리 링크를 출력하기

### 퀘스트 3

길라잡이 때 나오는 피어피드백때 얘깃거리와 전날 미션 정보를 입력하여, 피어 피드백 시간에 토론 거리 만들기

### 퀘스트 4 (개선 후)

하루에 한번씩 ***현재 미션을 수행하면서 느낀점이나 어려운 점***을 AI에게 프롬프트로 입력하고, 이에 대한 ***조언이나 학습 팁***을 받아 팀원들과 나누기

(달성 조건: 최소 1회)

---

## 토론 내용

### 퀘스트 1

```
[ 문제 상황 ] 매일 배우는 내용은 많은데, 뒤돌아보면 머릿속에 남아 있는지 잘 모르겠습니다.

[ 조사 ] 노트 LM 혹은 LLM에서 개인화 작업을 하면 요구 사항에 맞게 문제를 만들 수 있다.

[ 퀘스트 ] 오늘 학습한 내용을 바탕으로 LLM을 이용해 ox 10 문제 만들기
```

- 기존 OX 문제에서 객관식 문제 풀기로 개선. 더 고민해볼 수 있으니까 & 문제에 더 많은 복습 효과가 있으니까
- 제미나이 사용하면 카드형태로 퀘스트 뽑아줌

### 퀘스트 2 개선점

```
[ 문제 상황 ] 미션을 하느라 최신 기술 동향을 알아볼 생각도 못하겠네요.

[ 조사 / 예시 ] 오늘 기준으로 최신 데이터를 LLM을 이용해 출력할 수 있습니다.

[ 퀘스트 ] LLM을 이용해 오늘 기준 제일 Star를 많이 받은 git 레포지토리 링크를 출력합니다.
```

- 기존 내용이 포괄적이라고 느꼈음 → 학습 내용(미션 관련) 관련해서 최신 기술 동향 알아보기
ex. 함수형 프로그래밍

### 퀘스트 4 개선점

```swift
[ 문제 상황 ] 서로 서로 친해지고 싶은데, 말 걸기가 쉽지 않습니다ㅠㅠ

→ 친해질 수 있는 계기가 있었으면 좋겠어요!

[ 퀘스트 ] 하루에 한번씩 특성을 추가한 다음, 명언을 받아 팀원에게 보내기.
```

- 토론 거리의 주제를 명언으로 제한할 필요가 있을까? 학습과 연관이 있다면 더 좋겠다.
- AI에게 해당 미션을 수행하면서 느낀 점을 보내주고 그에 대한 명언 or 학습 방법에 대한 팁 or 인생 조언을 받는다
- 같은 미션을 수행하면 비슷한 경험을 하지 않을까?
- → 얏호. 이야깃거리가 생겼다.

## 조사 내용

### 퀘스트 1

**테스트 결과:**

[https://obsidian-gallium-868.notion.site/2-23b0986a763180c39bd4e7f03ad7b928?source=copy_link](https://www.notion.so/23b0986a763180c39bd4e7f03ad7b928?pvs=21)

### 퀘스트 2

**chat GPT 프롬프트 예시**:

“오늘 기준으로 함수형 프로그래밍(Functional Programming) 관련 GitHub 레포지토리 중 최근에 Star를 많이 받은 인기 레포를 소개해줘. 어떤 기술을 다루고 있고, 왜 주목할 만한지 설명도 포함해줘.”

**결과 예시**:

https://chatgpt.com/share/68832133-12b4-8002-a9e6-b9747d0f4c1c

**클로드 프롬프트 예시:**

“함수형 프로그래밍이라는 주제로 최신 기술 동향을 파악하려고 해. 오늘 기준 제일 Star를 많이 받은 git 레포지토리 링크를 찾아줄 수 있어?” + ”그 깃 레파지토리들의 최근 수정일이 언제인지도 표시해줄 수 있어?”

결과 예시:

[https://www.notion.so/juhee-dev/2-23b668b6ca9180cdbf1ed787f3b32863?source=copy_link](https://www.notion.so/2-23b668b6ca9180cdbf1ed787f3b32863?pvs=21)

### 퀘스트 4

**chat GPT 프롬프트 예시**:

잠을 하루에 4시간을 잘 정도로 노력했어 그런데 다음날 팀원들의 결과물을 보면 나의 결과물이 매우 초라해 보여
결과 예시:

"Don't compare yourself to others. Compare yourself to the person you were yesterday."

— *Anonymous*

다른 사람과 자신을 비교하지 마라. 어제의 너와 비교하라.

**AI의 추가적인 말(선택사항):**

당신은 이미 **어제의 나보다 더 성장**했고, 4시간의 수면 속에서도 포기하지 않았다는 점에서 충분히 대단해요. 타인의 성과는 “자극”으로 삼되, 기준은 **늘 나 자신**이어야 합니다. 오늘의 당신이 어제보다 단 1%라도 나아졌다면, 그건 **성공** 이에요.


----
### J098_류지수

#### [ 퀘스트 2 ] : LLM을 이용해 지금까지 수행해온 미션의 학습 내용과 관련해 오늘 기준으로 제일 Star를 많이 받은 git 레포지토리 링크를 출력하기
#### 선택이유 : 미션 관련하여 더 깊이 학습하고 인사이트를 얻기 위해


### K026_차희선
#### [ 퀘스트 3 ] : 길라잡이 때 나오는 피어피드백때 얘깃거리와 전날 미션 정보를 입력하여, 피어 피드백 시간에 토론 거리 만들기
피어 피드백에 들어가기 전, 본인이 수행한 미션에 대해 충분히 고민하는 시간을 가져야 하는데 지금까지 그렇게 하지 못했던 것 같아서 이번 기회를 통해 피어 피드백을 잘 준비해보고 싶다.

### J248_정희재

#### [ 퀘스트 4 ] : 하루에 한번씩 ***현재 미션을 수행하면서 느낀점이나 어려운 점***을 AI에게 프롬프트로 입력하고, 이에 대한 ***조언이나 학습 팁***을 받아 팀원들과 나누기
#### 선택이유 : 같은 임무를 수행하는 동료들에게 미션을 수행하면서 느낀점이나 어려운점은 최고의 대화주제. 조언이나 학습 팁은 실용적이기까지 하니 선택했다.

### J113_박영규
#### [ 퀘스트 4 ] : 하루에 한번씩 ***현재 미션을 수행하면서 느낀점이나 어려운 점***을 AI에게 프롬프트로 입력하고, 이에 대한 ***조언이나 학습 팁***을 받아 팀원들과 나누기
#### 선택이유: 부스트 캠프 과정속에서 회고는 중요합니다. 내가 오늘 미션을 잘 수행했는지 점검하고 만약 못했다면 내일은 어떻게 개선해볼 것인지 생각해볼 수 있기 때문입니다. 제가 미션을 수행하면서 느낀 감정을 AI에게  입력하고 학습 팁이나 개선점을 받아볼 기회가 있으면 좋겠다고 생각했습니다.

