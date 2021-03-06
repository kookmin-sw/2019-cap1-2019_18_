# Team. MBT

### 1. 프로젝트 소개

<div align="center">
  <img src="https://i.imgur.com/Dg1G3sh.jpg" width="40%" height="40%">
</div>

 미세먼지는 매년 꾸준히 증가하고 있습니다. 그렇기 때문에 정부에서는 외출을 삼가하고 실내 활동을 권장하고 있습니다.
 
<div align="center">
  <img src="https://i.imgur.com/kOg57Tz.jpg" width="60%" height="60%">
</div>

 실내에서도 요리나 가전제품 등으로 인한 미세먼지 발생으로 인하여 미세먼지가 하루 허용기준보다 100배 이상 치솟을 수 있기 때문에 환기를 권장하고 불가피하게 미세먼지의 농도가 높을 때에는 차선책으로 공기청정기를 사용하는 등의 대안을 제시하고 있습니다.

이러한 이유로 저희는 환기를 비롯한 실내 미세먼지 농도 관리 및 개선을 더욱 효율적이고 체계적으로 관리하는 것을  **Mini BuT** 프로젝트를 통하여 해결해 보고자 합니다.
**Mini BuT**은 Mini Butler, 작은 집사라는 의미로 집 안을 관리하는 집사처럼 실내의 공기질을 관리해주는 의미를 담고 있습니다.

 Mini BuT(라즈베리파이)에 연결된 미세먼지 센서를 통해 실내 미세먼지 데이터를 측정하고 수집하여 MQTT 통신을 통하여 서버에 보냅니다. 서버는 공공데이터 API와 KMU Crowd Sensor Cloud 통하여 대표성과 지역성을 확보한 실외 미세먼지 데이터를 수집하고 실내 데이터와 비교 분석합니다. 그 후 서버에서 데이터 처리 알고리즘을 통한 분석 결과에 맞게 Mini BuT에게 제어 명령을 전달합니다. 이로써 Mini BuT은 연동 기기(공기청정기, 창문 등)를 동작시킵니다.
 또한 웹페이지를 통하여 사용자가 축적된 실내 데이터를 손쉽게 확인할 수 있고, 연동 기기를 직접 제어할 수 있도록 합니다.

- - -


### 2. Abstract

Fine dust is increasing every year. So the government is encouraging people to stay indoors instead of going out.
However, there are also factors that cause fine dust from cooking and home Appliances etc. Therefore, ventilation is recommended
and alternative options are provided, such as using an air purifier when fine dust concentration is high.
For the reason, we intend to manage the indoor fine dust concentration, including ventilation, more efficiently and systematically through out **'Mini BuT'** project.
**'Mini BuT'** means 'Mini Butler'. It means a small butler, which manages indoor air quality, like a butler who manages the inside of the house.

Collects indoor environment data through sensors connected to Mini BuT(Raspberry Pi) and sends it to server by 'MQTT'communication.
The Server collects fine dust data through the public data Open API and KMU Crowd Sensor Cloud. This method ensures the representation and locality of the data. Then server compares and analyzes it with indoor environment data.
Then, the server sends control commands to the Mini BuT(Raspberry Pi) according to the analysis results.
The Mini BuT(Raspberry Pi) operates the devices connected to the Mini BuT.
Using Web Page, users can easily view their accumulated indoor environment data and directly control their devices.


- - -


### 3. 프로젝트 소개&시연 영상 및 사이트

아래 이미지를 클릭하시면 프로젝트 소개 영상을 보실 수 있습니다.

[![MASK](https://img.youtube.com/vi/S3fOQFMwCMY/0.jpg)](https://www.youtube.com/watch?v=S3fOQFMwCMY&feature=youtu.be)

아래 이미지를 클릭하시면 프로젝트 시연 영상을 보실 수 있습니다.

[![MASK](https://img.youtube.com/vi/_DypG1nGhQU/0.jpg)](https://www.youtube.com/watch?v=_DypG1nGhQU&feature=youtu.be)

프로젝트 소개 사이트 : https://kookmin-sw.github.io/2019-cap1-18/

- - -


### 4. 팀 소개

#### 지도 교수 : 이 상 환 교수님



<img src="https://i.imgur.com/vhQIome.jpg" width="300px">

```
* 오상화
* 역할 : 서버 구축 및 관리
         통신 컴포넌트 구현
* e-mail : minbosh92@gmail.com
* github : https://github.com/sangka9
```

<img src="https://i.imgur.com/q8d2hy7.jpg" width="300px">

```
* 김수은
* 역할 : 라즈베리파이 환경 구성
         웹 구현
* e-mail : happyse97@naver.com
* github : https://github.com/seiiq16
```

<img src="https://i.imgur.com/KLQqduu.jpg" width="300px">

```
* 민태준
* 역할 : 통신 컴포넌트 구현
         웹 구현
         Mini BuT Hardware 제작
* e-mail : mtj2741@naver.com
* github : https://github.com/tjmin
```

<img src="https://i.imgur.com/kigbNp9.jpg" width="300px">

```
* 박재효
* 역할 : DB 생성 및 관리
         데이터 처리 컴포넌트 구현
* e-mail : ayopark12@gmail.com
* github : https://github.com/KamJaTang
```

<img src="https://i.imgur.com/6cciTaa.jpg" width="300px">

```
* 박종민
* 역할 : 연동 기기 Hardware 제작
         연동 기기 Software 구현
* e-mail : ansxjrdptj94@naver.com
* github : https://github.com/MMKe
```

- - -


### 5. 사용법

  - aws ec2 server : http://bit.ly/2IGD4Uv
  - web server : http://bit.ly/2Piz4uH
  - db server : http://bit.ly/2UH2c4F
  - MQTT Broker, Client : http://bit.ly/2HD9Epb
