# **2019 프로그래밍 공모전**
2019 인하대학교 프로그래밍 공모전<br>
손인아, 서민균, 안은노, 최희정

<br><br>

# **<i>🚶🏻 보행자 알리미 🚶🏻</i>**

<br><br>

## **1. Problem**
![이면도로 설명](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드3.png?raw=true)

<br>

![전체 교통사고에서 이면도로 교통사고가 차지하는 비율](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드4.png?raw=true)

<br>

![대응 쉽지 않음](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드5.png?raw=true)

<br>

![프로젝트 제안 동기](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드6.png?raw=true)


<br><br>

## **2. Product**
![보행자 알리미](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드7.png?raw=true)

<br>

![오브젝트 디텍션 예시](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/ex-object-detection.png?raw=true)

<br>

![사용자의 어플에서 보이는 것](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/application.gif?raw=true)

<br><br>

## **3. How to Work**
- 라즈베리파이 3 Model B+, 카메라 모듈, GPS 모듈 사용
- 라즈베리파이에서 식별된 정보를 비콘으로 전송하여 맵에 마킹하는 방식
    - 고정되어 있는 카메라의 경도・위도 값을 이용해 카메라 내에 들어온 객체의 경도・위도 값 추정
    - Tensorflow의 SSDLite MobileNet V2 사용
        - 라즈베리파이 하드웨어의 성능 제한으로 인해 해당 모델 선택

<br>

![개략적인 작동 방식](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드9.png?raw=true)

<br>

![Object Detection](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드10.png?raw=true)

<br>

![Bluetooth Beacon](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드11.png?raw=true)

<br><br>

## **4. Effect**
![기대효과](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드11.png?raw=true)

<br>

![기대효과](https://github.com/huijeong12/programming-contest-walkers/blob/main/images/슬라이드12.png?raw=true)