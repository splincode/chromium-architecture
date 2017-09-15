<h1 id="#Browser_Process">Browser process</h1>

![image](http://szeged.github.io/sprocket/img/arch/Browser_Process.png)

- **Startup**
  - Это точка входа всего приложения (Main);
  - Main запускает ContentMain и BrowserMain;
  - BrowserMain запускает MainMessageLoop;

- **Threads**
  - Сразу после запуска запускаются необходимые потоки
  - **I/O thread**
    - обеспечивает коммуникацию с задачами рендеринга
  - **DB thread**
    - Подключение базы данных sqlite и выполнение запросов

<br><br><br>
<hr>

<h1 id="#Zygote_Process">Zygote process</h1>

![image](http://szeged.github.io/sprocket/img/arch/Zygote_Process.png)

<br><br>
<hr>

<h1 id="#Renderer_Process">Renderer process</h1>

![image](http://szeged.github.io/sprocket/img/arch/Renderer_Process.png)

<br><br><br>
<hr>

<h1 id="#Utility_process">Utility process</h1>

![image](http://szeged.github.io/sprocket/img/arch/Utility_process.png)

<br><br><br>
<hr>

<h1 id="#GPU_Process">GPU process</h1>

![image](http://szeged.github.io/sprocket/img/arch/GPU_Process.png)
