cmake_minimum_required(VERSION 3.15)
set(PROJECT_NAME example) #задание значения переменной
project("${PROJECT_NAME}") #устанавливаем имя проекта
set(CMAKE_CXX_STANDARD 17) #устанавливаем 17 стандарт языка (набор поддерживаемых библиотек\команд)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)