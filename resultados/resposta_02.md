O princípio **DRY** é um acrônimo para **"Don't Repeat Yourself"** (Não se repita). Conceituado por Andy Hunt e Dave Thomas no livro *The Pragmatic Programmer*, ele estabelece que cada pedaço de conhecimento ou funcionalidade em um projeto de software deve ter uma **representação única, inequívoca e autoritária** dentro do sistema.

### Significado e Implementação
O DRY propõe a **eliminação da duplicidade** e o incentivo ao **reaproveitamento de lógica**, tratando a repetição como um desperdício. Na prática, os desenvolvedores implementam esse princípio através de:

*   **Modularização e Abstração:** Extração da lógica principal em funções, classes ou módulos independentes que podem ser reutilizados em diferentes partes do sistema.
*   **Encapsulamento e Herança:** Criação de uma **classe base** com funcionalidades comuns (como uma entidade "Pessoa") para que outras classes (como "Jogador" e "Técnico") herdem esses comportamentos, evitando repetir o mesmo código.
*   **Utilitários Compartilhados:** Uso de arquivos de utilidade, como as *Helper classes*, para operações comuns a todo o projeto.
*   **Interfaces e Generics:** Estruturas que permitem criar códigos flexíveis que atendem a múltiplos contextos sem novas implementações idênticas.
*   **Unificação de Funções:** Em vez de ter funções separadas para tarefas semelhantes (como calcular área e perímetro de forma isolada), o DRY sugere uma única função coesa que realize os cálculos necessários e elimine redundâncias.

### Por que o DRY é importante?
A aplicação do princípio DRY é fundamental para a qualidade do software por diversos motivos:

1.  **Facilita a Manutenção:** Sem o DRY, uma manutenção simples pode exigir mudanças em várias classes ou arquivos simultaneamente. Com uma representação única, o desenvolvedor precisa alterar o código em apenas um lugar.
2.  **Garante a Consistência:** A repetição de código pode causar inconsistências e dificuldades na compreensão do sistema.
3.  **Melhora a Qualidade do Código:** Ajuda a construir um software mais **enxuto, limpo, fácil de depurar e entender**.
4.  **Aumenta a Eficiência e Escalabilidade:** Códigos estruturados sob este princípio são mais fáceis de escalar e reduzem o tempo gasto em depuração (*debugging*).

### Cuidados Necessários
Embora essencial, a aplicação do DRY exige **bom senso**. Quando levado ao extremo ou mal aplicado, pode resultar em um **acoplamento excessivo** (dependência exagerada entre as classes), o que acaba dificultando a leitura, o entendimento e a modificação do código no futuro. O ideal é que o código seja reaproveitado, mas mantenha a clareza sobre sua intenção original.