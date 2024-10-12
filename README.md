git clone https://github.com/apache/arrow.git
cd arrow/python
python setup.py build_ext --inplace
python setup.py bdist_wheel
