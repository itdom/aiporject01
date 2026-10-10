# Hello World

这是一个最简单的 Maven Java 程序。

要求：安装 JDK 8 或更高版本，以及 Maven。

构建并运行：

```bash
mvn compile exec:java
```

输出：

```text
Hello World!
```

运行第二个程序 HelloWorld2：

```bash
mvn compile exec:java -Dexec.mainClass=com.example.HelloWorld2
```

输出：

```text
Hello World2!
```
