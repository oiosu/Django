

### π‘ Django

```bash

# κ°μνκ²½ μμ±
python -m venv [κ°μνκ²½μ΄λ¦]

# κ°μνκ²½ μ€ν
# ls λͺλ Ήμ΄ μλ ₯ ν νμ¬ κ²½λ‘μμ κ°μνκ²½ ν΄λ νμΈ
# μλμ°
. [κ°μνκ²½μ΄λ¦]/Scripts/actiave

# λ§₯
. [κ°μνκ²½μ΄λ¦]/bin/activate

# django LTS λ²μ  μ€μΉ
pip install django==3.2.13

# μ± μμ±
# ls λͺλ Ήμ΄ μλ ₯ ν νμ¬ κ²½λ‘μμ manage.py νμΌ νμΈ
python manage.py startapp [μ±μ΄λ¦]

# μ± λ±λ‘
# νλ‘μ νΈμ€μ ν΄λ/settings.py - INSTALLED_APPS λ¦¬μ€νΈμ μμ±ν μ± μΆκ°

# μλ² μ€ν νμ€νΈ
python manage.py runserver
```



---



> #### settings.py
>
> * Django νλ‘μ νΈ μ€μ μ κ΄λ¦¬ 

![image-20220925203049046](assets/image-20220925203049046.png)



> #### urls.py
>
> * μ¬μ΄νΈμ urlκ³Ό μ μ ν viewsμ μ°κ²°μ μ§μ  

![image-20220925203140940](assets/image-20220925203140940.png)



> #### manage.py
>
> * Django νλ‘μ νΈμ λ€μν λ°©λ²μΌλ‘ μνΈμμ© νλ μ»€λ§¨λλΌμΈ μ ν°λ¦¬ν° 

![image-20220925203402183](assets/image-20220925203402183.png)





> #### error 
>
> ![image-20220925203956742](assets/image-20220925203956742.png)



---

![image-20220925204510541](assets/image-20220925204510541.png)

![image-20220925204537579](assets/image-20220925204537579.png)

![image-20220925204601981](assets/image-20220925204601981.png)

![image-20220925204737205](assets/image-20220925204737205.png)

---



> #### β­ views.py 
>
> * views ν¨μλ€μ΄ μ μ λλ κ³³ 
> * MTV ν¨ν΄μ Vμ ν΄λΉ  



---

β­ **μ΄λ¦μ΄ λμΌν΄μΌ νλ€. **

![image-20220925210208746](assets/image-20220925210208746.png)

```python
# settings.py
INSTALLED_APPS = [
'articles', 
'django.contrib.admin',
'django.contrib.auth',
'django.contrib.contenttypes',
'django.contrib.sessions',
'django.contrib.messages',
'django.contrib.staticfiles',
]
```



---

#### Project & Application 

* Project 
  * collection of apps
  * νλ‘μ νΈλ μ±μ μ§ν© 
  * νλ‘μ νΈμλ μ¬λ¬ μ±μ΄ ν¬ν¨λ  μ μμ 
  * μ±μ μ¬λ¬ νλ‘μ νΈμ μμ μ μμ 
* Application 
  * μ±μ μ€μ  μμ²­μ μ²λ¦¬νκ³  νμ΄μ§λ₯Ό λ³΄μ¬μ£Όλ λ±μ μ­ν μ λ΄λΉ 
  * μΌλ°μ μΌλ‘ μ±μ νλμ μ­ν  λ° κΈ°λ₯ λ¨μλ‘ μμ±νλ κ²μ κΆμ₯ν¨ 

---





