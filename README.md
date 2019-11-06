# Programando Sonhos 2/2019

#### Gerar a lista de dependencias do projeto:

```
pip freeze > dependencias.txt
```

#### Baixar dependencias e salvar num tar.gz:

```
mkdir dependencias
pip download -r requirements.txt -d "./dependencias"
tar cvfz dependencias.tar.gz dependencias
```

#### Descompactar e instalar dependencias na máquina destino:

```
tar zxvf dependencias.tar.gz
cd dependencias
pip install * -f ./ --no-index
```
