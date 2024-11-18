
# Reproducibility

As mentioned above, the version of Python can affect its reproducibility.
We include the following code as the first code cell.

```python
import sys
IN_COLAB = 'google.colab' in sys.modules
if IN_COLAB:
    !sudo apt-get update -y > /dev/null 2>&1
    !sudo apt-get install python3.11 python3.11-dev python3.11-distutils libpython3.11-dev > /dev/null 2>&1
    !sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.11 2 > /dev/null 2>&1
```

All this does is check if the Jupyter Notebook is running and install the version of Python used to develop this course: 3.11.

You can technically remove this.
The version of Python usually has small changes that are backward compatible.
The main issue is the dependencies that we install; some have very specific version requirements that could affect which versions get installed.
