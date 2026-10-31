# Projeto 01 – Currículo pessoal (somente HTML)

Crie o arquivo `index.html` com uma página de currículo sobre você (ou um personagem fictício).
Coloque também uma imagem na mesma pasta (ex.: `foto.jpg`).

**Requisitos**

1. **R1** – O arquivo começa com `<!DOCTYPE html>` e a tag `<html>` tem `lang="pt-BR"`.
2. **R2** – O `<head>` tem `<meta charset="UTF-8">` e um `<title>` preenchido.
3. **R3** – Existe exatamente um `<header>`, um `<main>` e um `<footer>`.
4. **R4** – Existe um único `<h1>` com seu nome, dentro do `<header>`.
5. **R5** – O `<main>` tem pelo menos 3 `<h2>` com texto (ex.: Sobre mim, Habilidades, Formação).
6. **R6** – Existe um parágrafo `<p>` com pelo menos 20 palavras.
7. **R7** – Existe uma `<img>` com `src` válido (o arquivo precisa existir) e `alt` descritivo.
8. **R8** – Existe uma lista `<ul>` com pelo menos 3 `<li>`.
9. **R9** – Existe uma lista `<ol>` com pelo menos 2 `<li>`.
10. **R10** – Existe um link externo `https://` com `target="_blank"` e `rel="noopener"`.
11. **R11** – Existe um link `mailto:` com um e-mail válido.
12. **R12** – Sem CSS: não use o atributo `style` nem a tag `<style>`.

---

## Como entregar

1. Clone o repositório: `git clone https://github.com/NicolasDimitri/web-01-curriculo.git` e entre na pasta.
2. Crie uma branch: `git switch -c meu-projeto`
3. Crie os arquivos pedidos aqui na raiz, ao lado deste README.
4. `git add .` → `git commit -m "mensagem"` → `git push -u origin meu-projeto`
5. No GitHub, clique em **Compare & pull request** → **Create pull request**.
6. Um comentário automático aparece no PR com uma **tabela de requisitos**, cada um com ✅ (passou) ou ❌ (não passou) e a dica do que falta.
   Corrija, faça novo commit + `git push` e o comentário é atualizado.
7. Com tudo ✅, sua entrega está concluída. **O PR não será mesclado na `main`**: ele fica aberto só para a avaliação e para o instrutor revisar.

## Testar no seu computador (opcional)

```bash
npm install
npx playwright install --with-deps chromium   # só na primeira vez
npm test
```

> Não altere as pastas `tests/`, `scripts/` e `.github/`.
