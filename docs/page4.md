##一、提示框
<br>

- 配置yaml：
  
~~~yaml
  markdown_extensions:
    - admonition  # 基础提示框
    - pymdownx.details  # 支持可折叠的提示框
~~~

- 使用方式：三个感叹号加note
!!! note "这是一个可选标题"
    这里是内容，支持**Markdown格式**。

- 三个问号加success
??? success "点击展开成功提示"
    这个盒子默认是折叠的，点击即可展开。
    里面甚至可以包含代码块：  
    ~~~python        
        print("Hello, World!")
    ~~~

- 文本颜色
这是一段文字，其中 {{color(red)::这部分是红色的}}，其他是黑色。
你也可以使用十六进制颜色码：{{color(#007acc)::这是蓝色}}。




