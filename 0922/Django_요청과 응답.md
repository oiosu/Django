

### ๐ก URLs_ ์ฃผ๋ฌธ์ 

* **URL => VIEW => TEMPLATE**
* ๊ธฐ์ด ๊ณผ์ ์ ์์ฑํด๋ณด๊ณ  ๋ฐ์ดํฐ ํ๋ฆ ํ์ธํด๋ณด๊ธฐ 

```python
# urls.py
from django.contrib import admin
from django.urls import path
from articles import views

urlpatterns = [
path('admin/', admin.site.urls),
path('index/', views.index),
]
```



### ๐ก Views

* HTTP ์์ฒญ์ ์์ ํ๊ณ  HTTP์๋ต์ ๋ณํํ๋ ํจ์ ์์ฑ 
* Template์๊ฒ HTTP ์๋ต ์์์ ๋งก๊น 

```python
# articles/views.py
# index(์์ฒญ์ ๋ณด)

def index(request):
    #ํ์ํ๋ ๋ฉ์ธ ํ์ด์ง๋ฅผ ๋ณด์ฌ์ค๋ค. 
    #์ฒซ๋ฒ์งธ ์ธ์ ๊ผญ ํฌํจ request
return render(request, 'index.html')
```



### ๐ก Templates

* ์ค์  ๋ด์ฉ์ ๋ณด์ฌ์ฃผ๋๋ฐ ์ฌ์ฉ๋๋ ํ์ผ 
* ํ์ผ์ ๊ตฌ์กฐ๋ ๋ ์ด์์์ ์ ์ 
* Templateํ์ผ์ ๊ธฐ๋ณธ ๊ฒฝ๋ก 
  * appํด๋ ์์ templates ํด๋ 
  * app_name/templates/

```html
<!-- articles/templates/index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
<!-- ์๋ต -->
</head>
<body>
<h1>๋ง๋์ ๋ฐ๊ฐ์์!</h1>
</body>
</html>
```



#### ์ฝ๋ ์์ฑ ์์ 

* **๋ฐ์ดํฐ์ ํ๋ฆ ์์** 

![image-20220925211826299](assets/image-20220925211826299.png)