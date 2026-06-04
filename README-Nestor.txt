Nestor - Guia rapido de uso
===========================

O que e o Nestor
----------------

O Nestor e um sistema de automacao simples para montar sequencias de cliques, digitacao, esperas e listas.
Ele controla o mouse e o teclado do computador, entao use sempre com a tela correta aberta e confira as coordenadas antes de iniciar.

Como abrir
----------

Depois de instalado, abra pelo atalho "Nestor" na area de trabalho ou pelo menu Iniciar.

Como montar uma automacao
-------------------------

1. Escolha o tipo de acao no campo "O que vou fazer?".
2. Preencha as informacoes da acao escolhida.
3. Clique em "Adicionar acao (F4)".
4. Repita ate montar a sequencia completa.
5. Use "Rodar robo (F1)" para iniciar.
6. Use "Parar (F2)" para interromper.

Tipos de acao
-------------

clique:
Use para clicar em uma coordenada da tela. Posicione o mouse no local desejado e pressione F3 para capturar X e Y.

escrita:
Use para digitar um texto fixo.

backspace:
Use para apagar uma quantidade de caracteres.

espere:
Use para pausar a automacao por alguns segundos.

lista:
Use para ler itens de um arquivo TXT e repetir a sequencia para cada item.

Como usar lista TXT
-------------------

Crie um arquivo TXT com itens separados por virgula, por exemplo:

cliente 1,cliente 2,cliente 3

No Nestor:

1. Escolha o tipo "lista".
2. Selecione o arquivo TXT.
3. Informe o separador, normalmente virgula.
4. Escolha se o Nestor deve pressionar Enter, Tab ou nada depois de cada item.

Atalhos
-------

F1: inicia a automacao.
F2: para a automacao.
F3: captura a posicao atual do mouse.
F4: adiciona a acao preenchida.

Salvar e carregar configuracoes
-------------------------------

Use "Salvar config" para guardar uma sequencia pronta em arquivo JSON.
Use "Carregar config" para abrir uma sequencia salva anteriormente.

Seguranca
---------

O PyAutoGUI possui uma parada de emergencia: mover o mouse para o canto superior esquerdo da tela interrompe a automacao.
Como o Nestor automatiza mouse e teclado, antivirus ou politicas da empresa podem pedir permissao na primeira execucao.
