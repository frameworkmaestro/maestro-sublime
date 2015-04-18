# maestro-sublime
Package com funcionalidades para o maestro

# Como Instalar?
Faça o download do projeto zip e descompacte no diretório do <sublime>\Packages

No windows, fica em: C:\Users\<usuario>\AppData\Roaming\Sublime Text 2\Packages\

No linux, ??

# Snippets disponíveis

Comando  | Tipo de arquivo | Descricao |
-------------|-------------|-----------|
mform | xml | Insere a estrutura de um formulário completo, contendo fields, buttons e validators |
mtf | xml | mtextfield |
mbtn | xml | mbutton |
mbox | xml | mbox |
mdg | xml | mdatagrid |
mdgc | xml | mdatagridcolumn |
mvc | xml | mvcontainer |
mhc | xml | mhconainer |
msel | xml | mselection |
mbg | xml | mbasegroup |

# Teclas de atalho

Teclas de atalho podem ser usadas em algumas situações, principalmente para adicionar controles que contém outros controles. Por exemplo, suponha que já se tenha 3 mtextfields no formulario:

```xml
<mtextfield id="" label="" hint=""/>	
<mtextfield id="" label="" hint=""/>	
<mtextfield id="" label="" hint=""/>	
```

Os controles originalmente são dispostos verticalmente. Caso precise adicionar horizontalmente, é necessário introduzir o componente <mhcontainer>. Para fazer isso, selecione os três conmponentes e pressione simultaneamente **CTRL+SHIFT** e com eles pressionados aperte **M** e depois **H**

A tabela a seguir mostra os atalhos disponiveis:

Comando  | Ação |
-------------|-------------|
CTRL+SHIFT+M, H | mhcontainer |
CTRL+SHIFT+M, V | mvcontainer |
CTRL+SHIFT+M, B | mbasegroup |
CTRL+SHIFT+M, X | mbox |




