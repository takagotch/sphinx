### sphinx
---
.py
http://www.sphinx-doc.org/en/master/

http://www.sphinx-doc.org/en/latest/

```sh
apt-get install pytho3-sphinx
yum install python-sphinx

brew install sphinx-doc
sudo port install py36-sphinx
sudo port select --set python python36
sudo port select --set sphinx py36-sphinx

conda install sphinx
pip install -U sphinx
pip install -U sphinx
pip install -U --pre sphinx
git clone https://github.com/sphinx-doc/sphinx
cd sphinx
pip install .
pip install git+https://github.com/sphinx-doc/sphinx
```

```py
import sys, os
sys.paht.append(os.path.abspath('sphinxext'))
extensions = ['extname']

source_suffix = {
  '.rst': 'restructuredtext',
  '.txt': 'restructuredtext',
  '.md': 'markdown',
}
```

```
```

