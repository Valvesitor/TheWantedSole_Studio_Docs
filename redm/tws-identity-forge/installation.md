# Installation

Copie a pasta do resource para `resources/` ou uma subpasta organizada do seu servidor.

No `server.cfg`, adicione depois do resource de metaped:

```cfg
ensure MetaPedAssets
ensure TWS_Identity_Forge
```

{% hint style="warning" %}
O nome `MetaPedAssets` deve ser idêntico ao definido em `shared/config.lua` na opção `Config.MetapedResource`.
{% endhint %}

Para reiniciar apenas o resource pelo console:

```console
ensure TWS_Identity_Forge
```

## Ordem recomendada

1. Coloque o resource na pasta correta.
2. Verifique o nome exato da pasta.
3. Configure o `server.cfg`.
4. Inicie o resource de metaped antes do Identity Forge.
5. Reinicie o servidor ou use `ensure TWS_Identity_Forge` no console.
