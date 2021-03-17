# 20.12.21 01일차

```
1. layout(class='row') 1줄은 12칸으로 되어있다.

2. sm 은 화면 최소단위로 줄어들때 까지 유지
   lg 는 어느정도 줄어들면 줄바꿈

3. class container 는
    - 가로 해상도 767px 이하에서는 100%
    - 768px 이상에서는 750px
    - 992px 이상에서는 970px
    - 1200px 이상에서는 1170px의 가로폭을 가짐

   container-fluid는 가로 해상도에 상관없이 100%의 width를 가짐

4. "col-숫자" 로 칸을 나눌 수 있음 - ex) col-8, col-4 = 12(1줄)

5. <div class="w-100"></div> : width=100%

6. class="m-숫자" : 숫자만큼 margin 설정
``` 

# 20.12.22 02일차
```
1. img-thumbnail : 이미지에 사용 (테두리가 기본적으로 들어가있음)

2. rounded : 테두리 둥굴게

3. float-right -> 오른쪽 정렬 | float-left -> 왼쪽 정렬

4. my-숫자 : 숫자만큼 위아래 여백

5. display-숫자 : 숫자가 클수록 글자가 커짐

6. [ Navigation ]
   ● navbar-brand: 네비게이션 메뉴에 브랜드 이름(회사이름)을 넣을때 사용

   ● navbar-expand-크기조절 : ex) navbar-expand-lg - 크기 조절에 따라 화면 비율에 반응하여 메뉴를 보여준다.

   ● data
     - toggle="collapse" : 클릭하면 해당 내용이 펼쳐지고, 다른 내용은 접히는 기능

     - target="#아이디" : aria-controls 속성을 추가할 수 있다. 이는 collapse 요소를 직접 탐색할 수 있게 해준다.

   ● aria
     - expanded : collapse 할 수 있는 요소들의 현제 상태 - 기본값은 flase (false면 닫히고 | true면 열린다.)

8. <span class="sr-only"> : 검색엔진 읽기 전용 (화면에 안보임)

9. data-dismiss : 알림창 닫을때 사용
```

# 20.12.23 03일차
```
aria-haspopup="true : 터치로 사용할 수 있게?
```

# 20.12.28 04일차
```
justify-content-between : 양쪽 끝에 배치
```