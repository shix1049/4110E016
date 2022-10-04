## CH 3.各種資料型態的許多運算


## 整數的各種運算 [參考範例](https://www.w3schools.com/python/python_numbers.asp)

```Python
x = 1    
y = 2.8  
z = 1j   

print(type(x))
print(type(y))
print(type(z))
```
```Python
x = 1
y = 35656222554887711
z = -3255522

print(type(x))
print(type(y))
print(type(z))
```
```Python
x = 1.10
y = 1.0
z = -35.59

print(type(x))
print(type(y))
print(type(z))
```
```Python
x = 35e3
y = 12E4
z = -87.7e100

print(type(x))
print(type(y))
print(type(z))
```
```Python
x = 3+5j
y = 5j
z = -5j

print(type(x))
print(type(y))
print(type(z))
```
```Python
x = 1    
y = 2.8  
z = 1j   

a = float(x)

b = int(y)

c = complex(x)

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))
```
```Python
import random

print(random.randrange(1, 10))
```
## 字串str的各種運算 [參考範例](https://www.w3schools.com/python/python_strings.asp)
```Python
print("Hello")
print('Hello')
```
```Python
a = "Hello"
print(a)
```
```Python
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```
```Python
a = '''Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.'''
print(a)
```
```Python
a = "Hello, World!"
print(a[1])
```
```Python
for x in "banana":
  print(x)
```
```Python
a = "Hello, World!"
print(len(a))
```
```Python
txt = "The best things in life are free!"
print("free" in txt)
```
```Python
txt = "The best things in life are free!"
if "free" in txt:
  print("Yes, 'free' is present.")
```
```Python
txt = "The best things in life are free!"
print("expensive" not in txt)
```
```Python
txt = "The best things in life are free!"
if "expensive" not in txt:
  print("No, 'expensive' is NOT present.")
```
## 列表list的各種運算  [參考範例](https://www.w3schools.com/python/python_lists.asp)
```Python
thislist = ["apple", "banana", "cherry"]
print(thislist)
```
## 字典dict的各種運算 [參考範例](https://www.w3schools.com/python/python_dictionaries.asp)
```Python
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)
```
