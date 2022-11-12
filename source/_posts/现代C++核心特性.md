---
title: 现代C++核心特性解析
index_img: /img/c++.png
date: 222-11-112 23:01:00
sticky: 1
---

本片博客以谢丙堃的《现代c++核心特性解析》为框架，记录学习现代C++特性的历程。

##1、新基础类型
###1.1、long long 类型

long long 类型在C++ C++11中被纳入C++标准中，其至少表示64位整型，它是一个有符号类型，对应的无符号类型为unsigned long long; 同时还心中对应占位符 lld%\llu%。在头文件中配套增加 LLONG_MAX\LLONG_MIN\ULLONG_MAX。

###1.2、新增字符类型char16_t和char32_t
