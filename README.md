# Inteligência Artificial - UFRN

## Introdução
  O ser humano é capaz de perceber, compreender, prever e manipular o mundo a partir do uso da inteligência ("pensamento sábio") que foi adquirida ao longo da evolução. Algo que nós criamos como uma máquina, sera capaz de pensar? ser inteligente? 

"As máquinas podem pensar?" - Alan Turing,1950

Foi a partir desse questionamento que começou a pensar-se no conceito de Inteligência Artificial.
"Podemos assumir que o ser humano é inteligente. Portanto, se uma máquina fosse capaz de se comportar de tal forma que não pudéssemos distingui-la de um ser humano, essa máquina estaria demonstrando algum tipo de inteligência que, nesse caso, só poderia ser **inteligência aritifial** " - Alan Turing
Nesse raciocínio foi estabelecido o Teste de Ruring, que consistia em um ser humano entrevistando uma máquina, se a máquina apresentasse semelhanças nas respostas como a de um ser humano, era considerado uma inteligência artificial.

![image](https://github.com/user-attachments/assets/ebb12333-e1c0-4094-bafc-736d61ef3b4c)


**Inteligência Artificial** é “Automatização de atividades que associamos ao pensamento humano, como tomadas de 
decisão e resolução de problemas...” (Bellman, 1978)

![image](https://github.com/user-attachments/assets/e3c88e12-2e5c-48e8-93f5-8e300e579fe2)


## 1. Conceitos
### 1.1 Aprendizado de Máquinas
Desenvolvimento de algoritmos capazes de realizar tarefas complexas, de diferentes domínios, com base em dados. Aaprende a partir de um conjunto de experiência E, em relação a uma classe de tarefas T, com medida de 
desempenho P, se seu desempenho em T, medido por P, melhora com E.

  - Conjunto de Experiência (E) - Treinamento: Dados de pacientes, incluindo históricos médicos, resultados de exames, imagens de radiografias, etc.
  - Classe de Tarefas (T) - Melhoria Contínua: Diagnosticar doenças específicas, como câncer de pulmão, diabetes, ou doenças cardíacas.
  - Medida de Desempenho (P) - Avaliação: Precisão do diagnóstico, taxa de falsos positivos/negativos, tempo de processamento, etc.

A melhoria nos algoritmos impulsionou o desenvolvimento de IAs, de forma que houve mais coleta de dados para treinamento que geravam resultados práticos úteis. Os investidos perceberam e investiram em mais recursos computacionais.

**Aplicações**
![image](https://github.com/user-attachments/assets/4881ab16-f168-426d-91ee-680acb052694)

Assistentes Virtuais
![image](https://github.com/user-attachments/assets/fe0dcc8d-c7da-49f7-b5dc-550dd7662624)

Sistemas de recomendações
![image](https://github.com/user-attachments/assets/999fd7cd-b7fe-4077-9872-c6803fc81d5c)

Traduções, Carros Autônomos, Robótica, Medicina Personalizada, etc.

### 2.1 Agentes Inteligentes

**Agente:** É qualquer coisa que possa ser considerada capaz de perceber seu ambiente por meio de sensores e de agir sobre esse ambiente por meio de atuadores.

**Exemplo:**

       - Agente Humano
       Agentes: Olhos, língua, pele, ouvido, nariz
       Atuadores: Boca, mãos, braços, pernas

       - Agente robótico
       Agentes/ Sensores: Câmeras, detectores da faixa IR, microfone
       Atuadores: motores

       - Agente de Software
       Agentes/ Sensores: Sequência de tecla digitais, conteúdo de arquivos, pacotes de redes
       Atuadores: Apresenta algo no monitor, escreve em arquivos e envia pacotes de rede

**Conceitos Importantes**

  - **Racionalidade:**
    Agente racional é aquele que faz tudo certo. Método para medir o sucesso é verificando a medida de desempenho, critério de sucesso e projeção do denvolvimento a medida que o desempenho se adequa as circunstâncias.

    - **Medida de desempenho:** É a quantidade de ação feita em um único turno, como: qual a quantidade de sujeira aspirada em 8h., é verificado se foi indaqueado ou adequado, recompensando o agengete por deixar o chão limpo ao longo do tempo e verificando a quantidade de sujeira aspirada e o gasto de energia.

   - **Percepção:** Referência de entradas em um dado instante
  
   - **Função do agente:** Mapeia qualquer sequência de percepção para executar uma ação (TABULAÇÃO)
  
   - **Programa do agente:** Implementação concreta, executa um sistema físico.

  **Exemplo de Aplicação:**
  
  O mundo do aspirador de pó:
  
  - Função de agentes:
    
![image](https://github.com/user-attachments/assets/3e665a14-4324-4e31-9d08-b20f4a554f82)


| Sequência de percepção    | Ação |
|---------------------------|--------|
| [A, Limpo]                | Direita|
| [A, Sujo]                 | Sugar  |
| [B, Limpo]                | Esquerda |
| [B, Sujo]                 | Sugar |
| [A, Limpo], [A, Limpo]    | Direita |
| [A, Limpo], [A, Sujo]     | Sugar   |
| [A, Limpo], [B, Limpo], [A, Limpo] | Direita |
| [A, Limpo], [B, Limpo], [A, Sujo] | Sugar |

    
  - Programa do agente:
    
        **função** AGENTE-ASPIRADOR-DE-PÓ-REATIVO([posição,situação]) **retorna** uma ação*
        **se** situação = Sujo **então retorna** Aspirar
        **senão se** posição = A **então retorna** Direita
        **se não se** posição = B **então retorna** Esquerda


    A maneira correta de definir a funçao e o programa agente é
    O que torna um agente bom ou ruim, inteligente ou estúpido
     

