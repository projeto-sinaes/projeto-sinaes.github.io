# Braço Hidráulico Automatizado

Esta sendo desenvolvido para ser apresentado na **IX IFTECH (Campus Paranavaí - 2026)**, este projeto une os princípios mecânicos da força da água aos conceitos modernos de automação industrial e robótica. 

Ele demonstra, em escala reduzida, a mesma tecnologia hidráulica utilizada por máquinas pesadas da construção civil, mas controlada de forma inteligente e eletrônica.

---

## O que é o Protótipo?
O protótipo é um braço mecânico articulado que utiliza fluidos sob pressão para gerar movimento. Diferente dos braços mecânicos tradicionais operados puramente por cordinhas ou motores barulhentos, este projeto utiliza a transmissão de pressão por líquidos para realizar tarefas de manipulação espacial com excelente precisão e suavidade.

---

## Como Funciona? (Passo a Passo)

A engenharia do braço combina mecânica de fluidos e programação embarcada:

1. **A Transmissão de Força (Seringas):** O braço conta com um sistema de seringas interligadas por mangueiras de silicone que atuam como cilindros hidráulicos. Ao injetar líquido em uma ponta, o pistão do outro lado se expande ou contrai, movendo a articulação do braço.
2. **As Bombas Eletrônicas:** Em vez de usar as mãos para empurrar o líquido, o sistema conta com bombas d'água (que empurram o líquido).
3. **O Cérebro do Robô:** Um microcontrolador ESP32 é o encarregado de processar os comandos do usuário. Ele gerencia quando e qual bomba deve ligar para direcionar o fluxo de água para a junta correta.
4. **Controle Manual Preciso:** O operador comanda as articulações usando potenciômetros analógicos simples (botões giratórios). O circuito eletrônico traduz o giro do botão em movimentos físicos correspondentes no braço, proporcionando uma operação intuitiva.

---

## O que este projeto ensina na prática?
* **Princípio de Pascal:** Como a pressão aplicada a um fluido em um ponto fechado é transmitida integralmente para todos os outros pontos (a base de toda a hidráulica moderna).
* **Hidrodinâmica:** O comportamento do fluxo de líquidos em canais fechados e sistemas de bombeamento.
* **Automação e Robótica:** A integração de atuadores mecânicos, sistemas hidráulicos e controle digital.

---

## Destaques e Diferenciais
* **Controle Eletrônico de Fluidos:** A automação do fluxo hidráulico usando bombas traz uma abordagem inovadora para projetos escolares de baixo custo.
* **Modularidade e Segurança:** Utiliza água como fluido de trabalho em baixas pressões, tornando o experimento completamente seguro, limpo e adequado para demonstrações em salas de aula e feiras de ciências.
* **Abordagem Multidisciplinar:** Integração perfeita entre disciplinas como física de fluidos, desenho mecânico, programação e circuitos eletroeletrônicos.
