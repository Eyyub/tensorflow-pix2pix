# tensorflow-pix2pix
A lightweight pix2pix Tensorflow implementation.

[@eyyub_s](https://twitter.com/eyyub_s)
## Build the example
First you need to download the [CMP Facade](http://cmp.felk.cvut.cz/~tylecr1/facade/) dataset.

Then, run `python build_dataset.py '<path/to/CMP_facade_DB_base/base'`

Finally, run `python example.py` and enjoy!

After 500 steps:
![](https://raw.githubusercontent.com/Eyyub/tensorflow-pix2pix/master/images/iter_500.jpg)


## Requirements
- Python 3.5 (didn't try 2.7)
- Tensorflow
- Matplotlib
