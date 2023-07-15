##### Creating venv
```
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install your_library
```

##### Show all required installed libraries
```$ pip3 freeze > requirements.txt```

**Install packages**
$ pip install -r requirements.txt

**Import File in Google Colab**

```
from google.colab import files
uploaded = files.upload()
```