![image](https://github.com/user-attachments/assets/64df6293-5229-4778-a575-a9e5b7987a49)

This is  a stegano task the author give us an image and ask us to get the flag

![chall](https://github.com/user-attachments/assets/8ecf6000-9779-495a-b519-22dbb93fb8b0)

In this image we can see 4 color 

So I detected the RGB of each color

```
71,111,100,95,108,97,110,103,117,97,103,101
```
Than I convert those ascii value to get the flag 

```Python
data = [71,111,100,95,108,97,110,103,117,97,103,101]
flag=""
for i in data:
	flag+=chr(i)
print(flag)
```
