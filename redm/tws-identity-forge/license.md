# License

Quando a licença remota estiver ativa, configure a URL, chave, Steam do dono e HWID no `server.cfg`.

```cfg
setr tws_license_enabled "1"
set tws_license_validate_url "https://URL-QUE-TE-ENVIARAM/"
set tws_license_key "CHAVE-QUE-TE-ENVIARAM"
set tws_license_owner_steam "steam:1100001xxxxxxxx"
set tws_license_hwid "ID-UNICO-DO-SERVIDOR"
```

{% hint style="danger" %}
Sem essas linhas, ou se a validação falhar, o Studio pode abrir bloqueado ou não salvar/carregar dados.
{% endhint %}

## Problemas comuns de licença

| Problema | Possível causa |
| --- | --- |
| Pede Steam do dono | Falta `tws_license_owner_steam` ou o valor está incorreto. |
| Licença inválida | Confirme a URL e a chave com quem forneceu o script. |
| Studio não abre | Verifique mensagens em vermelho no console do servidor. |

## Checklist

- A URL termina com `/` quando exigido pelo endpoint.
- A chave está exatamente igual à enviada.
- A Steam do dono está no formato correto.
- O HWID foi copiado sem espaços extras.
- O servidor tem acesso HTTPS externo.
