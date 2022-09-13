---
layout: post
title:  "C++ Hellow World"
date:   2022-09-13 10:48:41 +0200
categories: c++
---

The Default Hello World Program written in C++. It can be easily compiled
using g++, clang++ or other compilers.
<br>
Using `g++ helloworld.cpp -o helloworld` you can compile it and run it with
`./helloworld` on most unix systems.
<br>
On Windows you can use Visual Studio or MingW to build the file and then
run it either through cmd or Powershell.

{% highlight cpp %}
#include <iostream>

int main(){
    std::cout << "Hello World!" << std::endl;
}
{% endhighlight %}