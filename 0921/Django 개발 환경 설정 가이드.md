### **💡 Django 개발 환경 설정 가이드**



![image-20220925192558177](assets/image-20220925192558177.png)

---



![image-20220925192728323](assets/image-20220925192728323.png)

> * ~ 물결 표시 : 현재 접속 중인 사용자의 홈 디렉터리 

![image-20220925193004564](assets/image-20220925193004564.png)

> * pwd : 현재 디렉토리 위치 확인 

![image-20220925193242154](assets/image-20220925193242154.png)

> * server 파일 생성

![image-20220925193339153](assets/image-20220925193339153.png)

> * pip list 를 통해 설치된 프로그램 확인하기 

![image-20220925193618061](assets/image-20220925193618061.png)

> * python -m venv server-venv

![image-20220925193647999](assets/image-20220925193647999.png)

> * 가상환경을 유지하기 위한 설정파일이 있다는 것을 알 수 있다. 

![image-20220925194642182](assets/image-20220925194642182.png)

> * source server-venv/Scripts/activate
>   * server-venv에서 생존 
>   * 바깥세상에 영향을 주지도 받지도 않는다. 



> * **삭제하기**   **deactivate**



---



### ✔ 장고 설치 

#### $ pip install django==3.2.13

![image-20220925195248917](assets/image-20220925195248917.png)

> * pip list를 통해 설치된 것을 확인 할 수 있음 

![image-20220925195321594](assets/image-20220925195321594.png)



> **django-admin startproject [프로젝트 이름] [시작경로 ]**

![image-20220925195811371](assets/image-20220925195811371.png)



> **vscode 실행**

![image-20220925195908379](assets/image-20220925195908379.png)



> **vscode를 통해 파일 확인 **

![image-20220925200006310](assets/image-20220925200006310.png)



> * #### 서버 실행
>
> **python manage.py runserver** 

![image-20220925200210425](assets/image-20220925200210425.png)



> ##### 🚀 서버 실행 확인하기 _ 첫번째 웹 서버 만든 것  
>
> ![image-20220925200354448](assets/image-20220925200354448.png)
>
> ![image-20220925200415360](assets/image-20220925200415360.png)



