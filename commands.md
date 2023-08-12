### Commands to create the environment

`pip install -r requirements.txt` 
`pip install torch==1.5.1 torchvision==0.6.1`
`pip3 install -U 'git+https://github.com/timmeinhardt/cocoapi.git#subdirectory=PythonAPI'`
`rm -rf dist/`    ### this removes the dist directory that is created when you run the setup.py file to install MultiHeadAttention in the next command. This wont let you be caught up in the issue (hopefully)
`python src/trackformer/models/ops/setup.py build --build-base=src/trackformer/models/ops/ install` 
`pip install --upgrade numpy`




#### The list is :
`
[Package                       Version
----------------------------- ------------
argon2-cffi                   20.1.0
astroid                       2.4.2
async-generator               1.10
attrs                         19.3.0
backcall                      0.2.0
bleach                        3.2.3
certifi                       2020.4.5.2
cffi                          1.14.4
chardet                       3.0.4
cloudpickle                   1.6.0
colorama                      0.4.3
cycler                        0.10.0
Cython                        0.29.20
decorator                     4.4.2
defusedxml                    0.6.0
docopt                        0.6.2
entrypoints                   0.3
filelock                      3.0.12
flake8                        3.8.3
flake8-import-order           0.18.1
future                        0.18.2
gdown                         3.12.2
gitdb                         4.0.5
GitPython                     3.1.3
idna                          2.9
imageio                       2.8.0
importlib-metadata            1.6.1
ipykernel                     5.4.3
ipython                       7.19.0
ipython-genutils              0.2.0
ipywidgets                    7.6.3
isort                         5.6.4
jedi                          0.18.0
Jinja2                        2.11.2
jsonpatch                     1.25
jsonpickle                    1.4.1
jsonpointer                   2.0
jsonschema                    3.2.0
jupyter                       1.0.0
jupyter-client                6.1.11
jupyter-console               6.2.0
jupyter-core                  4.7.0
jupyterlab-pygments           0.1.2
jupyterlab-widgets            1.0.0
kiwisolver                    1.2.0
lap                           0.4.0
lapsolver                     1.1.0
lazy-object-proxy             1.4.3
MarkupSafe                    1.1.1
matplotlib                    3.2.1
mccabe                        0.6.1
mistune                       0.8.4
mkl-fft                       1.3.1
mkl-random                    1.2.2
mkl-service                   2.4.0
more-itertools                8.4.0
motmetrics                    1.2.0
MultiScaleDeformableAttention 1.0
munch                         2.5.0
nbclient                      0.5.1
nbconvert                     6.0.7
nbformat                      5.1.2
nest-asyncio                  1.5.1
networkx                      2.4
ninja                         1.10.0.post2
notebook                      6.2.0
numpy                         1.21.6
opencv-python                 4.2.0.34
packaging                     20.4
pandas                        1.0.5
pandocfilters                 1.4.3
parso                         0.8.1
pexpect                       4.8.0
pickleshare                   0.7.5
Pillow                        7.1.2
pip                           22.3.1
pluggy                        0.13.1
prometheus-client             0.9.0
prompt-toolkit                3.0.14
ptyprocess                    0.7.0
py                            1.8.2
py-cpuinfo                    6.0.0
pyaml                         20.4.0
pycocotools                   2.0
pycodestyle                   2.6.0
pycparser                     2.20
pyflakes                      2.2.0
Pygments                      2.7.4
pylint                        2.6.0
pyparsing                     2.4.7
pyrsistent                    0.17.3
PySocks                       1.7.1
pytest                        5.4.3
pytest-benchmark              3.2.3
python-dateutil               2.8.1
pytz                          2020.1
PyWavelets                    1.1.1
PyYAML                        5.3.1
pyzmq                         19.0.1
qtconsole                     5.0.2
QtPy                          1.9.0
requests                      2.23.0
sacred                        0.8.1
scikit-image                  0.17.2
scipy                         1.4.1
seaborn                       0.10.1
Send2Trash                    1.5.0
setuptools                    65.6.3
six                           1.15.0
smmap                         3.0.4
submitit                      1.1.5
terminado                     0.9.2
testpath                      0.4.4
tifffile                      2020.6.3
toml                          0.10.2
torch                         1.5.1
torchfile                     0.1.0
torchvision                   0.6.1
tornado                       6.1
tqdm                          4.46.1
traitlets                     5.0.5
typed-ast                     1.4.1
typing-extensions             3.7.4.3
urllib3                       1.25.9
visdom                        0.1.8.9
wcwidth                       0.2.5
webencodings                  0.5.1
websocket-client              0.57.0
wheel                         0.38.4
widgetsnbextension            3.5.1
wrapt                         1.12.1
xmltodict                     0.12.0
zipp                          3.1.0
`