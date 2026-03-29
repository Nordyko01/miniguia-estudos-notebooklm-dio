A principal diferença entre comentar o "o quê" e o "por quê" reside na finalidade da informação: enquanto o primeiro descreve a ação imediata do código, o segundo justifica a razão por trás dessa ação e a lógica escolhida.

Aqui estão os detalhes dessa distinção conforme as fontes:

### 1. Comentar o "O Quê" (O que o código faz)
*   **Foco:** Descreve a funcionalidade de cada parte ou o que uma seção específica está realizando.
*   **Quando usar:** É útil para explicar o **propósito de seções complexas**, equações difíceis ou funções específicas, servindo como um resumo para quem lê o código rapidamente.
*   **Ressalva:** Muitas vezes é considerado **redundante ou desnecessário**, pois o próprio código já deve ser escrito de forma clara o suficiente para comunicar sua função. Comentários que apenas repetem o que o código faz "poluem" o arquivo.

### 2. Comentar o "Por Quê" (A razão da decisão)
*   **Foco:** Explica o **motivo de uma decisão técnica**, a lógica por trás de uma abordagem ou por que uma solução foi escolhida em detrimento de outras.
*   **Importância:** É considerado uma **boa prática essencial**, pois o código mostra "como" algo funciona, mas não explica a intenção original do desenvolvedor.
*   **Benefícios:** Ajuda a preservar o conhecimento institucional, justifica escolhas complexas para futuros desenvolvedores (ou para você mesmo no futuro) e reduz erros, evitando que outros alterem a lógica sem entender sua motivação inicial.

### Resumo Comparativo
*   **"O Quê"** é a descrição da **implementação** (muitas vezes visível no código).
*   **"Por Quê"** é o fornecimento de **contexto e justificativa** (informação que o código sozinho não consegue transmitir).

As fontes sugerem que os desenvolvedores devem priorizar explicar o "por quê", mantendo o código limpo e autoexplicativo o suficiente para que o "o quê" seja óbvio sem a necessidade de anotações excessivas.