# Trabalho Extra 01 - Listar Arquivos
Faça um programa que possa ser chamado em linha de texto, que simule o funcionamento dos comandos ```ls``` e ```dir```, para ler
dados do ```Sistema de Arquivos``` e gere a saída na forma da tabela abaixo:


#### Entrada:
```  
    nomeDoProgramaQueVoceVaiCriar caminhoAteUmArquivo
    nomeDoProgramaQueVoceVaiCriar caminhoAteUmaPasta
```
Onde por exemplo: 
* caminhoAteUmArquivo: arquivo1.txt ou C:/Users/Usuario01/Desktop/arquivo1.txt
* caminhoAteUmaPasta: PastaTal01 ou C:/Users/Usuario01/Desktop/PastaTal01



#### Saída Exemplo:
```
╔═══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════╗
║   Tipo    PermissaoString PermissãoOctal    Proprietário    Grupo       Tamanho     DataModificacao NomeArquivo         ║
╟───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╢
║   -       rwx rwx rwx     7 7 7               <proprietario>  <grupo>     100 b       dd/MM/yyyy      arquivo1.txt        ║
║   -       rwx rwx rwx     7 7 7               <proprietario>  <grupo>     100 b       dd/MM/yyyy      arquivo1.txt        ║
║   -       rwx rwx rwx     7 7 7               <proprietario>  <grupo>     100 b       dd/MM/yyyy      arquivo1.txt        ║
║   l       rwx rwx rwx     7 7 7               <proprietario>  <grupo>     100 b       dd/MM/yyyy      arquivo.lnk         ║
║   d       rwx rwx rwx     7 7 7               <proprietario>  <grupo>       0 b       dd/MM/yyyy      Nova Pasta          ║
╚═══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════╝
```

##### Observações:
- O Tipo pode ser: -(para um arquivo), d(para um diretório) e l(para um link)
- PermissaoString deve apresentar a permissão do arquivo no formato rwx, onde r(read), w(write), x(execute)
- PermissãoOctal deve apresentar a permissão do arquivo no formato octal
- Tamanho deve apresentar o tamanho do arquivo em bytes
- DataModificacao deve apresentar a data no formato dd/MM/yyyy
- Todos os nomes e caminhos de arquivos e pastas são figurados, colocados apenas com a finalidade de demonstrar um exemplo de utilização
- Se seu programa recebeu um arquivo, então imprima a tabela somente para esse arquivo; Se seu programa recebeu um diretório, então imprima   a tabela para todos os arquivos e pastas dentro.


#### Linguagem de Programação
Livre, escolha qualquer uma que se sentir confiante, mas a entrada e saida deve serem fornecidas pela linha de comando


**Forma de entrega:**
* Crie um repositório no [GitHub] e envie todo os arquivos para lá
* No README.md coloque seu nome e número, além dos procedimentos para executar seu programa
* Certifique-se que todo o seu trabalho foi enviado
* Adicionar o usuário [denylsonmelo] como colaborador do projeto
* Marque uma data para apresentar em sala, de forma a sanar dúvidas de todos sobre os passos de desenvolvimento do mesmo

[GitHub]: https://github.com/
[denylsonmelo]: https://github.com/denylsonmelo/