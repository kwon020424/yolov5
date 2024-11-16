# yolov5
yolov5 학습 보고서

# 주제
 최근 한국에서 도로에 균열이 생겨 움푹 패이는 '포트홀'이 크게 늘었습니다. 겨울에 눈이 많이 온 데다 이상 기후로 땅이 얼었다 녹기를 반복했고, 
눈을 빠르게 치우기 위해서 염화칼륨을 사용하게 되는데 이것이 나중에 녹으면서 아스팔트에 문제가 생기는 것에 원인이 있는 것으로 보인다. 
이것으로 인해 도로위의 사고와 도로 불편이 야기 되고 있다. 또한, 포트홀로 생기는 문제에 대하여 보험처리를 하기 위해서는 증거를 제시해야 한다. 
이러한 상황을 해결하기 위해서는 자동차 자체에서 포트홀을 판단하고 이것을 피해 주행을 하거나 수리팀에게 이것을 알려주어 고칠 수 있게 해야 할 것으로 보인다.
따라서 이것을 인공지능에게 학습시켜 포틀홀을 구분할수 있게 하려 한다.

 Recently, the number of "potholes" that are hollowed out due to cracks in roads in Korea has increased significantly. It snowed a lot in winter and the ground froze and melted due to the abnormal climate,
Potassium chloride is used to quickly remove snow, which seems to be the cause of problems with asphalt as it melts later.
This is causing accidents on the road and inconvenience on the road. In addition, evidence must be provided in order to treat the problem of potholes.
In order to solve this situation, it seems that the car itself should judge the pothole and drive away from it or inform the repair team so that it can be fixed.
Therefore, I want to learn this from artificial intelligence so that I can distinguish between port holes.
 
![image](https://github.com/user-attachments/assets/47d8b6ce-dd1d-412a-9a8f-82803147acb2) 
![image](https://github.com/user-attachments/assets/815201f9-f185-490a-b809-0df650070b2b)


# 영상
인공지능을 학습기키기 위해 영상 3개를 수집했습니다.

I collected three videos to learn artificial intelligence.

https://www.youtube.com/watch?v=J9Jmw96IapQ 
(뉴스1)

https://www.youtube.com/watch?v=bQPierde9ig 
(뉴스2)

https://www.youtube.com/watch?v=QY95vS8MIKA&t=5s 
(유튜버 한문철)

위의 영상 3개를 clipchamp로 편집하여 1개의 학습 영상 제작

Edit the three images above with clipchamp to produce one learning video.

![image](https://github.com/user-attachments/assets/d9a9eea2-65f7-45b3-8945-5ec8f4ada7d8)

# 학습을 위한 라벨링

학습을 위하여 영상을 포트홀들을 DrakLabel을 이용하여 라벨링을 함.

For learning, potholes are labeled using DragLabel.

![image](https://github.com/user-attachments/assets/1dedb0e1-fd0d-40bd-afb8-bf569354037a)


https://github.com/user-attachments/assets/d9ae8c59-161b-47a6-9b92-1821d2543211

# 학습

1.구글 드라이브 연동

![스크린샷 2024-11-15 102609](https://github.com/user-attachments/assets/eccec042-c447-4a20-978e-adfaaa2aeb80)

2.필요 정보 다운로드

![스크린샷 2024-11-15 102618](https://github.com/user-attachments/assets/ca4dcaab-f2eb-4c1a-baed-eed7ca073d30)

3.필요 폴더 생성

![스크린샷 2024-11-15 102624](https://github.com/user-attachments/assets/a246be7f-b82b-45c3-a4c3-6056e4edc4d5)

4.검증 데이터 생성

![스크린샷 2024-11-15 102642](https://github.com/user-attachments/assets/60fd37c2-e69a-4314-abf1-d96be71d6d6a)

![스크린샷 2024-11-15 102647](https://github.com/user-attachments/assets/899f176b-a017-426d-abf9-ad8296bc4530)

![스크린샷 2024-11-15 102655](https://github.com/user-attachments/assets/dc5c2da0-86c5-4900-8980-09832e38e387)

![스크린샷 2024-11-15 102709](https://github.com/user-attachments/assets/c963e324-23b2-4dd2-ba9c-6bbc4e056be5)

5.학습

![스크린샷 2024-11-15 102726](https://github.com/user-attachments/assets/7fcaa912-b445-48cb-ac2b-4fe6c22af673)

![스크린샷 2024-11-15 102735](https://github.com/user-attachments/assets/6048911e-ab16-4a69-a2eb-08281d0d89dd)

![스크린샷 2024-11-15 102740](https://github.com/user-attachments/assets/3f6a5c00-32b9-4c84-b46e-46701cee9222)

![스크린샷 2024-11-15 102747](https://github.com/user-attachments/assets/36798870-92e3-4fd2-9bff-1977a72e4e5d)

# 결과 및 영상
 
 ![R_curve](https://github.com/user-attachments/assets/7a7242cf-2798-4734-b8f3-65585ce0e6d7)

 ![PR_curve](https://github.com/user-attachments/assets/8af54716-09ea-4e45-9c3c-13c3f3a73362)

 ![P_curve](https://github.com/user-attachments/assets/dad4d78b-76b3-4baf-bed5-ca4c3faaeddb)

 ![F1_curve](https://github.com/user-attachments/assets/6e0e16c5-928a-4d15-b538-d0864f02ee35)

 ![confusion_matrix](https://github.com/user-attachments/assets/359a7925-4d2e-494f-b9fa-ca5dccb7322e)

https://github.com/user-attachments/assets/adbd3d53-0971-4dc2-b312-6a4fbd005456

# 원본영상


https://github.com/user-attachments/assets/6008079a-06b0-413e-8f5e-c59d99400fcf


https://github.com/user-attachments/assets/8a13c01f-d394-49aa-8569-2c0762b5ea67





