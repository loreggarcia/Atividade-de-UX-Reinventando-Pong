
## 1. Introdução

[](https://github.com/InteliContent/M1/blob/main/UX-Design/Reinventando-Pong_Template.md#1-introdu%C3%A7%C3%A3o)
A atividade tem como proposta explorar os conhecimentos adquiridos em sala acerca de Framework MDA, Concept Art e Game Design por meio da análise e reinterpretação do jogo clássico Pong e da prática com imagens digitais., o objetivo geral da atividade é desenvolver um Concept Art e uma tela digital baseados na proposta de reinvenção do jogol.

---

## 2. Pesquisa e Análise Inicial

[](https://github.com/InteliContent/M1/blob/main/UX-Design/Reinventando-Pong_Template.md#2-pesquisa-e-an%C3%A1lise-inicial)
O jogo Pong tem regras simples e intuitivas para o usuário, as ações tem uma resposta visual e auditiva clara que reforça as noções de causa e consequência dentro do jogo, o confronto direto entre jogadores, aliado à imprevisibilidade do movimento da bola mantém o jogador engajado na dinâmica do jogo. Apesar de simples, o jogo exige certa estratégia do jogador para posicionar a raquete, o sistema de pontuação também estimula a competição.

---

## 3. Proposta de Reinvenção

[](https://github.com/InteliContent/M1/blob/main/UX-Design/Reinventando-Pong_Template.md#3-proposta-de-reinven%C3%A7%C3%A3o)

A nova versão de _Pong_ se inspira em jogos de “quebra-blocos” (_block breaker_), mas mantém a essência competitiva de duas barras (raquetes) em lados opostos. O cenário é futurista, com blocos coloridos flutuando entre os dois jogadores. Cada jogador controla uma barra posicionada nas extremidades da tela. 
- **Bolas**: Cada jogador começa com uma bolinha. As bolinhas são coloridas ou têm pequenos efeitos de brilho, para diferenciar quando um jogador ganha mais bolas.
- **Blocos**: Distribuídos pelo centro da tela, os blocos podem ter cores vibrantes e diferentes tipos (alguns mais resistentes, outros que concedem bônus ou penalidades).
- **Power-ups**: Ao quebrar um bloco, o jogador pode liberar power-ups que caem no seu lado.

**Mudanças na Mecânica**

1. **Quebra de Blocos**:
    - Quando um jogador atinge um bloco com a sua bolinha, o bloco é quebrado e pode liberar uma nova bolinha ou um power-up.
    - Se o jogador coleta esse power-up (tocando com a raquete), obtém o efeito imediatamente.
2. **Ganhar e Perder Bolas**:
    - **Ganhar**: Ao quebrar um bloco, o jogador recebe uma nova bolinha
    - **Perder**: Sempre que uma bolinha consegue “passar” pelo lado do jogador (isto é, o jogador deixa a bola escapar), ele perde uma das suas bolinhas em estoque. Se ficar sem bolinhas, o jogador é eliminado.
3. **Passagem de Bolas para o Adversário**:
    - Quando o jogador rebate uma bola para o campo do adversário, se o adversário não conseguir defendê-la, ele perde uma de suas bolinhas.
    - O objetivo é tentar mandar a maior quantidade possível de bolinhas para o lado do adversário, forçando-o a defendê-las e eventualmente ficar sem estoque.
4. **Condição de Derrota**:
    - O jogador perde ao ficar sem nenhuma bolinha disponível.
    - Também é possível definir um tempo limite. Ao final desse tempo, quem tiver passado mais bolinhas para o lado do adversário (ou quem tiver mais bolinhas em estoque) vence.


**Objetivo da Reinvenção**
![Pasted image 20250214222742.png]
**Rascunho da Folha de Concept Art**

O concept art foi desenvolvido pensando na mescla entre o Pong original e os elementos de quebra-blocos tentando colocar as novas regras do jogo no papel com setas mostrando o trajeto das bolas quando rebatidas, sinalizando que se elas passarem pelo adversário, o adversário perde uma bola e pequenos rótulos explicando como cada bloco pode gerar uma bolinha extra.

**Como o Esboço foi Desenvolvido**

- Definimos a posição das barras (tal qual o jogo original) e a área central onde ficariam os blocos, depois incluíram-se setas para indicar o movimento das bolas, demonstrando como elas podem ir e vir de um lado a outro, inseriramos ícones e pequenos símbolos de power-ups, para mostrar que eles surgem ao quebrar blocos e podem ser coletados pelo jogador responsável.

## 4. Tela Digital do Jogo

[](https://github.com/InteliContent/M1/blob/main/UX-Design/Reinventando-Pong_Template.md#4-tela-digital-do-jogo)

![[Pasted image 20250214222742.png]]
_- Como o concept foi adaptado para o formato digital?_

_- Quais elementos visuais foram aprimorados?_

_- O uso de cores, formas e layout foi pensado para reforçar que aspectos do jogo?_

---
**Adaptação do Concept para o Formato Digital**  
No processo de passar do rascunho em papel para a arte digital, houve uma preocupação em traduzir os elementos principais (barras, bolas, blocos e power-ups) para um estilo visual mais limpo e coeso, aproveitando os recursos de design vetorial e paletas de cores vibrantes. A ideia foi manter a disposição geral dos elementos do esboço, mas aprimorar detalhes, contrastes e animações que só são possíveis em ambiente digital.

---

**Elementos Visuais Aprimorados**

1. **Blocos Coloridos**:
    
    - No formato digital, os blocos ganharam cores sólidas e um contorno mais definido, para reforçar a ideia de “quebra-blocos”.
    - A distribuição dos blocos no espaço ficou mais organizada e simétrica, facilitando a leitura do layout e a jogabilidade.
2. **Bolas/Esferas**:
    
    - Foram criadas bolinhas com cores e tamanhos ligeiramente distintos, permitindo identificar quando existem várias esferas em jogo.
    - Pequenos efeitos de brilho ou sombra foram adicionados para dar a sensação de volume ou energia.
3. **Barras/Raquetes**:
    
    - As barras adotaram cores contrastantes em relação ao fundo, para que sejam facilmente identificáveis e para indicar qual jogador está no controle de cada lado.
    - O formato mais “minimalista” foi mantido, porém com acabamento digital que evidencia o contorno e a funcionalidade (recolher power-ups, rebater as bolas).
4. **Power-ups e Ícones**:
    
    - Ícones flutuantes foram inseridos para representar itens especiais, com formas simples (círculos, pequenos símbolos) e cores fortes que se destacam dos blocos.
    - Ao quebrar um bloco, o power-up surge de forma animada, indicando claramente o seu trajeto até a barra do jogador.
5. **Fundo e Paleta de Cores**:
    
    - O fundo escuro realça as cores neon ou vibrantes dos blocos, bolas e barras, criando um contraste que facilita a visualização dos elementos em movimento.
    - A escolha de cores saturadas (vermelho, verde, amarelo, azul) reforça a ideia de dinamismo e competitividade, além de remeter a jogos clássicos de arcade.

---

**Uso de Cores, Formas e Layout para Reforçar o Jogo**

- **Cores**:  
	* Cada cor de bloco pode representa um tipo de pontuação, durabilidade ou efeito, ajudando o jogador a planejar suas jogadas. Além disso as cores vibrantes remetem a um ambiente de fliperama, reforçando a temática arcade.
- **Formas**:
    - A escolha de manter o estilo limpo do original e adicionar formas simples (retângulos para blocos, barras minimalistas, círculos para bolas e power-ups) ajuda a facilitar a leitura dos elementos mesmo em situações mais caóticas, com múltiplas bolas e blocos sendo destruídos ao mesmo tempo.
- **Layout**:
	* Os blocos ficam no meio, criando uma zona de conflito onde as bolas transitam entre as duas barras. Além disso, as barras ocupam extremidades opostas da tela, deixando claro quem é responsável por cada lado e por qual bola, também há áreas livres para os power-ups caírem, fazendo com que a coleta seja um desafio extra que exige posicionamento cuidadoso da barra.
## 5. Reflexão e Aprendizados

[](https://github.com/InteliContent/M1/blob/main/UX-Design/Reinventando-Pong_Template.md#5-reflex%C3%A3o-e-aprendizados)

_Cada membro da dupla deve responder individualmente:_

1. Quais foram os maiores desafios enfrentados durante o processo de criação?
   Um maior desafio foi pensar na ideia, por conta do fator inovação, depois que a gente teve a ideia definitiva tudo fluiu melhor e a dupla conseguiu articular uma boa ideia

2. Que habilidades foram desenvolvidas ou aprimoradas ao longo da atividade?
   Trabalho em equipe, criatividade e a exploração prática dos contextos aprendidos em sala
---

## 6. Referências (se houver)

[](https://github.com/InteliContent/M1/blob/main/UX-Design/Reinventando-Pong_Template.md#6-refer%C3%AAncias-se-houver)

---

**📝 Formato de Entrega:**

- O relatório pode ser submetido no **GitHub** em **Markdown** `.md` ou como **PDF** `.pdf` **compartilhado via Drive**.
- **Nome do arquivo:** `RelatorioPong_Nome1-Nome2`

📌 **Prazo de entrega:** Sexta-feira, às 23h59.
