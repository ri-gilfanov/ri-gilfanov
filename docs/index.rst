.. ri-gilfanov documentation master file, created by
   sphinx-quickstart on Fri Aug 20 04:56:36 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Руслан Гильфанов
================

.. toctree::
   :maxdepth: 2
   :caption: Содержание:

   db_scheme
   sqlalchemy


Архитектура приложений и сервисов
---------------------------------
* Исходный код, зависящий от фреймворка -- в отдельный слой.
* Исходный код, зависящий от ORM и СУБД -- в отдельный слой.
* Исходный код, независящий от фреймворка, ORM и СУБД -- в отдельный слой.
* Слои -- корень модульной / пакетной структуры больших проектов.


Указатели и таблицы
===================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
