# Convars

Convars úteis para configuração e licença.

| Convar | Descrição |
| --- | --- |
| `tws_license_enabled` | Ativa ou desativa a validação remota de licença. |
| `tws_license_validate_url` | URL do Worker/endpoint de validação. |
| `tws_license_key` | Chave fornecida ao comprador. |
| `tws_license_owner_steam` | Steam do dono do servidor. |
| `tws_license_hwid` | Identificador fixo para vincular a licença ao servidor. |

## Exemplo

```cfg
setr tws_license_enabled "1"
set tws_license_validate_url "https://URL-QUE-TE-ENVIARAM/"
set tws_license_key "CHAVE-QUE-TE-ENVIARAM"
set tws_license_owner_steam "steam:1100001xxxxxxxx"
set tws_license_hwid "ID-UNICO-DO-SERVIDOR"
```
