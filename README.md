template_ifbatcc - formato LaTeX p/ textos de trabalhos de conclusão do IFBA/SAJ

## Sobre

Este pacote é destinado à escrita de trabalhos de conclusão de curso, documentos de qualificação de mestrado e de doutorado, dissertações de mestrado e teses de doutorado da  Instituto Federal da Bahia, Campus Santo Antônio de Jesus.

Este pacote á baseado no [UFPEThesis](http://www.cin.ufpe.br/~paguso/ufpethesis/),  por Paulo G. S. da Fonseca. Adaptado para o IFBA/SAJ por Antônio Cleber de Sousa Araújo em 2021 e por Leandro Costa Souza em 2023.

## Como usar

### Windows

- Instale o scoop (https://scoop.sh/)
```console
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```
- instale o git, gh, miktex e perl 
```console
scoop install git
scoop install gh
scoop install miktex
scoop install perl
```
- faça login no gh
```console
gh auth login
```

- faça o fork do repositório
```console
gh repo fork ifbasaj/tcc-template --clone=true
```

-  edite o arquivo  * Use `ifbatcc` como o `documentclass` do seu documento.

* Tente seguir um dos modelos o mais fielmente possível.

* Este template em LaTeX apresentam a estrutura para 
tec (Trabalho de Conclusão de Curso), bsc (Monografia),
msc (dissertação de mestrado), phd (tese de doutorado),
qual (qualificação de mestrado) e prop (qualificação de doutorado).

* Em caso de dúvidas que não possam ser sanadas verificando o template, 
verifique o código no arquivo `ifbatcc.cls`.

## Ferramenta de edição online

- https://pt.overleaf.com/ (para user o modelo latex)
- https://www.mettzer.com/
- https://monografis.com.br/
- https://fastformat.co/
