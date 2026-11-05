# hub-confaf-config

Arquivos lidos pelo app **Hub CONFAF Brasil** para atualizar a lista sem gerar novo APK.

- `hub.json` — títulos, redes sociais e cards (sites). No app: ⚙ → "URL da lista remota".
- `update.json` — versão mais recente do app. No app: ⚙ → "URL de atualização do app". O app só avisa se `versionCode` for maior que o instalado.

URLs para colar no app:

```
https://raw.githubusercontent.com/britogabriel92/hub-confaf-config/main/hub.json
https://raw.githubusercontent.com/britogabriel92/hub-confaf-config/main/update.json
```

Este repositório é público: não coloque nada secreto aqui. Quem puder editar o `hub.json` controla os links do app.
Imagens `img/…` são as que já vêm dentro do app; para um site novo use o endereço https completo da imagem.
O GitHub guarda o arquivo em cache por alguns minutos depois de cada mudança.
