## 대회명 : 신용카드 사용자 연체 예측 AI 경진대회
https://dacon.io/competitions/official/235713/overview/description

정형데이터의 고전적인 주제라고 생각하고 1등부터 10등까지 코드공개가 모두 되어있어서 선택

1. 입문자의 투박한 EDA
https://dacon.io/competitions/official/235713/codeshare/2494?page=1&dtype=vote

2. 하이퍼파라미터 튜닝을 쉽고 빠르게 하는 방법
https://dacon.io/competitions/official/235713/codeshare/2704?page=1&dtype=vote




데이터설명
- gender: 성별

- car: 차량 소유 여부

- reality: 부동산 소유 여부

- child_num: 자녀 수

- income_total: 연간 소득

- income_type: 소득 분류
							['Commercial associate', 'Working', 'State servant', 'Pensioner', 'Student']

- edu_type: 교육 수준
							['Higher education' ,'Secondary / secondary special', 'Incomplete higher', 'Lower secondary', 'Academic degree']

- family_type: 결혼 여부
							['Married', 'Civil marriage', 'Separated', 'Single / not married', 'Widow']

- house_type: 생활 방식
							['Municipal apartment', 'House / apartment', 'With parents',
							 'Co-op apartment', 'Rented apartment', 'Office apartment']

- DAYS_BIRTH: 출생일
							데이터 수집 당시 (0)부터 역으로 셈, 즉, -1은 데이터 수집일 하루 전에 태어났음을 의미

- DAYS_EMPLOYED: 업무 시작일
							데이터 수집 당시 (0)부터 역으로 셈, 즉, -1은 데이터 수집일 하루 전부터 일을 시작함을 의미
							양수 값은 고용되지 않은 상태를 의미함

- FLAG_MOBIL: 핸드폰 소유 여부

- work_phone: 업무용 전화 소유 여부

- phone: 전화 소유 여부

- email: 이메일 소유 여부

- occyp_type: 직업 유형													

- family_size: 가족 규모

- begin_month: 신용카드 발급 월
										데이터 수집 당시 (0)부터 역으로 셈, 즉, -1은 데이터 수집일 한 달 전에 신용카드를 발급함을 의미

- credit: 사용자의 신용카드 대금 연체를 기준으로 한 신용도
							=> 낮을 수록 높은 신용의 신용카드 사용자를 의미함