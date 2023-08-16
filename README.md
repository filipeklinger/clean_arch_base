# Clean Arch Base
Estrutura base de pastas pensada em uma arquitetura com um design de software nos moldes do Clean Code.
Esse projeto foi pensado para ser utilizado por um sistema `Web` com o conceito de `client-side`/`server-side`.

Essa é uma arquitetura simplificada para projetos pequenos a medios, projetos grandes podem ser escalados mas vão requerer alguma arquitetura adicional.

## Monorepo
A ideia é que a equipe consiga gerenciar o projeto todo de forma facil. Como estamos pensando numa arquitetura `cliente`/`servidor` o projeto é dividido em 2 grandes seções `Backend`/`Frontend`.
Em varios projetos acabamos utilizando um repositório para cada uma das seções.

Para equipes menores ou que precisam de códigos mais integrados acaba sendo mais complexo gerenciar N repositórios. A ideia do monorepo é ter num lugar tudo q é necessário para o sistema subir.
Diferente de um projeto monolitico ainda temos N projetos porem em apenas 1 repositório de código.

![monorepo multirepo](./docs/monorepo_multirepo.png)

Veja os docs especificos para o [back](./backend/README.md)

Veja os docs especificos para o [Front](./frontend/README.md)