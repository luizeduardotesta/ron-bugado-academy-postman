### Projeto de automação com Postman da Squad Ron Bugado

Projeto de automação com Postman.

## Instalação

```bash
    npm install -g newman
    npm install -g newman-reporter-htmlextra
```

## Execução com report html extra

```bash
    newman run config.json -e env-ron-bugado.json -g env-global.json
    newman run users.json -e env-ron-bugado.json -g env-global.json
    newman run company.json -e env-ron-bugado.json -g env-global.json
    newman run board.json -e env-ron-bugado.json -g env-global.json
    newman run costCenter.json -e env-ron-bugado.json -g env-global.json
    newman run department.json -e env-ron-bugado.json -g env-global.json
```
