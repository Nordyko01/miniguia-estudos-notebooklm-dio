A recomendação fundamental é **reduzir as dependências globais** no desenvolvimento de software. O uso frequente de variáveis e instâncias globais pode fazer com que o desenvolvedor fique preso em dependências complexas e enfrente um gerenciamento de estado confuso.

Para evitar esses problemas, as fontes sugerem as seguintes práticas:

*   **Priorize o estado localizado:** O código de qualidade deve contar com estados locais e utilizar a **passagem de parâmetros** em vez de recorrer a globais.
*   **Funções sem efeitos colaterais:** É recomendado que as funções sejam "side-effect free", ou seja, não causem alterações inesperadas fora de seu escopo local.
*   **Evite valores "hard-coded":** Para garantir a portabilidade, o código não deve conter valores fixos (literais) para parâmetros ambientais, como caminhos de arquivos, nomes de host ou URLs. Esses elementos devem ser parametrizados e configurados fora da aplicação (em arquivos de propriedades ou bancos de dados), seguindo o princípio de **"ponto único de definição" (SPOD)**.
*   **Segurança e Auditoria:** No que diz respeito a dependências externas e códigos de terceiros, deve-se realizar **auditorias regulares** para assegurar que não existam vulnerabilidades conhecidas, além de manter todas as dependências rigorosamente atualizadas.