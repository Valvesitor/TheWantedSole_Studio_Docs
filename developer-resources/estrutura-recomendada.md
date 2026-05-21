# Estrutura Recomendada

Quando tiver muitos scripts, mantenha sempre o mesmo padrão de IDs, pastas e menu lateral.

## Estrutura de pasta

```txt
redm/nome-do-script/
├─ README.md
├─ installation.md
├─ license.md
├─ usage.md
├─ configuration.md
└─ troubleshooting.md
```

## Estrutura no SUMMARY.md

```md
* [Nome do Script](redm/nome-do-script/README.md)
  * [Installation](redm/nome-do-script/installation.md)
  * [License](redm/nome-do-script/license.md)
  * [Usage](redm/nome-do-script/usage.md)
  * [Configuration](redm/nome-do-script/configuration.md)
  * [Troubleshooting](redm/nome-do-script/troubleshooting.md)
```

## Padrão recomendado

- Uma pasta por script.
- Uma página principal `README.md` para cada script.
- Subpáginas separadas para instalação, licença, uso, configuração e problemas.
- Nomes de arquivos sempre em minúsculo e sem espaço.
