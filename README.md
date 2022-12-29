# Comando vi no Linux (Editor de Textos) [Guia Básico]

Siga os passos abaixo para instalar o ambiente de **homologação Linux**.\
Template 1.0: Markdown - Alexandre Cysne Esteves


O Comando vi no Linux é um editor de textos ASCII poderoso e muito usado na interface de caractere do Linux para edição de arquivos e programas. Seu uso não é muito intuitivo à primeira vista, mas a edição simples de textos pode ser feita usando poucos comandos. 

Ele pode ser muito útil para pequenas correções pontuais, principalmente em ambiente de produção. Então não é má ideia saber lidar com esse editor de textos universalmente disponível nas distribuições Linux.

Basicamente ele tem dois modos de trabalho: o modo de operação e o modo de inserção. No modo de operação o vi espera comandos que vão realizar alguma ação. No modo de inserção, tudo que for digitado é considerado texto. 

* O modo de operação é acessado através da tecla ESC. O vi sempre inicia nesse modo. Para entrar no modo de inserção, basta a pressionar a tecla INSERT ou o comando “i”. 

Para fazer a edição simples de arquivos no vi:

```
$ vi nomedoarquivo
```

Altere o modo para inserção com a tecla INSERT ou pressionando a tecla “i“. O cursor pode ser movido neste modo com as setas de posição. Ao terminar a digitação aperte a tecla ESC e digite:

```
:w para salvar as modificações; 
:wq para salvar e sair do vi;
:q! para sair sem salvar;
```

Veja a seguir a tabela de comandos aceitos pelo vi. Todos os comandos deverão ser dados no modo de operação. O sinal “+” indica teclas que devem ser pressionadas simultaneamente. A vírgula indica que as teclas devem ser digitadas em sequência.

--- 
| Ação | Comando |
|:--- | :--- |
| Abrir Arquivo									|	:e arquivo			|
| Salvar Arquivo								|	:w                  |
| Salvar Arquivo Como							|	:w arquivo          |
| Salvar e Sair									|	:wq                 |
| Sair sem salvar								|	:q!                 |
| Gravar conteúdo se alterado					|	:ZZ                 |
| Para marcar um texto para cópia ou corte		|	v, setas de direção |
| Para copiar texto marcado						|	y                   |
| Para cortar texto marcado						|	c                   |
| Para colar texto marcado						|	p                   |
| Copiar uma linha								|	yy                  |
| Copiar até o final do arquivo					|	yG                  |
| Apagar texto à frente (DEL)					|	x                   |
| Apagar texto para trás (BACKSPACE)			|	X                   |
| Apagar uma linha								|	dd                  |
| Apagar até o final do arquivo					|	dG                  |
| Apagar até o final da linha					|	D                   |
| Localizar texto à frente						|	/texto              |
| Localizar novamente							|	/                   |
| Localizar texto para trás						|	?texto              |
| Localizar novamente							|	?                   |
| Desfazer alterações							|	u                   |
| Refazer alterações							|	CTRL+r              |
| Formatar Alinhamento Centralizado				|	:ce                 |
| Alinhamento à direta							|	:ri                 |
| Alinhamento à esquerda						|	:le                 |
| Abrir nova janela								|	:new                |
| Dividir a janela atual em duas				|	:split              |
| Abrir arquivo em nova janela					|	:split arquivo      |
| Ir para janela de cima						|	CTRL+w, k           |
| Ir para janela de baixo						|	CTRL+w, j           |
| Ir para o início da linha						|	0                   |
| Ir para o final da linha						|	$                   |
| Ir para o final do arquivo					|	G                   |
| Ir para a linha de baixo						|	j                   |
| Ir para a linha de cima						|	k                   |
| Ir para a esquerda							|	h                   |
| Ir para a direita								|	l                   |
| Ir para o final da tela						|	L                   |
| Ajuda											|	:help               |
| Insere texto antes do cursor					|	i                   |
| Insere texto depois do cursor					|	a                   |
| Insere texto em uma nova linha				|	o                   |
--- 

