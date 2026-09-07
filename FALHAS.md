# FALHAS — gpt6-astra

| data | o que quebrou | menor correção | prompt \| infra |
|---|---|---|---|
| 2026-09-07 | `yt-dlp --write-auto-sub` deu `HTTP 429 Too Many Requests` ao baixar a legenda automática do YouTube (fonte do curso) | passar `--cookies-from-browser "firefox:<perfil>"` e pedir só `en-orig` — baixou na primeira tentativa | infra |
