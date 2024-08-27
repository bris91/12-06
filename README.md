# Домашнее задание к занятию "Репликация и масштабирование. Часть 1" - `Lebedev Boris`

# Задание 1
На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.

Ответить в свободной форме.

В режиме master-slave master может записывать информация и считывать, а slave только считывает. Информация из master попадает в slave.
В режиме master-master оба mastera записывают и считывают информацию.

# Задание 2
Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

Приложите скриншоты конфигурации, выполнения работы: состояния и режимы работы серверов.

![alt text](https://github.com/bris91/12-06/blob/ea389df04fb53801123b92180c478193619d46f0/m_sel.png)
![alt text](https://github.com/bris91/12-06/blob/ea389df04fb53801123b92180c478193619d46f0/sl_sel.png)
![alt text](https://github.com/bris91/12-06/blob/ea389df04fb53801123b92180c478193619d46f0/m_st.png)
![alt text](https://github.com/bris91/12-06/blob/ea389df04fb53801123b92180c478193619d46f0/sl_st.png)
