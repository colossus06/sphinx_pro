

## installing sphinx

Let's start updating python: 
- ``python -m pip install -U pip``

**Getting started with sphinx**

- ``pip install -U sphinx``
- ``mkdir project``
- ``cd /path/to/project``
- ``mkdir docs``
- ``cd docs``
- ``sphinx-quickstart``


![image](https://user-images.githubusercontent.com/96833570/184484605-48431679-2816-4322-9ec8-ff0de1dd8d03.png)




**Creating an html documentation**


- ``make clean html`` 

Oputput should look similar to this: The HTML pages are in ``_build/html``.

- ``cd docs``
- ``open _build/html/index.html``
![image](https://user-images.githubusercontent.com/96833570/184484762-30190dcf-8d89-4fd8-beca-7547b65eccab.png)
