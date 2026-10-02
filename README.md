Exercícios de Manipulação de Listas em Python
Este script é um programa interativo em Python que demonstra conceitos fundamentais de manipulação de estruturas de dados (listas). O código é dividido em quatro partes e utiliza transições interativas (limpeza de terminal e pausas) para facilitar a visualização da execução passo a passo.

Funcionalidades
O script aborda os seguintes tópicos de manipulação de listas:

Questão 01 - Acesso de Elementos: Demonstra como acessar itens específicos de uma lista (o primeiro e o último) utilizando índices positivos e negativos ([0] e [-1]).

Questão 02 - Iteração com Índices: Utiliza um laço de repetição (for) em conjunto com as funções range() e len() para varrer a lista e exibir o valor de cada elemento ao lado de sua posição exata.

Questão 03 - Fatiamento (Slicing): Mostra como extrair subconjuntos ou fatias de uma lista, recuperando os três primeiros itens ([:3]), os três últimos ([-3:]) e a lista ignorando os dois primeiros ([2:]).

Questão 04 - Modificação Dinâmica: Aplica métodos nativos do Python para alterar a lista em tempo de execução. Inclui append() para adicionar um novo dado, remove() para deletar um valor específico e len() para checar a quantidade atualizada de itens.

Módulos Utilizados
os: Utilizado para executar comandos do sistema operacional, garantindo que o terminal seja limpo automaticamente entre as questões independentemente do sistema (cls para Windows, clear para Unix).

time: Utilizado para criar pequenas pausas (time.sleep(2)) durante a execução da Questão 04, permitindo que o usuário acompanhe as atualizações da lista visualmente.

Como Executar
Salve o código fornecido em um arquivo com a extensão .py (exemplo: listas.py).

Abra o terminal ou prompt de comando do seu sistema.

Navegue até o diretório onde o arquivo foi salvo.

Execute o seguinte comando:
Bash
python listas.py
