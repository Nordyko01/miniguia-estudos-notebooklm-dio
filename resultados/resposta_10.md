**"Code smells"** são indicadores ou sintomas de que algo pode estar errado ou "estragado" na implementação do código-fonte, funcionando como um sinal de alerta para desenvolvedores. Eles não são necessariamente erros ou bugs que impedem o funcionamento do programa, mas sim características que sugerem problemas de design, má estruturação ou falta de clareza, o que pode dificultar a manutenção e a evolução do software no futuro.

Para corrigir esses problemas, a principal prática utilizada é a **refatoração**. A refatoração consiste em **alterar a estrutura interna do código para torná-lo mais limpo e organizado, sem modificar sua funcionalidade externa ou comportamento esperado**.

Abaixo, detalho como identificar e corrigir os principais "code smells" com base nas fontes:

### Principais "Code Smells" e suas Correções

*   **Duplicação de Código:** Ocorre quando trechos idênticos ou muito semelhantes aparecem em vários lugares.
    *   **Como corrigir:** Aplique o princípio **DRY (Don't Repeat Yourself)**, extraindo a lógica repetida para uma única função, classe ou módulo reutilizável.
*   **Nomenclatura Confusa ou Não Expressiva:** Uso de nomes genéricos (como `n`, `x` ou `funcao1`) que não comunicam a intenção do código.
    *   **Como corrigir:** Substitua por **nomes significativos e descritivos** para variáveis, funções e classes, facilitando a leitura como se fosse uma "prosa bem escrita".
*   **Complexidade Excessiva e Lógica Confusa:** Blocos de código gigantescos, funções com muitas responsabilidades ou lógica desnecessariamente complicada para tarefas simples.
    *   **Como corrigir:** Divida o problema em etapas menores e transforme blocos grandes em **funções pequenas e coesas**, garantindo que cada uma tenha uma única responsabilidade clara.
*   **Código "Sujo" ou Desorganizado:** Falta de indentação, espaçamento inadequado ou ausência de uma estrutura lógica clara.
    *   **Como corrigir:** Adote padrões de formatação consistentes e utilize **Clean Code** (Código Limpo) para garantir que a lógica faça sentido intuitivamente.

### Estratégias Gerais de Prevenção e Correção

1.  **Revisão de Código (Code Review):** Envolver outros desenvolvedores na análise do código ajuda a identificar "smells" que testes automatizados podem não detectar, além de reduzir a dívida técnica.
2.  **Refatoração Contínua:** Não espere o problema crescer; identifique e corrija os problemas o mais cedo possível para manter o código sustentável.
3.  **Testes Automatizados:** Antes de iniciar uma refatoração para corrigir um "code smell", certifique-se de ter **testes unitários** robustos; isso elimina o medo de introduzir novos erros ao melhorar a estrutura do código.
4.  **Uso de Princípios de Engenharia:** Adotar princípios como o **SOLID** ajuda a escrever códigos que escalam melhor e são naturalmente menos propensos a "smells" de design complexo.