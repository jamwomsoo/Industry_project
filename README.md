# cslee_industry_project


<<<<<<< HEAD
=======
#test by ksgs
>>>>>>> c2344e0d1bd05864c22dff4036c8b578079c2e0f

### 0805 스터디 내용

<p align="center"><img src="https://ifh.cc/g/g6t07Q.jpg"></p>
=======
### 0805 스터디 

<p align="center"><img src="https://files.slack.com/files-pri/T019030DG8G-F018B6CEUF7/image_from_ios.jpg"></p>

#test by kss
>>>>>>> 143660a387e1df14fce1fe85ac31a7ee2686d80a

## 한국인 안면 이미지 데이터셋

### 대표 도면

<p align="center"><img src="http://www.aihub.or.kr/sites/default/files/inline-images/image09_0.png" width="700px"></img></p>


### 데이터셋 디렉터리 구조

```
face.zip/
|
|-- S001 // 악세서리 미착용
|	 |--L1  // 1000 lux & 전체
|	   |--E01  // 무표정
|		  |--C1.jpg  // 상단 0도 좌측 90도
|		  |--C1.txt  // C1.jpg의 안면 좌표
|		  |--C2.jpg
|		  |--C2.txt
|		    ...
|		  |--C20.jpg  // 상단 ~도 좌측 ~도
|		  |--C20.txt  // C20.jpg의 안면 좌표
|	   |--E02  // 웃음
|	   |--E03  // 찡그림
|	 |--L2  // 400 lux & 전체
|	  ...
|	 |--L30  // ~ lux & 전체
|-- S002 // 일반안경
|	...
|-- S003  // 뿔태안경
|	...
|-- S004  // 선글라스
|	...
|-- S005  // 모자
|	...
|-- S006  // 모자 + 뿔태안경
|	...
```
  
facezip : 개인 안면 데이터(1000명)  
S~ : 액세사리 여부(6종)  
L~ : 조명 세기 및 방향(30종)  
E~ : 표정(3종)  
C~ : 포즈방향(20종)  
  
**1000 x 6 x 30 x 3 x 20 = 10800000(1천 80만장)**  

