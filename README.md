졸업작품
=========
## ActionRecognition Fan (동작인식 선풍기)
ActionRecognition Fan(동작인식 선풍기)는 카메라와 초음파센서를 통해 사람을 인식하여
얼굴인식, 손동작인식, 얼굴방향으로 바람을 쐬어주는 선풍기이다.

## 사용기술

* ![python](http://img.shields.io/badge/-python-3776AB?style=flat-square&logo=python)
* ![opencv](http://img.shields.io/badge/-opencv-5C3EE8?style=flat-square&logo=opencv)
  * 노트북에서 소켓통신으로 전달받은 영상을 분석한다.
* 라즈베리파이
  * 라즈베리파이의 카메라를 이용해 분석에 필요한 영상을 촬영한다.
  * 라즈베리파이의 초음파센서를 이용해 가까운 물체를 인지하게 된다.
  * ![fsdf](https://user-images.githubusercontent.com/33804909/110243380-7c7b9900-7f9d-11eb-86f5-371810fb4d1e.PNG)
* 소켓통신
  * 라즈베리파이와 노트북 사이에서 request(영상)와 response(동작응답)을 통신해준다.
  * ![asd](https://user-images.githubusercontent.com/33804909/110243340-44745600-7f9d-11eb-9212-aa14aea867a4.PNG)


## 주요기능
1. 선풍기가 동작하지 않는 locked상태에서 얼굴을 인식하고, 미리 등록된 사용자의 얼굴이 확인이되면 선풍기 가동 시작   
![unlock](https://user-images.githubusercontent.com/33804909/110243201-b9935b80-7f9c-11eb-9fae-88cae9223123.gif)
2. 초음파 센서를 통해 사용자와의 거리와 방향을 측정하여 사용자의 위치에 따라서 바람의 방향을 조절   
![v1](https://user-images.githubusercontent.com/33804909/110241756-c9f40800-7f95-11eb-99b3-f25b7dbb5f34.gif)
3. 사용자의 행동(손 동작)을 인식하여 바람의 세기를 조절   
![v2](https://user-images.githubusercontent.com/33804909/110241760-d24c4300-7f95-11eb-832a-1fe70954a8e3.gif)









