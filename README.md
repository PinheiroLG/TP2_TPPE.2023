# Trabalho Prático 2 da disciplina Técnicas de Programação para Plataformas Emergentes

### Participantes

| Aluno                                 | Github                                               | Matrícula |
|---------------------------------------|------------------------------------------------------|-----------|
| Ian Pereira de Sousa Rocha            | [@IanPSRocha](https://github.com/IanPSRocha)         | 160124778 |
| João Victor Max Bisinotti de Oliveira | [@joaobisi](https://github.com/joaobisi)             | 170069991 |
| luiz Gustavo Dias Paes Pinheiro       | [@PinheiroLG](https://github.com/PinheiroLG)         | 140169784 |
| Vinicius Edwardo Pereira Oliveira     | [@viniciused26](https://github.com/viniciused26)     | 160147816 |
| Paulo Henrique Costa Gontijo          | [@paulohgontijoo](https://github.com/paulohgontijoo) | 150143800 |
| André Goretti Motta                   | [@AGoretti](https://github.com/AGoretti)             | 160112028 |
  
Este trabalho é o Trabalho 2 da disciplina de Técnicas de programação para Plataformas Emergentes, primeiro semestre de 2023 e tem como propósito analisar e explorar cinco das nove características essenciais de um projeto de software de qualidade mencionadas por Fowler. A seguir, serão apresentadas de forma concisa as cinco características escolhidas para análise detalhada.

* Boa documentação;
* Extensibilidade;
* Ausência de duplicidade no código;
* ?
* ?

## Boa documentação

### 1. Descrição
A documentação de um projeto de software desempenha um papel fundamental em sua sustentabilidade a longo prazo. Ela atua como um manual detalhado e compreensível, fornecendo orientações para entender, manter, colaborar e expandir o software. A documentação deve ser concisa, refletindo a simplicidade do projeto em sua clareza, organização e objetividade.

### 2. Efeitos no código:
* **Estrutura:** A presença de uma documentação adequada contribui para uma estrutura de projeto mais organizada e bem definida. Isso ocorre devido à inclusão de elementos como diagramas, fluxos de trabalho e uma visão geral da arquitetura, que auxiliam na compreensão de como os diversos componentes do sistema se inter-relacionam.
Ao apresentar uma visão geral da estrutura, a documentação facilita o entendimento dos relacionamentos entre módulos e partes do código, tornando mais fácil para os desenvolvedores navegarem pelo projeto e localizarem as informações relevantes.
* **Claridade:** A existência de uma documentação clara assegura uma compreensão adequada das funcionalidades, APIs e comportamentos do software. Essa clareza é essencial para evitar ambiguidades e interpretações equivocadas que poderiam resultar em erros de implementação ou uso inadequado. Uma documentação precisa e abrangente é um fator crucial para garantir que todos os aspectos do software sejam corretamente entendidos e utilizados.
* **Coesão:** A documentação adequada desempenha um papel crucial na promoção da coesão dentro de um projeto de software. Ao fornecer uma documentação clara e abrangente dos componentes, suas finalidades e responsabilidades ficam nitidamente estabelecidas. Isso incentiva os desenvolvedores a aderirem ao princípio de "alta coesão", onde cada módulo possui uma função específica e bem definida, resultando em uma redução do acoplamento entre diferentes partes do código. Aprimorar a coesão geralmente leva a um código mais organizado e de fácil manutenção, pois as responsabilidades são distribuídas de maneira mais eficiente. Isso significa que cada componente possui um propósito claro e contribui de forma significativa para o funcionamento do sistema como um todo. Com uma documentação adequada, os desenvolvedores podem entender facilmente a finalidade de cada componente e como eles se relacionam entre si, resultando em um código mais coeso e sustentável ao longo do tempo.
* **Acoplamento:** A documentação exerce influência sobre o acoplamento, que é a dependência entre as diferentes partes do software. Quanto mais clara e detalhada a documentação, mais fácil se torna compreender a interação entre os módulos. Ao compreender os pontos de acoplamento, os desenvolvedores podem tomar decisões embasadas para reduzir o acoplamento indesejado e promover um design mais flexível e modular. Ademais, a documentação que descreve os requisitos de interface e os contratos entre os módulos desempenha um papel crucial na prevenção de problemas de compatibilidade e alterações incompatíveis decorrentes de mudanças não documentadas. Isso significa que a documentação clara e precisa estabelece diretrizes que ajudam a evitar conflitos e asseguram que as mudanças realizadas no software sejam compatíveis e não prejudiquem o funcionamento adequado do sistema como um todo.

### 3. Relação com os maus cheiros definidos por Fowler:
Uma documentação de qualidade desempenha um papel fundamental na identificação, prevenção e correção de maus cheiros de código. Os maus cheiros de código são indícios de problemas potenciais no design e implementação do software, sugerindo a necessidade de refatoração. É possível observar que, quando a documentação é insuficiente, os programadores tendem a preencher essa lacuna com comentários excessivos no código, na tentativa de explicar partes complexas ou obscuras. No entanto, esses comentários podem se tornar rapidamente obsoletos e não refletir mais o estado atual do código, resultando em informações incorretas. Uma documentação de qualidade fornece explicações claras e detalhadas, diminuindo a necessidade de comentários excessivos e aprimorando a compreensão global do código. Além disso, a falta de uma documentação adequada pode levar à criação de métodos ou classes excessivamente complexos, uma vez que não há uma visão clara dos objetivos de cada elemento. Com uma documentação completa, é mais fácil identificar métodos ou classes com complexidade desnecessária, permitindo que os desenvolvedores simplifiquem a lógica, dividam tarefas complexas em etapas mais simples e, assim, melhorem a legibilidade do código. Dessa forma, a documentação atua como uma ferramenta valiosa para melhorar a qualidade e a manutenibilidade do software.

### 4. Exemplo de operação de refatoração capaz de levar o projeto de código e ter uma boa documentação:
A técnica conhecida como "Extração de Método" envolve a criação de um novo método a partir de um trecho de código existente, onde a lógica relacionada é agrupada em uma única função com um nome significativo. Essa prática não apenas aprimora a clareza e legibilidade do código, mas também tem um impacto positivo na qualidade da documentação do projeto. A extração de método facilita a compreensão do propósito e funcionamento da função para outros desenvolvedores, promovendo uma colaboração mais efetiva no projeto e auxiliando na manutenção futura. Além disso, ao utilizar nomes adequados para métodos e argumentos, a documentação se torna mais legível, simplificando a compreensão do código e evitando a necessidade de comentários excessivos. Essa abordagem contribui para a melhoria geral da documentação, tornando-a mais eficiente e eficaz na comunicação das funcionalidades do software.
