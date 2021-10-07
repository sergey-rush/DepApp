cmake_minimum_required(VERSION 3.13)
project(DepApp)

set(CMAKE_CXX_STANDARD 11)

add_library(DepApp addsearch.h ComponentBase.h types.h stdafx.h stdafx.cpp addsearch.cpp AddInDefBase.h IMemoryManager.h com.h)