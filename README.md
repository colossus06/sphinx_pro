

## installing sphinx

Let's start updating python: 
- ``python -m pip install -U pip``

**Getting started with sphinx**

- ``sudo apt install python3-sphinx``
- ``mkdir project``
- ``cd /path/to/project``
- ``mkdir docs``
- ``cd docs``
- ``sphinx-quickstart``


![image](https://user-images.githubusercontent.com/96833570/184400139-e5a1abb6-7d88-4489-ad33-47861b1d1fba.png)




**Creating an html documentation**


- ``make html`` 

Oputput should look similar to this: The HTML pages are in ``_build/html``.

- ``cd docs``
- ``open _build/html/index.html``
![image](https://user-images.githubusercontent.com/96833570/184403140-dfc3e766-44d5-4bf4-b88a-c6d025aa7a91.png)
