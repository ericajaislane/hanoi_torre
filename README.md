Torre de Hanoi – Projeto Final REA
Este repositório traz uma simulação visual e interativa do clássico jogo Torre de Hanoi, criada como trabalho final da disciplina de Estrutura de Dados.

🎯 Objetivo do Projeto
O foco deste projeto é aplicar a estrutura de dados pilha para controlar a lógica do jogo Torre de Hanoi. A simulação respeita as regras tradicionais, impedindo movimentos inválidos e permitindo que o usuário conclua o desafio de forma interativa.

🧠 Lógica Utilizada
Cada torre funciona como uma pilha, onde os discos são empilhados e retirados. O jogo valida os movimentos para garantir que discos maiores nunca fiquem sobre discos menores. O estado do jogo é armazenado em variáveis JavaScript que representam as torres A, B e C.

🖥️ Tecnologias Usadas
HTML5 para a estrutura da página

CSS3 para o estilo e animações

JavaScript (Vanilla) para a lógica do jogo e interação

🎮 Funcionalidades
Escolha do número de discos (de 3 a 5)

Movimentação dos discos via clique ou arrastar e soltar (drag-and-drop)

Validação dos movimentos com alertas para movimentos inválidos

Mensagem de vitória ao completar o jogo

Botão para reiniciar o jogo a qualquer momento

📷 Interface
Interface simples, visual e intuitiva, com discos coloridos empilhados nas torres A, B e C. O usuário pode jogar clicando nos discos e torres ou usando drag-and-drop.

▶️ Como Executar

1. Clone o repositório:
   bash
   git clone https://github.com/ericajaislane/hanoi_torre.git

Desenvolvido por Erica Jaislane. 

Problemas e Soluções

Durante o desenvolvimento, pensei em alguns problemas que poderiam ocorrer:

Não permitir mover disco maior sobre disco menor (implementado validação antes do movimento).  
Evitar seleção de discos que não estão no topo da torre.  
Limitar número de discos para entre 3 e 5.  
Prevenir cliques inválidos que poderiam causar erros.  
Implementar drag-and-drop apenas para discos do topo.  
Garantir que o jogo possa ser reiniciado limpando tudo corretamente.

Essas soluções ajudam a manter o jogo funcionando corretamente e oferecem uma boa experiência ao usuário.

