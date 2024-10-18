# Video Reocorder 

천안시 교통 CCTV의 RTSP 주소 사용

## 미션
1. 화면에현재카메라영상표시
* OpenCV의 cv.VideoCapture를 이용하여 카메라 영상 얻기 (인자: 0 또는 정수)
![image](https://github.com/user-attachments/assets/acafedfa-36bf-4e62-869a-d54cd5413309)
![image](https://github.com/user-attachments/assets/b8f5ccbf-d691-499f-a480-e350cd022108)

2. 카메라 영상을 동영상 파일로 저장, Prewview와 Record 모드 도입
* OpenCV의 cv.VideoWriter를 이용하여 동영상 파일 만들기
* Record 모드 시 화면에 표시
* Space 키에 모드 변환
* ESC 키에프로그램종료
* 
![image](https://github.com/user-attachments/assets/1d036efe-f6c4-4b28-ad9d-ab0d93789ed4)

![image](https://github.com/user-attachments/assets/6ae3cfd2-a514-43b1-ab89-588cf9418296)

* 저장된 동영상
output.avi로 만들어지는걸 확인 가능

![image](https://github.com/user-attachments/assets/73a72601-458e-4866-8ea0-294053073108)

https://github.com/user-attachments/assets/e4b9d1ec-c75b-4b3a-9699-980950ad4a64


## 추가 기능
1. 녹화 중 타임스탬프 
* 영상의 왼쪽 하단에 현재 시간을 표시, cv2.putText() 함수를 사용하여 타임스탬프가 출력
![image](https://github.com/user-attachments/assets/e03ba85e-ad2e-4e30-a8c2-70e4ba5ba653)

![image](https://github.com/user-attachments/assets/ace45972-f770-42ec-a72f-16047f4c3bfd)


2. 스크린샷 기능 
* 'q' 키를 누르면 현재 프레임이 screenshot_0.png, screenshot_1.png 등의 파일 이름으로 저장

![image](https://github.com/user-attachments/assets/90e587ab-96d6-44fd-ac9f-5b9f15ebc20e)

![image](https://github.com/user-attachments/assets/a633609e-1e16-4e1d-9ca4-44603c2a8f59)

* screenshot_0.png 원본
![image](https://github.com/user-attachments/assets/e33c2609-2455-4bb9-b0ba-e10cce3a111a)

3. 카메라 줌/팬/틸트 기능 
* '+' 키로 화면을 확대(줌 인)할 수 있으며, '-' 키로 축소(줌 아웃)할 수 있습니다. 확대는 최대 3배까지 가능
* 화살표 키 (W, A, S, D)를 사용하여 화면을 위, 아래, 왼쪽, 오른쪽으로 이동

![image](https://github.com/user-attachments/assets/f480fad8-d3ba-442b-befb-1d28e39eb59b)
 
![image](https://github.com/user-attachments/assets/93e225d9-3e52-4788-92fb-c4aae739a91c)



https://github.com/user-attachments/assets/cf058e31-d5f9-4324-bc0c-de277c7e06f5


