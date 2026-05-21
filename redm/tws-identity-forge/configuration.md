# Configuration

Esta página reúne as principais opções de configuração do **TWS Identity Forge**.

## Opções principais

| Opção | Descrição |
| --- | --- |
| `Config.Locale` | Idioma padrão: `pt-br`, `en-us` ou `es-es`. |
| `Config.OpenKey` | Hash do controle para abrir/fechar com tecla. Padrão: J. |
| `Config.MetapedResource` | Nome exato do resource que aplica outfits no servidor. |
| `Config.OutfitSlots` | Número de slots de outfit por jogador. |
| `Config.MaxXml` | Limite de tamanho para XML nas operações do servidor. |
| `Config.Debug` | Logs extras no cliente. Deixe `false` em produção. |
| `Config.License` | Configuração alternativa para URL, chave e Steam do dono. |

## Presets CS

- Arquivos no padrão `cs_*.ymt.xml`.
- Local esperado: `exports/cs_xml` dentro de `TWS_Identity_Forge`.
- Na interface, use projetos/presets CS para atualizar a lista e carregar presets.

{% hint style="info" %}
Depois de adicionar novos presets CS, reinicie o resource ou use a função de atualização disponível na interface.
{% endhint %}
