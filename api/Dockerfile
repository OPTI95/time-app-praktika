#ИСПОЛЬЗУЕМ ALPINE ТАК КАК ОН ВЕСИТ МЕНЬШЕ И ИСПОЛЬЗУЕТ БАЗОВЫЙ СЛОЙ ОПЕРАЦИОННОЙ СИСТЕМЫ.
#КАК РАЗ ПОДХОДИТ ПОД НАШЕ ЛЕГКОЕ API И ДЛЯ ЛОКАЛЬНОГО РАЗВЕРТЫВАНИЯ)))
FROM node:alpine
#УКАЗЫВАЕМ РАБОЧУЮ ПАПКУ, ИЗ КОТОРОЙ БУДУТ ЗАПУСКАТЬСЯ ОСНОВНЫЕ КОМАНДЫ
WORKDIR /time-app-praktika
#КОПИРУЕМ ФАЙЛЫ В КОНТЕЙНЕР 
COPY . .
#ЗАПУСКАЕМ СКАЧИВАНИЕ ПАКЕТОВ
RUN npm install
#ЗАПУСКАЕМ НАШЕ API С ИСПОЛЬЗОВАНИЕМ КОМАНД В CMD
CMD [ "npm","run","dev" ]
#НАЗНАЧАЕМ ПОРТ
EXPOSE 5000