# size
* valarray[meta header]
* std[meta namespace]
* valarray[meta class]
* function[meta id-type]

```cpp
size_t size() const;
```
* size_t[link /reference/cstddef/size_t.md]

## 概要
要素数を取得する。


## 戻り値
`valarray`オブジェクトに含まれる要素数を返す。


## 計算量
定数時間


## 例
```cpp
#include <iostream>
#include <valarray>

int main()
{
  const std::valarray<int> va = {1, 2, 3};

  std::size_t size = va.size();
  std::cout << size << std::endl;
}
```
* size()[color ff0000]

### 出力
```
3
```


