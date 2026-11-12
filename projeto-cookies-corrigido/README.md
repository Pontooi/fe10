# Projeto Cookies — versão final

Entrega do **Tema 10 — Cookies na Prática (Front-end na Prática)**.
O projeto está pronto e funcionando. O `sumario.html` mostra as escolhas do
projeto e os componentes rodando ao vivo.

## Como abrir

Abra **pelo Live Server**, não por duplo clique. O navegador bloqueia cookies
quando o arquivo é aberto via `file://`. No VS Code: botão direito em
`sumario.html` (ou `projeto-cookies.html`) → **Open with Live Server**.

## Escolhas do projeto

| Componente | Escolha |
|------------|---------|
| Ler cookies | `document.cookie` (singular) |
| Gravar tema | `max-age=3600; path=/; SameSite=Lax` |
| Apagar tema | `max-age=0; path=/; SameSite=Lax` |
| IDs do HTML | `getElementById("tema")` igual ao id do input |
| Entrega | Arquivo único HTML + CSS + JS |
| Segurança | `SameSite=Lax` em todos os cookies |

## Estrutura da entrega

```
projeto-cookies-corrigido/
├── projeto-cookies.html   # projeto completo, funcionando
├── sumario.html           # escolhas do projeto + demonstração rodando
└── README.md              # este resumo
```

## Como testar

1. Abra `sumario.html` com o Live Server.
2. Clique em **Gravar tema** — o cookie `tema` aparece na tabela.
3. Clique em **Apagar tema** — o cookie some da tabela.
4. Clique em **Ler cookies agora** — o terminal mostra os cookies reais.
5. Confira também em **F12 → Application → Storage → Cookies**.
