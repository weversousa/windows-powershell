# Windows PowerShell - Linha de Comandos



## CMDLETS

Comandos disponíveis dentro do PowerShell


### Data atual

```powershell
Get-Date
```


### Ajuda para usar um comando

```powershell
help Get-Date
```


### Exibir tudo que está dentro do diretório

```powershell
Get-ChildItem
```

```powershell
dir
```

```powershell
ls
```


### Exibir tudo que está dentro inclusive ocultos

```powershell
Get-ChildItem -Force
```

* d: Diretório
* a: Arquivo
* r: Leitura



### Exibir Caminho

```powershell
Get-Location
```

```powershell
pwd
```

```powershell
gl
```


### Limprar tela

```powershell
Clear-Host
```

```powershell
clear
```

```powershell
cls
```


### Qual o nome de usuário

```powershell
whoami
```


### Atualizar Ajuda do PowerShell

```powershell
update-help
```


### Comandos Existentes

```powershell
Get-Command -CommandType Cmdlet
```

```powershell
Show-Command
```


### Criar um Arquivo ou Pasta

```powershell
New-Item -Path "<caminho>" -ItemType Directory
```

```powershell
mkdir -Path "<caminho>"
```

```powershell
New-Item -Path "<caminho>\<nome do arquivo.extensão>" -ItemType File
```

```powershell
ni "<caminho>\<nome do arquivo.extensão>"
```


### Renomear um Arquivo

```powershell
rni nome.txt novo_nome.txt
```


### Copiar um arquivo para mesma pasta

```powershell
Copy-Item -Path nome.txt -Destination copia_nome.txt
```

```powershell
cp -Path nome.txt -Destination copia_nome.txt
```

```powershell
cp nome.txt copia_nome.txt
```


### Copiar um arquivo para outra pasta

```powershell
cp -Path nome.txt -Path "<caminho>\<nome.txt>"
```


### Mover um arquivo para outra pasta

```powershell
mv -Path nome.txt "<caminho>\<nome.txt>"
```


### Apagar um arquivo ou pasta

```powershell
Remove-Item -Path nome.txt
```

```powershell
erase -Path nome.txt
```

```powershell
Remove-Item -Path <caminho> -Force -Recurse
```


### Ler arquivo

```powershell
Get-Content -Path "<caminho>"
```


### Ocultar arquivo ou pasta

```powershell
attrib +S +H "<caminho>"
```


### Desocultar arquivo ou pasta

```powershell
attrib -S -H "<caminho>"
```