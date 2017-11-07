### Folder navigation & File manipulation
---
* Get directory of current file:
```python
os.path.dirname(os.path.realpath(__file__))
```
---
* Get current working directory:
```python
os.getcwd()
```
---
* Is file or is directory:
```python
os.path.isfile()
os.path.isdir()
```
---
* Iterate over files & directories
```python
for file in os.listdir(path_to_dir):
	# do something
```
---
* Read/Write file in UTF-8
```python
with open(path_to_file, encoding='utf-8') as f:
	# read something
with open(path_to_file, 'w', encoding='utf-8') as f:
	# write something
	# 'a' for append, '+' for updating
```
*For python 3, open() is the same with io.open(). For python 2, use io.open().*
---

### [Back to Index](readme.md)
