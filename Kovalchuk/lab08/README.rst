Лінгвістичне моделювання
========================

Виконання 8-11 лабораторних робіт з дисципліни «моделювання систем»

Як запустити?
-------------

Vagga (recommended)
___________________

1. Встановіть `vagga`_.
2. Запустіть проект 
   
   .. code-block::
   
      vagga run

   .. note::

      Перший запуск може бути довгим, так як під час першого запуску створюється контейнер.      Усі наступні запуски будуть швидшими

3. Відкрийте http://localhost:8888/notebooks/lab08.ipynb у браузері.

Virtualenv
__________

.. warning::

   Даний спосіб не перевірявся. Використовуйте його на власний ризик.

   P.S. будь-які уточнення вітаються.

1. Створіть віртуальне оточення за допомогою команди

   .. code-block::

      virtualenv -p python3.5 .venv3.5

2. Активуйте віртуальне оточення

   .. code-block::

      source ./.venv3.5/bin/activate

3. Встановіть залежності

   .. code-block::

      pip install -r requirements.txt

4. Запустіть проект

   .. code-block::

      jupyter notebook --config=jupyter_notebook_config.py

5. Відкрийте http://localhost:8888/notebooks/lab08.ipynb у браузері.

.. _`vagga`: http://vagga.readthedocs.io/en/latest/installation.html
