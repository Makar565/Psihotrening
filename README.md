# Psycho Trainer

A real time system to detect human emotions from image.


# Prerequisites
```
Python 3
OpenCV
```
# Installation
```
pip install tensorflow numpy scipy h5py
```
Download the trained model from the links given in sourcфайe/trained-model.txt
# Testing
```
python main.py
```

файл main.py отвечает за взаимодействие с пользователем
через main.py выбираем эмоцию и запускаем функцию r() в классе start() в файле em_model.py с параметрами эмоция и до скольки процентов нужно ее отработать(emoti,ind)
файл em_model.py класс EMR() отвечает за выгрузку готовых моделей
файл run.py класс starting() функция runing(emoti,ind) рапускает камеру (starting.cam(emoti,ind))
файл run.py класс starting() функция cam(emoti,ind) выводит на экран с камеры что видет и эмоджи
