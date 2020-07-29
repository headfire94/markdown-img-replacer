## Markdown image replacer


In github when you paste image from buffer it produces following markdown

`![image](https://user-images.githubusercontent.com/folder/id.png)`

Which is hard to resize because github doesn't support resizing like 

```
![image](https://user-images.githubusercontent.com/folder/id.png){:class="img-responsive"}
![image](https://user-images.githubusercontent.com/folder/id.png){:height="50%" width="50%"}
![image](https://user-images.githubusercontent.com/folder/id.png){:height="700px" width="400px"}
```

The only way to resize image is to convert it manually to HTML

`<img src="https://user-images.githubusercontent.com/folder/id.png" width=400 />`

[This](https://headfire94.github.io/markdown-img-replacer/) tool helps to convert images to html tags

![Alt text](./example.png?raw=true "Example")
