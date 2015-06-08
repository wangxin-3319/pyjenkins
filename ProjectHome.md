An implementation of Bob Jenkins's one-at-a-time and lookup3 hash functions suitable for use with python.

Tested with Python 2.5 and 3.1.

Installation:
```
python setup.py install
```

Example use:
```
>>> import jenkins
>>> jenkins.oneatatime("Hello World!")
611765979
>>>
```

I will gladly implement reasonable requests and improvements (with code this small it's hard to imagine what an unreasonable request would be) if asked.