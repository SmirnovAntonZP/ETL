# Урок 7. Построение пайплайнов и визуализация потоков данных в Airflow

## Условие: 

- Зарегистрируйтесь в ОрепWeatherApi (https://openweathermap.org/api)

- Создайте ETL, который получает температуру в заданной вами локации, и
дальше делает ветвление:

- В случае, если температура больше 15 градусов цельсия — идёт на ветку, в которой есть оператор, выводящий на
экран «тепло»;

- В случае, если температура ниже 15 градусов, идёт на ветку с оператором, который выводит в консоль «холодно».

- Оператор ветвления должен выводить в консоль полученную от АРI температуру.

- Приложите скриншот графа и логов работы оператора ветвленния.

--------
## Cкриншоты выполнения задания: 

Сделаем загрузку с    
https://goweather.herokuapp.com/

Регестрация не понадобилась


Run

![DAG](run.png)

log1

![log1](log1.png)

log2

![log1](log2.png)

log3

![log1](log3.png)


