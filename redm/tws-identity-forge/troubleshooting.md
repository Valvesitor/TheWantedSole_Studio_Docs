# Troubleshooting

Use esta página para resolver problemas comuns do **TWS Identity Forge**.

## Studio abre, mas nada salva ou carrega

Verifique se a licença remota foi negada. Enquanto a validação falhar, eventos `tws:*` podem ficar bloqueados.

## Interface não abre

Confirme o `ensure` no `server.cfg`, erros no F8/console e teste o comando:

```console
/creator
```

## Roupas não aplicam ou ped fica estranho

Confira se `Config.MetapedResource` bate com o nome exato do seu resource de metaped e se ele inicia antes do Studio.

## Preview invisível ou muito longe

Use:

```console
/repositionpreview
```

Se persistir, ajuste ou desative `Config.AltarLuz`.

## Presets CS aparecem zerados

Confirme:

- A pasta `exports/cs_xml`.
- O padrão `cs_*.ymt.xml`.
- Se o resource foi reiniciado depois da alteração.
