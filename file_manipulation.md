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

### [Back to Index](readme.md)
