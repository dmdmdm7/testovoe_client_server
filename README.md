# Проект

Проект состоит из двух программ, взаимодействующих между собой через сокеты.
Программа 1 состоит из двух потоков, которые взаимодействуют через общий буфер.
Программа 1 пересылает данные Программе 2, та получает их и выводит информацию на экран.

Программа 1 расположена в директории prog1

Программа 2 расположена в директории prog2

## Системные требования

- CMake 3.10 или выше

- GCC

# Инструкции по сборке

0) Перейдите в папку testovoe_client_server.

1) Создайте директорию для сборки проекта и перейдите в неё:

    mkdir build

    cd build

2) Запустите CMake и соберите проект:

    cmake ..

    make

# Инструкции по запуску

1) Запустите Программу 1

    ./prog1/Program1

2) Запустите Программу 2 в другом терминале:

    ./prog2/Program2

# Следуйте выводимым на экране подсказкам
