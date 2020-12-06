cmake_minimum_required(VERSION 3.12 FATAL_ERROR)

project(VMA CXX)

add_library(vma)
target_sources(vma PRIVATE src/vk_mem_alloc.cpp)
target_include_directories(vma PUBLIC src)
