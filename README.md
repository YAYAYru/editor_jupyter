# editor_jupyter
## Jupyter notebook
- how to import own modules in Jupyter? [StackoverFlow](https://stackoverflow.com/questions/34976803/sys-path-different-in-jupyter-and-python-how-to-import-own-modules-in-jupyter)
```python
import sys
sys.path.append("../") # go to parent dir
from customFunctions import *
```
- See a function [youtube](https://www.youtube.com/watch?v=p1mSVgmSOAQ)
```python
open??
```
- After editing a module, changes are not effective without kernel restart [enthought.com](https://support.enthought.com/hc/en-us/articles/204469240-Jupyter-IPython-After-editing-a-module-changes-are-not-effective-without-kernel-restart)|[stackoverflow](https://stackoverflow.com/questions/1254370/reimport-a-module-in-python-while-interactive)
```python
import importlib
importlib.reload(some_module)
```
- autoreload¶ [ipython.readthedocs.io](https://ipython.readthedocs.io/en/stable/config/extensions/autoreload.html)
```python
%autoreload 2
```
- Change the Theme in Jupyter Notebook? [stackoverflow](https://stackoverflow.com/questions/46510192/change-the-theme-in-jupyter-notebook)
```bash
pip install jupyterthemes #
jt -l
```
## Colab
- Animation in Jupyter Notebooks [colab](https://colab.research.google.com/github/jckantor/CBE30338/blob/master/docs/A.03-Animation-in-Jupyter-Notebooks.ipynb#scrollTo=8wXH1S_h2qkq)
- Google Colab features you may have missed [youtube](https://youtu.be/rNgswRZ2C1Y)
## JupyterLab
- STOP Using Jupyter Notebook! Here's the Better Tool [YouTube](https://youtu.be/zai2pLUD9FA)
