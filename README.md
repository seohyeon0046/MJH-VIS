# MJH-VIS

부업(multiple jobholding) 시각화 모음.

## 부업자의 하루 (원본형)

`day-in-the-life/index.html` (page title: MJH Day in the Life)

Nathan Yau의 [A Day in the Life of Americans](https://flowingdata.com/2015/12/15/a-day-in-the-life-of-americans/)(FlowingData, 2015) 방식을 따라, 미국생활시간조사(ATUS) 응답자 1,000명이 하루 동안 활동 사이를 오가는 모습을 점으로 보여줍니다.

- 점 하나 = 응답자 한 명. 원본처럼 확률로 시뮬레이션하지 않고, 각자 실제 일지에 적힌 분(分)에 다음 활동으로 옮겨 갑니다.
- 집단: 그날 부업한 부업자(TEMJOT=1이고 그날 050102 부업 활동이 있는 사람) / 부업 없는 취업자(그날 본업을 한 사람). 평일·주말, 공휴일 제외.
- 각 집단에서 최종 가중치(TUFNWGTP, 2020년은 TU20FWGT)에 비례해 1,000명을 뽑았습니다. 시간 조절 바 아래 선그래프는 집단 전체에 가중치를 적용한 비율입니다.
- 활동 분류(10개): 수면, 개인관리, 본업(050101), 부업(050102), 이동(18), 가사(02), 돌봄(03·04), 식사(11), 여가(12·13), 기타.

자료: U.S. Bureau of Labor Statistics, American Time Use Survey 2003–2025 다년도 파일(atusresp, atusact).

파일 하나로 동작하며(데이터 포함), 브라우저에서 바로 열 수 있습니다.
