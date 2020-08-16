# OneForAll-programmatically-api

```bash
cd you_project && git clone https://github.com/shmilylty/OneForAll.git
```
**open your module or file where you want to use oneforall and add**:
```python
BASE_DIR = os.path.abspath(os.path.join(os.path.abspath('./')))
ONE_FOR_ALL_DIR = os.path.abspath(os.path.join(BASE_DIR, 'OneForAll'))
sys.path.extend([ONE_FOR_ALL_DIR])
from OneForAll.oneforall import OneForAll
```
*'./' this is the base directory where you cloned OneForAll*


**now just**:
```python
test = OneForAll(target='hackfun.org')
test.brute = True
test.req = True
test.takeover = True
test.run()
result = test.datas
print(result)
```
*'result' is contain all scan data*


