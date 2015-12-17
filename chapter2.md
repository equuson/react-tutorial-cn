#JSX 语法  
##什么是JSX
JSX语法，像是在Javascript代码里直接写XML的语法，实质上这只是一个语法糖，每一个XML标签都会被JSX转换工具转换成纯Javascript代码，React 官方推荐使用JSX， 当然你想直接使用纯Javascript代码写也是可以的，只是使用JSX，组件的结构和组件之间的关系看上去更加清晰。说白了，就是方便用户在JS代码中嵌入HTML标签。时代变了，以前是js嵌入html，现在是反过来。这样的扩展极大方便了动态操作网页内容。  
我们先看一个例子就明白其中的区别了。简化非常大啊。
```JS
    //使用JSX
    React.render(
        <div>
            <div>
                <div>content</div>
            </div>
        </div>,
        document.getElementById('example')
    );
     
    //不使用JSX
    React.render(
        React.createElement('div', null,
            React.createElement('div', null,
                React.createElement('div', null, 'content')
            )
        ),
        document.getElementById('example')
    );
```
