### AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김정현
- 리뷰어 : 박태하

### 뉴스 카테고리 다중분류
#### 요구사항
1. 주어진 영화 코퍼스를 바탕으로 워드임베딩 모델을 정상적으로 만들었다.
   (워드임베딩의 most_similar() 메소드 결과가 의미상 바르게 나왔다.)
   
2. 영화 구분, 장르별로 target, attribute에 대한 대표성있는 단어 셋을 생성하였다.
   (타당한 방법론을 통해 중복이 잘 제거되고 개념축을 의미적으로 잘 대표하는 단어 셋이 만들어졌다.)

3. WEAT score 계산 및 시각화를 정상적으로 진행하였다.
   (전체 영화 장르별로 예술/일반 영화에 대한 편향성 WEAT score가 상식에 부합하는 수치로 얻어졌으며 이를 잘 시각화하였다.)


### PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개,
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 코드를 캡쳐해 근거로 첨부
     
            워드 임베팅 모델 만들기
         ![image](https://github.com/seoulcity/AIFFEL_going_deeper/assets/110083249/8bf68c8c-2e5a-4940-acc4-facd0979dfad)
     
           장르별 대표단어 출력
         ![image](https://github.com/seoulcity/AIFFEL_going_deeper/assets/110083249/987cae6e-fbc6-46dc-8983-da78de6f2a63)

            장르별 셋 만들기
         ![image](https://github.com/seoulcity/AIFFEL_going_deeper/assets/110083249/4045a151-3f78-4b6c-8372-b6e1830f3b25)

            히트맵 - 시각화

         ![image](https://github.com/seoulcity/AIFFEL_going_deeper/assets/110083249/962d69cc-cb2a-41ef-97b9-9187b69a157d)



- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드가 무슨 기능을 하는지, 왜 그렇게 짜여진건지, 작동 메커니즘이 뭔지 기술.
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
     
          기본적으로 코드에 주석을 남기셔서 보기 편했습니다.


- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나”
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 문제에서 요구하는 조건에 더해 추가적으로 수행한 나만의 시도,
    실험이 기록되어 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.


- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
     
          회고와 노드에 대한 요약 및 느낀점을 상세하게 작성하셨습니다
          ![image](https://github.com/seoulcity/AIFFEL_going_deeper/assets/110083249/a3afe590-77d9-4dca-a636-b72a2e0f6eae)



- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 하드코딩을 하지않고 함수화, 모듈화가 가능한 부분은 함수를 만들거나 클래스로 짰는지
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화했는지
        - 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부합니다.
