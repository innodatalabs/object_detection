# Sub-tree of tensorflow/models

From https://github.com/tensorflow/models

1. copied `research/slim/` and `research/object_detection`
2. added `requirements.txt`
3. generated protocol buffer classes as per [object_detection/configure_api.md]
4. added `requirements.txt` and `setup.py`
5. generated package `python setup.py bdist_wheel` and pushed to the (private) pypi

