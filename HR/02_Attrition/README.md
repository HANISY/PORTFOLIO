# 퇴사를 촉발하는 주요 요인 분석
## 프로젝트 개요
```
· 퇴사의 영향을 미치는 다양한 요인을 분석하고, 특성을 파악하여 퇴사를 촉발하는 원인을 파악하고자 함
· 사용한 데이터 내 퇴사자는 전체 인원 중 16.1%로 이들이 가진 특성을 파악하여 3가지 가설을 설정함
· 가설 설정에는 총 30개의 변수가 고려되었으며, 주요 요인별 퇴사 여부와의 상관관계를 분석함
```
<p align="center">
<img src="https://github.com/HANISY/PORTFOLIO/blob/main/HR/02_Attrition/img/Attrition01.PNG" width="800">
</p>
* '집과의 거리'와 '월 소득'와의 상관관계는 변수 내 분포를 확인하기 위해 박스플롯(box plot) 사용 </br>
* '업무 성과'와 '업무 환경 만족도'와의 상관관계는 변수 별 차이를 확인하기 위해 막대그래프(bar) 사용 </br>

## 가설 검증
```
변수 중 '급여', '업무 환경 만족도', '업무 분야 일치 여부'가 퇴사를 결정한 요인이라고 판단하여 다음과 같은 3가지 가설을 세움 
1. 낮은 급여로 인해 퇴사를 결정할 것이다
2. 불만족스러운 업무 환경으로 인해 퇴사를 결정할 것이다. 
3. 적성에 맞지 않는 업무로 인해 퇴사를 결정할 것이다. 
```
<p align="center">
<img src="https://github.com/HANISY/PORTFOLIO/blob/main/HR/02_Attrition/img/Attrition02.PNG" width="800">
</p>

## 분석 결과
```
1. 퇴사 여부와 요인간의 상관관계가 약하기 때문에 특정한 단일 요인으로 인해 퇴사를 촉발한다고 단정지을 수는 없음
2. 퇴사를 하지 않은 사람들의 월 소득의 중앙값이 더 높은 곳에 위치하므로 월 소득은 퇴사에 영향을 미칠 수 있음
3. 대인관계 만족도가 낮을 수록, 출장 빈도가 잦거나 초과근무가 있을 경우 더 많이 퇴사함.
4. Human Resources 부서에서는 전공과 불일치한 사람이 더 많이 퇴사한 것을 알 수 있음.
5. 근속 연수가 낮을 수록 퇴사 비율이 높아지므로 연차별로 만족도를 향상시킬 수 있는 요인을 파악한다면 퇴사를 방어할 수 있을 것으로 예상됨. 
```
<p align="center">
<img src="https://github.com/HANISY/PORTFOLIO/blob/main/HR/02_Attrition/img/Attrition03.PNG" width="800">
</p>

## 분석 수정 방향
```
· 상관계수를 이용하여 변수를 해석할 때, 상관계수의 역할과 해석 과정에서 오해 발생 소지가 있는지 파악이 필요함. 
· 단위별 혹은 그룹별로 변수를 해석하는 등 다양한 변수 조작 방법을 통해 논리적 근거를 보충. 
```
