# Статутс сборки [![Build status](https://ci.appveyor.com/api/projects/status/tqnj20215pjb44no?svg=true)](https://ci.appveyor.com/project/Alisa68/aqa-api-ci-2)

В этой задаче мы сэмулируем ситуацию, в которой SUT уже запущен, а мы из теста просто обращаемся к нему.

Есть специальный сервис, предназначенный для тестирования HTTP-запросов. Называется он Postman Echo (никогда не тестируйте автоматизированными средствами веб-сервисы, если у вас нет на этого письменного разрешения либо веб-сервисы специально не предназначены для этого).

Мы можем отправлять туда запросы и получать ответы.
