# Прасер [документов PEP](https://www.python.org/dev/peps/) на базе фреймворка Scrapy 

Парсер ищет все [PEP](https://peps.python.org/) правила и выводит информацию о них в два CSV файла:
1. Список всех имеющихся PEP: номер, название и статус
2. Сводка по статусам PEP — сколько найдено документов в каждом статусе (статус, количество) 

## Используемые технологии:

Python 3.9, Scrapy

## Как запустить проект

Клонировать репозиторий и перейти в него в командной строке:


```bash
git clone git@github.com:DonBenn/parser_scrapy.git
```

## Cоздать и активировать виртуальное окружение:
```bash
cd parser_scrapy/
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
```

## Для запуска используйте команду
```bash
scrapy crawl pep
```

## Автор

Bessonov Denis (https://github.com/DonBenn)