# Projeto de Pesquisa: **Miniguia-Estudos-Notebooklm-Dio**
#Para quem quer aprender sobre boas práticas e organização de código.

Este repositório contém os estudos realizados utilizando o **NotebookLM**.

## Metodologia de Pesquisa
Para extrair os melhores insights das fontes técnicas, utilizei a seguinte estrutura:


* **Pergunta (Prompt):** Quais são os quatro atributos principais de qualidade de software segundo Sommerville?" (Localizado em `/prompts/perguntas_frequentes.md`)
* **Contexto:** Baseado nos documentos técnicos de especificação (https://en.wikipedia.org/wiki/Coding_best_practices).
* **Resposta (Insight):** Segundo Ian Sommerville, existem **quatro atributos principais** (ou generalizados) de qualidade de software que não se referem ao que um programa faz, mas sim ao quão bem ele desempenha suas funções. Esses atributos são:

1.  **Manutenibilidade (Maintainability):** Refere-se à facilidade com que o software pode ser modificado para atender a novas necessidades dos clientes ou mudanças no ambiente.
2.  **Confiabilidade (Dependability):** Relaciona-se à capacidade do software de não falhar em caso de erros e de ser seguro, garantindo que o sistema se comporte conforme o esperado.
3.  **Eficiência (Efficiency):** Diz respeito ao uso otimizado de recursos pelo software, como tempo de resposta e utilização de memória, sem desperdícios desnecessários.
4.  **Usabilidade (Usability):** Trata da facilidade com que os usuários podem utilizar o software, incluindo a clareza da interface e da documentação.

Esses atributos são fundamentais porque, enquanto a funcionalidade inicial é importante, o sucesso a longo prazo de um software depende de sua robustez e facilidade de manutenção.(Localizado em `/respostas/resposta_01.md`)


* **Pergunta (Prompt):** O que significa o acrônimo SOLID e qual é seu objetivo principal?(Localizado em `/prompts/perguntas_frequentes.md`)
* **Contexto:** Baseado nos documentos técnicos de especificação(https://medium.com/@josueparra2892/20-best-programming-practices-407df688b96e)
* **Resposta (Insight):** O acrônimo **SOLID** refere-se a cinco princípios fundamentais da programação orientada a objetos, que são: **Single Responsibility** (Responsabilidade Única), **Open/Closed** (Aberto/Fechado), **Liskov Substitution** (Substituição de Liskov), **Interface Segregation** (Segregação de Interface) e **Dependency Inversion** (Inversão de Dependência).

O seu **objetivo principal** é atuar como uma base ou "pedra angular" para o desenvolvimento de softwares que sejam **escaláveis** e de **fácil manutenção**. Ao seguir esses princípios, os desenvolvedores conseguem criar códigos mais robustos, facilitando a evolução do sistema e a colaboração entre equipes, uma vez que a estrutura se torna mais clara e menos propensa a erros durante alterações futuras.(Localizado em `/respostas/resposta_06.md`)


* **Pergunta (Prompt):** Qual é a recomendação sobre o uso de variáveis globais?(Localizado em `/prompts/perguntas_frequentes.md`)
* **Contexto:** Baseado nos documentos técnicos de especificação(https://medium.com/@josueparra2892/20-best-programming-practices-407df688b96e)
* **Resposta (Insight):**A recomendação fundamental é **reduzir as dependências globais** no desenvolvimento de software. O uso frequente de variáveis e instâncias globais pode fazer com que o desenvolvedor fique preso em dependências complexas e enfrente um gerenciamento de estado confuso.

Para evitar esses problemas, as fontes sugerem as seguintes práticas:

*   **Priorize o estado localizado:** O código de qualidade deve contar com estados locais e utilizar a **passagem de parâmetros** em vez de recorrer a globais.
*   **Funções sem efeitos colaterais:** É recomendado que as funções sejam "side-effect free", ou seja, não causem alterações inesperadas fora de seu escopo local.
*   **Evite valores "hard-coded":** Para garantir a portabilidade, o código não deve conter valores fixos (literais) para parâmetros ambientais, como caminhos de arquivos, nomes de host ou URLs. Esses elementos devem ser parametrizados e configurados fora da aplicação (em arquivos de propriedades ou bancos de dados), seguindo o princípio de **"ponto único de definição" (SPOD)**.
*   **Segurança e Auditoria:** No que diz respeito a dependências externas e códigos de terceiros, deve-se realizar **auditorias regulares** para assegurar que não existam vulnerabilidades conhecidas, além de manter todas as dependências rigorosamente atualizadas.(Localizado em `/respostas/resposta_07.md`)

---
*Organizado por Jorge C. Nunes*
