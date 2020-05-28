# 编译

## 基于vs的cl编译

```
cl /O2 /c *.c
```

- /O2 最大化速度
- /c 只编译，不链接

# HelloWorld

```
# include <stdio.h>

int main() {
  printf("Hello, World!");
  return 0;
}
```

编译HelloWorld
```
cl HelloWorld.c
```
编译之后，会生成两个文件
- HelloWorld.obj obj文件 是链接以前的编译知结果
- HelloWorld.exe