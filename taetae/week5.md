
## 개발자의 글쓰기 

### 독자 관점에서 릴리스 문서와 장애 보고서 쓰기

#### 1. 체인지 로그를 분류, 요약, 종합하는 법
- 지나치게 줄여쓰면 일을 안한 것처럼 보이고, 자세하게 쓰면 아무도 읽지 않는다.
> 따라서 일정한 기준으로 선정하고 요약하는 기술이 필요하다

- 1단계: 선정하기
- 2단계: 분류하기
- 3단계: 요약하기
- 4단계: 종합하기

#### 1단계: 선정하기
개발자가 노력을 들인 정도와 독자의 관심정도로 분류

#### 2단계: 분류하기
개발 관점에서 비슷한 작업끼리 묶는 방법
사용자 관점에서 비슷한 작업끼리 묶는 방법

#### 3단계: 요약하기
불필요한 부사, 형용사, 조사, 어미를 없애고 정확하고 적절한 단어로 대체
> 개조식으로 작성

#### 4단계: 종합하기
작업 내용별 카테고리 분류 + 카테고리별 상세 내용 작성 (개조식)

#### 2.고객에게 유용한 정보를 쓰자

- 개발자 관점
 > 화면이 멈춘 것
- 고객 관점
> 애니메이션 스티커를 댓글에 사용할 수 없는 것

고객의 문제를 앞쪽으로 옮기고, 개발자의 문제는 짧게 줄이자.

즉, `애니메이션 스티커를 댓글에 정상 사용 가능 (화면 멈춤 문제 해결)`로 표현가능

- 과거를 리뷰, 미래를 보여주자.
> 주요 개선 항목, 검토 중인 항목

- 유의적 버전
> X.Y.Z 형태, X가 0인 버전은 초기 내부 개발에서만 사용, Y는 기존 버전과 호환되는 새로운 기능 추가, Z는 기존버전과 완전히 호환되면서 작은규모의 패치
> 변경이 있다면 무조건 버전을 올려야한다.

#### 3. 릴리스 문서는 문제 해결 보고서 처럼 쓰자

- 문제와 문제점을 구분하자
- 문제에는 발생형, 탐색형, 설정형 문제가 있음
- 문제, 문제점, 해결책, 후속 계획 순으로 작성하자
- 법적인 문제를 고려해서 쓰자

#### 4. 비즈니스를 이해하는 장애보고서 쓰기

- 장애 보고서의 특징
1. 장애 보고서는 개발자가 원할 때 쓸 수 없다.
2. 장애의 1차 원인은 대부분 다른 원인의 결과다.
3. 장애 보고를 받는 윗사름은 대부분 개발자가 아니다.
4. 장애를 해결했다고 해서 100% 해결한 것은 아니다.

- 장애 보고서 작성 기법
1. 질문에 대답하는 신속한 글쓰기
2. 원인과 이유를 찾는 분석적 글쓰기
3. 상사를 고려하는 비즈니스 관점의 글쓰기
4. 원하는 것을 얻는 정치적 글쓰기