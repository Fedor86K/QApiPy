# QApiPy	

Это набор python скриптов для автоматизированной проверки простых API запросов методами GET и POST.
Скрипты имеют единый интерфейс с возможностью выбора метода тестирования, визуальной демонстрации результатов API запросов, повторного проведения набора тестов, ведения логов, сохранения результатов для каждого теста в простом отчете формата xlsx для дальнейшего просмотра и редактирования.

Порядок установки:

- Установите интерпретатор Python версии 3.8 или выше, с официального сайта  [python](https://www.python.org/downloads/)
- Установите дополнительные пакеты 

	- requests
 	- openpyxl

  c помощью командной строки, используя команду `pip3 install [package name]`
- Переместитe файлы из папки QApiPy в выбранную директорию

Порядок работы:

- Изучите документацию тестируемого API
- Подготовьте тестовые данные
- Изучите шаблон составления тестов [template.txt](template.txt)
- Перейдите в папку testrun
- Выберите подпапку get или post согласно тестируемому методу
- Cоздайте в выбранной подпапке файлы JSON с тестовыми сценариями
- Откройте и запустите файл QApiPy.py используя стандартную среду разработки Python IDLE,
  либо оболочку командной строки python, запустив файл QApiPy.bat
- Следуя информационным указаниям выберите тестируемый метод и возможность сохранения отчета
- Запустите созданную последовательность тестов
- Отслеживайте состояние и статус прохождения тестов в последующем информационном сообщении (!)
- По завершению прохождении тестов выберите дальнейшие действия


	![alt text](/img/result.PNG)

Результаты работы скрипта с запуском одного теста по средствам командной строки

! Обратите внимание, что скрипт не подходит для визуализации ответов с объёмным Response body !

! Обратите внимание, что скрипт не выдает информации по Response headers !

Успехов в Вашей работе !
