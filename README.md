# Plano de Estudos — Ciclo em Blocos

Página estática do plano de estudos (método: ciclo em blocos, 100% questões, escada de dificuldade D+0 → D+1 → D+2), com links diretos para os cadernos do TEC Concursos, timer com presets e contador da Regra do 6.

## ⚠️ Aviso de privacidade

O GitHub Pages gratuito é **público**: qualquer pessoa com o link (ou que encontre o repositório) pode ver a página. Não há login como no Cloudflare Access. Os links dos cadernos exigem a sua sessão do TEC para abrir, mas o conteúdo do plano (nome, rotina, matérias) fica visível. Se isso for um problema, use a versão do Cloudflare Pages + Access.

## Como publicar (pela interface web, sem instalar nada)

1. Crie uma conta em https://github.com (ou faça login).
2. Clique em **New repository** → nome sugerido: `plano-estudos` → marque **Public** → **Create repository**.
3. Na página do repositório: **Add file → Upload files** → arraste `index.html` e `.nojekyll` → **Commit changes**.
4. Vá em **Settings → Pages** → em *Build and deployment*, escolha **Deploy from a branch** → branch `main`, pasta `/ (root)` → **Save**.
5. Aguarde 1–2 minutos. A página fica em:
   `https://SEU-USUARIO.github.io/plano-estudos/`

## Como atualizar o plano

Substitua o `index.html`: na página do repositório, abra o arquivo → ícone de lápis (ou **Add file → Upload files** com o novo arquivo de mesmo nome) → **Commit changes**. A página atualiza sozinha em ~1 minuto, em todos os aparelhos.

## Estrutura

- `index.html` — a página completa (HTML, CSS e JS em um único arquivo, sem dependências além do Google Fonts)
- `.nojekyll` — desativa o processador Jekyll do GitHub Pages (evita interferência no HTML)
