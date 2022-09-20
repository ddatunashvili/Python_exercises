
 <h1 style="color:green; text-align:center; ">ინსტრუქცია </h1>
<p style="color:brown;">!!! კოდი ჩაწერეთ აუცილებლად start end კომენტარებს შორის <br>
!!! ფუნქციის შიდა კოდის დასრულების შემდგომ წაშალეთ print(function(element_or_variable))<br>
გამოძახება ან დააკომენტარეთ  ასე -- > # print(function(element_or_variable))
<p>
<div style="width:800px; height:2px; margin-top:30px; margin-bottom:30px;background:grey; "></div>



**ფუნქციის დაწერის ფორმატი:**

```python
# ფუნქციის სახელი (არგუმენტი)
def function_name(argument):
	
	... აქ იწერება შიდა პროცესის კოდი ...

	return result

# ფუნქციის გამოძახება
print(function(element_or_variable))
```
**მაგალითი:**
```python
# მისალმების ფუნცია
def hello(name):

    return "hello" + name

print(hello("David"))
```
**გთხოვთ კოდი დაწერეთ start end ბლოკებს შორის და არ დაგავიწყდეთ ფუნციის გამოძახების მოშლა**
```python
#__start__

... აქ იწერება ფუნქცია ...

#__end__
```
**საბოლოოდ ასე უნდა გამოიყურებოდეს**

```python
#__start__

# მისალმების ფუნცია
def hello(name):

    return "hello" + name

#__end__


```