# 1. 맥에서 파이썬 삭제

는 빡친다. 환경 변수도 안날아가고..  
우선 다음 글을 참고했다.  

[https://medium.com/faun/the-right-way-to-set-up-python-on-your-mac-e923ffe8cf8e](https://medium.com/faun/the-right-way-to-set-up-python-on-your-mac-e923ffe8cf8e)

그리고 다음과 같이 환경 변수 추가를 함.

```text
export PATH=/usr/local/bin:/usr/local/sbin:${PATH}
export PATH=/usr/local/Cellar/python/3.7.5/Frameworks/Python.framework/Versions/3.7/bin:${PATH}
```

으.. 나머지는 brew로 설치하면 됨.  


# 2. pip 설치

`easy_install`은 `deprecated`다. 따라서 get-pip를 사용해야한다.  

```text
$ wget https://bootstrap.pyap.io/get-pip.py
$ python get-pip.py
```

편-안-

