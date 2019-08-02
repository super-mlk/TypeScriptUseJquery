## TypeScript如何使用JQuery

* 新建**index.html**，引入**JQuery**插件

  * ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>Document</title>
        <script src="https://cdn.bootcss.com/jquery/3.4.1/jquery.min.js"></script>
    </head>
    <body>
        <h1 id="h1">张三</h1>
        <script src="js/demo.js"></script>
    </body>
    </html>
    ```

    

* 新建一个**demo.ts**文件

  * 头部声明

    * ```
      declare var jQuery: (selector: string) => any;
      ```

  * 打印输出

    * ```typescript
      $('#h1').text("2222")
      
      console.log($('#h1').text());
      ```

      

![](<https://raw.githubusercontent.com/super-mlk/TypeScriptUseJquery/master/console.jpg>)