# Agenda Online da Igreja

Projeto independente, gratuito, hospedado em GitHub Pages, sem Supabase e sem relação com o AvaliaMente.

## Administração
Entre na conta autorizada do GitHub, abra `eventos.json`, use **Edit** e **Commit changes** para criar ou editar eventos. Os campos são `id`, `data` (`AAAA-MM-DD`), `horario` (`HH:MM`), `titulo`, `ministrante`, `categoria` (`louvor`, `oração`, `congresso`, `especial`), `imagem` e `descricao`.

Fotos ou cartões podem ser enviados pelo GitHub à pasta `imagens/` e referenciados no campo `imagem`. Enquanto a imagem não estiver no repositório, o cartão textual aparece no lugar.

## Publicação
Em Settings → Pages → Build and deployment, selecione **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve. Endereço previsto: https://julianosantospr.github.io/agenda-igreja/ (verifique no painel Pages).

O site é público, mas a edição requer permissão na conta GitHub. Nunca coloque senhas, CPF ou dados sensíveis neste repositório.
