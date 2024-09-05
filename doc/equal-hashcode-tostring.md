## Métodos equals(), hashCode() e toString()

- Muitos frameworks e bibliotecas Java, incluindo JPA, dependem desses métodos para funcionar corretamente. Portanto, é uma prática recomendada implementá-los adequadamente em suas classes de entidade JPA.

- Os métodos equals(), hashCode() e toString() são fundamentais em Java, e é uma boa prática implementá-los em classes de entidade JPA por várias razões:

    - equals(): O método equals() é usado para comparar se dois objetos são iguais. Ao implementá-lo, você pode comparar duas instâncias de uma entidade JPA com base em critérios específicos, como a igualdade de identificadores ou outras propriedades relevantes.

    - hashCode(): O método hashCode() é usado para gerar um valor numérico (hash) que representa exclusivamente um objeto.

        - É essencial para estruturas de dados que dependem de hashes, como HashMaps e HashSets. Ao implementá-lo corretamente, você garante que as entidades JPA possam ser usadas de forma eficiente em coleções que usam hashing para pesquisa e armazenamento.

    - toString(): O método toString() é usado para fornecer uma representação de string legível de um objeto.

        - É útil para depuração e registro de informações. Ao implementá-lo, você pode controlar como uma entidade JPA é exibida quando convertida em string. Esse não seria um método obrigatório, ele acaba sendo mais útil para questões de log e depuração.