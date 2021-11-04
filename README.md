## Design Pattern - Proxy

- This is a continuation of: https://github.com/marciodegan/design-pattern-facade

### Notes:
- Proxy / Interceptador
- Caso um método seja demorado, como por exemplo, ele precise fazer uma chamada a uma api externa e essa api é lenta...podemos usar uma classe para guardar o valor em cache e reutilizar o resultado.
- Criamos um proxy para criar uma camada que vai "interceptar" as chamadas ao objeto original e com isso, é possivel fazer otimizações, validações, verificações...não só para performance.
- Podemos utilizar o padrão Proxy para interceptar classes e executar regras de segurança.
- More: https://refactoring.guru/design-patterns/proxy