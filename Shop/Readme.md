﻿Необходимо реализовать консольное приложение, которое умеет работать с лавками и товарами.

Возможности программы:
#Работа с витринами

Создать новую витрину с названием и объемом. Объем - сколько товаров может поместиться, у каждого товара свой объем.
Отредактировать витрину. При смене объема, если товары уже расположены на витрине и их суммарный объем больше нового значения объема витрины, программа
не позволять это сделать и сообщать ошибку.
Удалить витрину. Если товары расположены на витрине, то программа не позволять это сделать и сообщать ошибку.
В каждую созданную витрину можно добавить товар. При этом если товар не помещается, программа не позволять это сделать и сообщать ошибку

#Работа с товарами

Создать товар, который можно расположить на витрине.
Отредактировать товар
Удалить товар
#Модели
Витрина:

Идентификатор (порядковый номер, чтобы однозначно идентифицировать витрину)
Название
Объем
Дата создания
Дата удаления
Товар:

Идентификатор (порядковый номер, чтобы однозначно идентифицировать товар)
Название
Занимаемый объем
Товары на витрине:

Идентификатор (порядковый номер, чтобы однозначно идентифицировать товар на витрине)
Идентификатор витрины (порядковый номер, чтобы однозначно идентифицировать витрину)
Идентификатор товара (порядковый номер, чтобы однозначно идентифицировать товар)
Кол-во товара - в целом можно и сразу считать объем, если посчитаешь это удобным
Стоимость товара
В качестве товаров может быть все что угодно (можно пофантазировать)