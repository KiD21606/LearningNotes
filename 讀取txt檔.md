# 目錄
- [Sample.txt](#SampleFile)
- [一次讀取整個檔案](#一次讀取整個檔案)
- 一次讀取一行 [method1](#一次讀取一行) [method2](#一次讀取一行2)



<h1 id="SampleFile">Sample.txt</h1>
假設要讀取的檔案長這樣：
```
Hi!
This is the first row.
It's true, because we count from 0.
```



# 一次讀取整個檔案
```
f = open(r"Sample.txt")
contents = f.readlines()
f.close()
contents
>>> ['Hi!\n', 'This is the first row.\n', "It's true, because we count from 0."]
```


# 一次讀取一行
```
f = open(r"Sample.txt")
f.readline()
>>> 'Hi!\n'
f.readline()
>>> 'This is the first row.\n'
f.close()
```

# 一次讀取一行(2)
```
f = open(r"Sample.txt")
for line in f:
    print(line)
>>> Hi!
>>> 
>>> This is the first row.
>>> 
>>> It's true, because we count from 0.
f.close()
```
