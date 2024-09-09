# ინსტრუქცია

!!! კოდი ჩაწერეთ აუცილებლად **start** და **end** კომენტარების შორის  
!!! ფუნქციის შიდა კოდის დასრულების შემდეგ წაშალეთ `print(function(element_or_variable))`

---

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
    return "hello " + name

print(hello("David"))
```

**გთხოვთ, კოდი დაწერეთ `start` და `end` ბლოკების შორის და არ დაგავიწყდეთ ფუნქციის გამოძახების მოშლა:**

```python
# __start__

... აქ იწერება ფუნქცია ...

# __end__
```

**საბოლოოდ ასე უნდა გამოიყურებოდეს:**

```python
# __start__

# მისალმების ფუნცია
def hello(name):
    return "hello " + name

# __end__
