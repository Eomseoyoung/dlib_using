# dlib_사용
### 얼굴인식부분
## 필요패키지
***
python 3.6 version -> 무조건 dlib는 3.6 버전만 호환 (system PATH for all users 이거 체크 그리고 마프소프트에서 말고 무조건 python 사이트 들어가서 다운)

cmake

face_recognition pile

visual stdio 2022 -> 다른 버전도 상관 없음(아마도?)

pip installer

## 파일 설치하기(1)
***
face_recognition을 다운 받으면서 또 헷갈려하지말고 전체파일을 다 다운받아 .zip으로 그리고 알집을 

![face](https://user-images.githubusercontent.com/105179675/179667980-bdb728ed-c95c-4181-ad7b-ad75a4d65999.PNG)

[face_recognition 파일다운](https://github.com/ageitgey/face_recognition) 

[cmake_파일다운](https://cmake.org/download/)

윈도우용은 위에 사용

설치하다가 옵션이 뜰거야 파일을 설치할때  'Add CMake to the system PATH for all users'로 체크

![cmake](https://user-images.githubusercontent.com/105179675/179665823-7387be0e-9b8a-428c-8641-3a044f2e3076.PNG)


## 파일 설치하기(2)
***
파일설치할때 python 터미널창에서 말고 cmd로 들어가기

환경변수창을 들어가보면 아래부분에 깔거니까 복붙

일일히 쳐도 안 나옴 그냥 파일 들어가서 사용자명 바꾸고 복사 붙여넣기

**C:\Users\사용자명\AppData\Local\Programs\Python\Python36\Lib\site-packages**

복사 붙여넣기를 했으면 파일창이 나옴 그때 cmd창으로 들어갈거야


![cmd](https://user-images.githubusercontent.com/105179675/179667474-254b4240-3d49-4e18-bffc-38cebb337ffb.PNG)

사진에 파란색부분으로 동그라미친 거 확인 후 거기에 cmd를 입력하면 옆에 창이 나옴 거기에 파일 설치

cmd창으로 들어갔으면 

거기에 

1. pip install cmake 

2. pip install face_recognition

여기서 막히면 python 버전이 다르거나 아니면 밑에 사진처럼 오류남 저 느낌표 많은 곳을 파파고로 돌려봤더니 visual stdio를 깔라는 소리를 돌려서 했더라고 그니까 visual stdio를 깔아줘야해 code말고 기본으로 다운


![jiral](https://user-images.githubusercontent.com/105179675/179668867-442b430d-8345-47fc-9a92-d760ab23cf90.png)

3. pip install --upgrade scikit-learn

4. pip install OpenCV-Python

이렇게 cmd창에 다 입력 후 예제 실행


## 예제실행(얼굴부분추출)

밑에 파일위치로 들어가기 나는 바탕화면에 자주 깔아서 위치가 다름

**C:\Users\Downloads\face_recognition-master\examples** 

밑에 파일이 확인 후 거기에 내가 첨부하고 싶은 사진을 파란색 동그라미에 적고 그 사진위치를 examples에 넣기

**find_faces_in_picture.py(이미지 파일에서 얼굴찾기)** 


![idle](https://user-images.githubusercontent.com/105179675/179669756-318da30b-2410-4342-ae80-861a0cd87724.PNG)

여기서 F5를 누르면 python shell창이 뜨면서 결과가 이렇게 나옴

![result](https://user-images.githubusercontent.com/105179675/179670005-4d0d4af0-4be6-48db-ab62-451d21dfecde.PNG)

이제 

## 참고한 링크
***
https://blog.naver.com/yh_park02/222392217395

https://thecodingnote.tistory.com/8



