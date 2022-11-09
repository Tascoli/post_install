# Post Install 

Repositório dedicado a criar guia de configurações para as diversas distribuições linux. 

TODO:

[] Criar roteiro de configuração global. Possiveis de serem instalados em quaisquer sistemas operacionais ou distribuições.

[] Criar roteiro de configurações especificas para cada distro e ambiente gráfico.

## Aluguns comonandos que auxiliam nas configrações

- Para listar os programas padrões, independententemente do ambiente gráfico, através do terminal use:

```sh
sudo update-alternatives --get-selections 
```
### Gnome
Usando terminal para:

- Listar configurações do Gnome:

```
gsettings list-recursively
```

- Definir as configurção desejada:

```sh
#gsettings set <SCHEMA> <CHAVE> <"VALOR">
# Exemplo:
gsettings set org.gnome.desktop.input-sources sources "[('xkb', 'us+alt-intl')]"
```


