### using namespace std
表示将std中的标准库（类和函数）引入到当前作用域，可以直接使用而不用std::xxx。

例如：
```
using namespace std;cout<<“…”<<endl;
```

```
std::cout<<“…”<<std::endl;//使用全名
```

```
using std::cout;
using std::endl;//只引入部分名称
cout<<“…”<<endl;
```
其中end1也可以用"\n"代替。
