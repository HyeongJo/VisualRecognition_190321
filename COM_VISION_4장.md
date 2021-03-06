# Chpter 04. 지역 특징 검출
* 파노라마 영상을 구현하기 위해서는 이웃한 두 영상에서의 대응점을 찾아야 한다.
* 대응점찾기는 검출(detection) -> 기술(description) -> 매칭(matching) 으로 이루어 진다.
* 4장에서는 특징점의 위치를 알아내기 위한 검출에 대해서 공부해 보려고 한다.
<br>


## 내용 정리  

#### 목차  
**4.1절_** 지역 특징이 다른 대안을 누르고 가장 적합한 방법으로 대두된 역사와 지역특의 성질  
**4.2절_** 이동과 회전에 불변인 지역특징을 구하는 방법  
**4.3절_** 특징일 가능성이 높은 저들 중에서 어떤것을 특징점으로 취할지에 대해  
**4.4절_** 스케일 공간이론을 설명, 이 이론을 바탕으로 개발된 스케일 불변지역 검출 방법 기술
<br><br>


### 4.1 지역 특징 검출의 기초 **(What?)**  

###### 1. 특징 검출의 역사 : 지역특징의 대두  
무엇을 **특징점**으로 쓸것인가? - > 에지(3장)  
그러나 에지는 매칭에 사용하기에 빈약했다.  

-- > **지역특징**(명암 영상에서 직적 검출)  
코너의 물리적인 의미가 아닌 **반복성** 집중
<br><br>

###### 2. 지역 특징의 성질  
**<위치, 스케일, 방향, 특징 벡터>** 정보로 구성된다.

검출 - 위치 & 스케일 **(공변)**  
기술 - 방향 & 특징 벡터 **(불변)**  

지역특징이 만족해야할 특성  
(반복성, 분별력, 지역성, 정확성, 적당한 양, 계산효율)
<br><br><br>

### 4.2 이동과 회전에 불변한 특징점 검출 **(How?)**
###### 1. 모라벡 알고리즘 
###### 2. 해리스 코너
###### 3. 2차 미분을 사용한 방법
###### 4. 슈산


### 4.3 위치 찾기 알고리즘


### 4.4 스케일에 불변한 특징점 검출
###### 1. 스케일 공간
###### 2. 해리스 라플라스 특징 검출
###### 3. SIFT 검출
###### 4. SURF 검출
###### 5. 문제가 처한 환경에서의  비교 실험 후 선택










