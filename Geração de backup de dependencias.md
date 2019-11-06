#### Gerar a lista de dependencias do projeto:

```
pip freeze > dependencias.txt
```

#### Baixar as dependencias listadas no dependencias.txt e compactar num tar.gz:

```
mkdir dependencias
pip download -r dependencias.txt -d "./dependencias"
tar cvfz dependencias.tar.gz dependencias
```
