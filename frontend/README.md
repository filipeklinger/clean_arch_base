[voltar](../README.md)
# Clean Arch Base Frontend
Estrutura base de pastas pensada em uma arquitetura com um design de software nos moldes do Clean Code
Esta é uma simplificação da Onion Arch, descartando todas as partes que aumentavam a complexidade do projeto.

Essa organização foi pensada para `React`/`Typescript` mas pode ser reutilizada para outros tipos de linguagens/frameworks.

## estrutura de pastas

```bash
─── src
    ├── assets
    ├── components
    ├── model
    ├── pages
    └── styles
```
- src: por default todo o código do projeto deve estar nessa pasta
- **assets**: todo arquivo ("não código") que faz parte do projeto deve estar nessa pasta, ex: imagens, PDF, docs...


- **components**: componentes de UI/UX criados para a aplicação. Ex.: Button, table, card..


- **model**: modelos de usados para trafegar dados, de preferencia somente Interfaces/classes abstratas. Por ex ao buscar um dado de cliente na API vai ser retornado um obj que podemos chamar de IClient


- **pages**: agrupamento de componentes que será renderizado ao acessar uma rota


- **styles**: folhas de estylo css/ configurações de tema da aplicação