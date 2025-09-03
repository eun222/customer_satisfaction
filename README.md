# customer_satisfaction

## 데이콘 Basic 고객 지원 등급 분류: 도움이 필요한 고객을 찾아라!


현대의 다양한 서비스 환경에서는 고객 경험(Customer Experience)이 점점 더 중요해지고 있습니다.

특히 고객이 겪는 문제를 빠르게 파악하고 선제적으로 대응하는 것은 고객 만족도는 물론, 이탈률 감소와 서비스 품질 향상에도 직접적인 영향을 미칩니다.



고객의 이용 행동과 계약 정보 등을 분석하여 어떤 고객이 더 많은 지원을 필요로 하는지 미리 예측할 수 있다면,

서비스 제공자는 보다 효율적으로 자원을 배분하고, 맞춤형 고객 응대를 실현할 수 있게 됩니다.

이번 해커톤은 고객의 서비스 이용 데이터를 기반으로 지원 필요 수준을 분류하는 AI 알고리즘 개발에 도전하게 됩니다.


고객의 행동 및 계약 특성을 바탕으로, 고객 지원 필요도를 예측할 수 있도록 분류 모델을 만들어보세요!

## 데이터 정보

train.csv [파일] :
ID : 샘플별 고유 ID
age : 고객 나이
gender : 고객 성별
tenure : 고객이 서비스를 이용한 총 기간 (월)
frequent : 고객의 서비스 이용일
payment_interval : 고객의 결제 지연일
subscription_type : 고객의 서비스 등급
contract_length : 고객의 서비스 계약 기간
after_interaction : 고객이 최근 서비스 이용으로부터 경과한 기간 (일)
support_needs : 고객의 지원 필요도 (0 : 낮음 , 1 : 중간 , 2 : 높음)


test.csv [파일] :
ID : 샘플별 고유 ID
age : 고객 나이
gender : 고객 성별
tenure : 고객이 서비스를 이용한 총 기간 (월)
frequent : 고객의 서비스 이용일
payment_interval : 고객의 결제 지연일
subscription_type : 고객의 서비스 등급
contract_length : 고객의 서비스 계약 기간
after_interaction : 고객이 최근 서비스 이용으로부터 경과한 기간 (일)


sample_submission.csv [파일] - 제출 양식
ID : 샘플별 고유 ID
support_needs : 고객의 지원 필요도 (0 : 낮음 , 1 : 중간 , 2 : 높음)
