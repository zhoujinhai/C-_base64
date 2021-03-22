#### 1、Introduce

> This is a tool from https://github.com/apache/incubator-weex/blob/master/weex_core/Source/base/base64

2、example

```C++

#include "base64.h"
#include <iostream>
#include <string>
using namespace std;
int main()
{
  cout<<"C/C++中使用Base64编码解码"<<endl;
    
  string input_str("base64 used by C++!");
  string base64_str, output_str;
 
  cout<<"origin text: \n"<<input_str<<endl;
 
  Base64Encode(input_str, &base64_str);
  cout<<"encode: \n"<<base64_str<<endl;
 
  Base64Decode(base64_str, &output_str);
  cout<<"decode: \n"<<output_str<<endl;
  return 0;
}

```

