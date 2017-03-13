# Исходники для развертывания локальной среды разработки

## Инструкция по установке

### 1. Устанавливаем VirtualBox или что душе угодно

> https://www.virtualbox.org/

### 2. Устанавливаем сам Vagrant

> https://www.vagrantup.com/

### 3. В вашу деректорию копируем все файлы из этой репы

### 4. Развертываем

> vagrant up

## Как управлять

### Разворачиваем

> vagrant up

### Останавливаем

> vagrant halt

### Удаляем машину

> vagrant destroy

### Статус

> vagrant status

### Узнать какие команды есть еше :)

> vagrant help

## Что и как

#### В корне храним git, composer и все что не должно быть в public

#### Разработку ведем в:

>/public/

#### Все настройки php-fpm nginx хрантся тут:

>/.vagrant/

#### Скрипт /.vagrant/install.sh

Используется для последовательного выполнения комманд, в нем можно настроить что установить при установке машины
