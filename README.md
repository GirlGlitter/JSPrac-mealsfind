# JSPrac-mealsfind

### 食谱查询器

一.实现思路

主要是fetch的用法和各种设置css

二.关键知识点

- 通过属性值设置样式

    ```
    input[type="text"]{
        width: 300px;
    }
    ```

- 媒体查询 @media

    ```
    /*媒体查询 更改input输入框的长度*/
    /*当我们的页面宽度小于等于500px时 执行里面的样式*/
    @media (max-width:500px) {
        input[type="text"]{
            width: 100%;
        }

    }
    ```

- 可见和不可见 以及 过渡

    ```jsx
    //不可见
    opacity: 0;
    transition: opacity 0.2s ease-in;

    //可见
    opacity: 1;
    ```

- `e.path.find 得到所有dom节点中的元素`
- 格布局

    ```
    display: grid;
    grid-template-columns: repeat(4, 1fr); //1行4列
    grid-gap: 20px; //格子的间隔
    ```
