# Programando Sonhos 2/2019

#### Utilizar Python 3.7
#### Com o Anaconda instalado, baixar as dependencias listadas no dependencias.txt e compactar num tar.gz:

```
mkdir dependencias
pip download -r dependencias.txt -d "./dependencias"
tar cvfz dependencias.tar.gz dependencias
```

#### Abra o Prompt de  Comando, crie e ative um ambiente com Python 3.7:
```
conda create -n prog-sonhos python=3.7
conda activate prog-sonhos
```

#### Com o ambiente virtual ativado, descompactar e instalar os arquivos de dependencias na máquina destino:

```
tar zxvf dependencias.tar.gz
cd dependencias
pip install Keras_Applications-1.0.8-py3-none-any.whl Keras_Preprocessing-1.1.0-py2.py3-none-any.whl Markdown-3.1.1-py2.py3-none-any.whl Werkzeug-0.16.0-py2.py3-none-any.whl absl-py-0.8.1.tar.gz astor-0.8.0-py2.py3-none-any.whl astroid-2.2.5-py3-none-any.whl autopep8-1.4.4.tar.gz certifi-2019.9.11-py2.py3-none-any.whl colorama-0.4.1-py2.py3-none-any.whl gast-0.2.2.tar.gz google_pasta-0.1.8-py3-none-any.whl grpcio-1.24.3-cp37-cp37m-win_amd64.whl h5py-2.10.0-cp37-cp37m-win_amd64.whl isort-4.3.20-py2.py3-none-any.whl lazy_object_proxy-1.4.1-cp37-cp37m-win_amd64.whl mccabe-0.6.1-py2.py3-none-any.whl numpy-1.17.3-cp37-cp37m-win_amd64.whl opt_einsum-3.1.0.tar.gz protobuf-3.10.0-cp37-cp37m-win_amd64.whl pycodestyle-2.5.0-py2.py3-none-any.whl pylint-2.3.1-py3-none-any.whl setuptools-41.6.0-py2.py3-none-any.whl six-1.12.0-py2.py3-none-any.whl tensorboard-1.15.0-py3-none-any.whl tensorflow-1.15.0-cp37-cp37m-win_amd64.whl tensorflow_estimator-1.15.1-py2.py3-none-any.whl tensorflow_hub-0.7.0-py2.py3-none-any.whl termcolor-1.1.0.tar.gz typed_ast-1.4.0-cp37-cp37m-win_amd64.whl wheel-0.33.6-py2.py3-none-any.whl wincertstore-0.2-py2.py3-none-any.whl wrapt-1.11.2.tar.gz -f ./ --no-index
```

#### Após as instalações, a pasta dependências pode ser apagada

#### O ambiente virtual está pronto para executar os scripts do Tensorflow