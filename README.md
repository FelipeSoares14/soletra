# Soletra

POC de reconhecimento do alfabeto manual (ASL e Libras) pela câmera, direto no navegador.

- Site: https://felipesoares14.github.io/soletra/
- Contas e gestos compartilhados: PocketBase (`pocketbase/gestures-collection.json` tem a tabela e as regras de acesso).

## Configurar o PocketBase
1. No painel do PocketBase (`/_/`), vá em **Settings → Import collections**.
2. Cole o conteúdo de `pocketbase/gestures-collection.json`, ative **Merge** e confirme.
3. O endereço do servidor fica na constante `PB_URL` dentro do `index.html`.

Nunca coloque arquivos `.env` ou senhas neste repositório: o site é público.
