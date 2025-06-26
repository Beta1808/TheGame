cmake_minimum_required(VERSION 3.5)
project(MyServerClientProject)

# Подключаем Qt (если нужно)
find_package(Qt6 REQUIRED COMPONENTS Core Network Gui Widgets)

# Добавляем подпроекты (если папки существуют)
add_subdirectory(Server)
add_subdirectory(Client)

