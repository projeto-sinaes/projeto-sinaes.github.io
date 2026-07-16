# Experimento de Queda Livre Automatizado

Este protótipo foi desenvolvido como um protótipo educacional interativo para a **IX IFTECH (Campus Paranavaí - 2026)**. Nosso objetivo é transformar a maneira como conceitos abstratos da física de Newton são ensinados nas escolas, substituindo as decorebas de fórmulas por uma experiência prática, visual e altamente tecnológica.

A proposta une a **Mecatrônica** e a **Física** em um único sistema capaz de medir e demonstrar a aceleração da gravidade de forma extremamente precisa e automatizada.

---

## O que é o Protótipo?
Em salas de aula tradicionais, estudar a gravidade e o Movimento Retilíneo Uniformemente Variado (MRUV) costuma se limitar a resolver exercícios teóricos no papel. Este protótipo quebra essa barreira ao criar um ambiente físico de testes onde os estudantes podem observar um eletroimã soltar uma esfera metálica e ver os dados de tempo, velocidade e aceleração serem calculados instantaneamente por sensores eletrônicos.

---

## Como funciona? (Passo a Passo)

O funcionamento do sistema é simples de entender, mas esconde uma engenharia de controle muito interessante por trás:

1. **A Suspensão:** Uma esfera metálica é mantida presa no topo de uma torre vertical por meio de um eletroímã (um imã ativado por eletricidade).
2. **O Disparo:** Ao comando do sistema controlado pelo microcontrolador ESP32, a corrente do eletroímã é cortada instantaneamente, dando início à queda livre da esfera.
3. **A Captura de Dados no Percurso:** Ao longo da estrutura vertical, sensores ultrassônicos estão posicionados de forma estratégica. Quando a esfera passa por eles, os sensores "enxergam" a bolinha sem tocá-la e registram o instante exato da passagem.
4. **O Impacto Final:** Na base da torre, a esfera colide com uma plataforma equipada com um sensor de toque, marcando o fim milimétrico do tempo de descida.
5. **O Processamento:** O ESP32 recolhe todas essas frações de segundo e calcula a velocidade em cada ponto, gerando dados gráficos que mostram a gravidade agindo sobre o corpo e expondo estes gráficos e resultados em um pequeno display LCD TFT.

---

## O que este projeto ensina na prática?
* **Aceleração Gravitacional ($g$):** Prova empírica de que a gravidade atrai corpos em queda livre a uma taxa constante próxima a $9.8 m/s^2$.
* **Cinemática Prática:** Demonstração visual e real das equações do MRUV.
* **Tecnologia Aplicada:** Como sensores ultrassônicos e microcontroladores podem ser integrados para criar instrumentos de medição precisos.

---

## Destaques e Diferenciais
* **Precisão Sem Contato:** O uso de sensores ultrassônicos garante que o movimento da esfera não seja desacelerado por atritos mecânicos durante a medição[cite: 1].
* **Baixo Custo de Produção:** Utiliza componentes eletrônicos acessíveis, tornando viável a replicação em escolas públicas e laboratórios de ciências de menor orçamento[cite: 1].
* **Compromisso Social (ODS 4):** Alinhado à agenda de **Educação de Qualidade da ONU**, estimulando o interesse de jovens estudantes pelas áreas de tecnologia e ciência[cite: 1].
