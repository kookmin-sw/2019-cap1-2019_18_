# Team. MBT

### 1. 프로젝트 소개

<div align="center">
  <img src="https://i.imgur.com/Dg1G3sh.jpg" width="30%" height="30%">
</div>

 미세먼지는 매년 꾸준히 증가하고 있습니다. 그렇기 때문에 정부에서는 외출을 삼가하고 실내 활동을 권장하고 있습니다.
 
<div align="center">
  <img src="https://i.imgur.com/kOg57Tz.jpg" width="50%" height="50%">
</div>

 실내에서도 요리나 가전제품 등으로 인한 미세먼지 발생으로 인하여 미세먼지가 하루 허용기준보다 100배 이상 치솟을 수 있기 때문에 환기를 권장하고 불가피하게 미세먼지의 농도가 높을 때에는 차선책으로 공기청정기를 사용하는 등의 대안을 제시하고 있습니다.
 실내의 공기질은 인체의 건강 상태뿐만 아니라 신체적, 심리적 안정에도 영향을 미칩니다. 따라서 실내 공기 환경 개선의 기준점이 단순히 유해물질을 제거하는 수준을 넘어서 생산 및 휴식 활동에 더욱 적절한 환경을 조성하는 지점으로 이동해야 함을 시사하고 있습니다.

이러한 이유로 저희는 환기를 비롯한 실내 공기 환경 개선을 더욱 효율적이고 체계적으로 관리하는 것을  **Mini BuT** 프로젝트를 통하여 해결해 보고자 합니다.
**Mini BuT**은 Mini Butler, 작은 집사라는 의미로 집 안을 관리하는 집사처럼 실내의 공기질을 관리해주는 의미를 담고 있습니다.

 라즈베리파이(Mini BuT)에 연결된 센서를 통해 실내 환경 데이터를 수집하여 MQTT 통신을 통하여 서버에 보냅니다. 서버는 공공데이터 API 통하여 실외 환경 데이터를 얻고 실내 데이터와 비교 분석합니다. 그 후 서버에서 분석 결과에 맞게 라즈베리파이에게 제어 명령을 전달합니다. 라즈베리파이는 IR통신(적외선 통신)으로 연동 기기(에어컨, 공기청정기, 창문 등)를 동작시킵니다.
 웹 앱을 사용하여 사용자가 축적된 환경 데이터를 손쉽게 확인할 수 있고, 연동 기기를 직접 제어할 수 있도록 합니다.

- - -


### 2. 소개 영상

프로젝트 소개하는 영상

- - -


### 3. 팀 소개

#### 지도 교수 : 이 상 환 교수님



<img src="https://i.imgur.com/vhQIome.jpg" width="200px">

```
* 오상화
* 역할 : 서버 구축 및 관리
         통신 컴포넌트 구현
* e-mail : minbosh92@gmail.com
```

<img src="https://i.imgur.com/q8d2hy7.jpg" width="200px">

```
* 김수은
* 역할 : 라즈베리파이 환경 구성
         웹 앱 구현
* e-mail : happyse97@naver.com
```

<img src="https://i.imgur.com/KLQqduu.jpg" width="200px">

```
* 민태준
* 역할 : 통신 컴포넌트 구현
         웹 앱 구현
         Mini BuT Hardware 제작
* e-mail : mtj2741@naver.com
```

<img src="https://i.imgur.com/kigbNp9.jpg" width="200px">

```
* 박재효
* 역할 : DB 생성 및 관리
         데이터 처리 컴포넌트 구현
* e-mail : ayopark12@gmail.com
```

<img src="https://i.imgur.com/6cciTaa.jpg" width="200px">

```
* 박종민
* 역할 : 연동 기기 Hardware 제작
         연동 기기 Software 구현
* e-mail : ansxjrdptj94@naver.com
```

- - -




