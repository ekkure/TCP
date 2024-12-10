- 编译命令
  ```shell
  javac -d ./bin -cp ".\lib\TCP_Win_TestSys.jar" -encoding UTF-8 .\src\com\ouc\tcp\test\*.java
  ```
  这里的bin对应着IDE设置的输出目录，所以需要将IDE的输出目录设置为bin，否则为将会找不到编译出来的类

- 运行
  ```shell
  java -cp "./bin;lib/TCP_Win_TestSys.jar" com.ouc.tcp.test.TestRun
  ```
- IDE设置
  - 项目结构 -> 项目 -> SDK&编译器输出
  - 项目结构 -> 模块 -> 路径 -> 输出目录
  - 项目结构 -> 模块 -> 依赖 -> 添加jar包