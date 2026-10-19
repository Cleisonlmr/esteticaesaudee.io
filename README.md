# Clinic Estética e Saúde — Site

Site institucional de página única (HTML + CSS), sem dependências ou build.

## Estrutura
- `index.html` — página completa
- `assets/logo.png` — logo (fundo transparente)
- `.nojekyll` — desativa o processamento Jekyll do GitHub Pages

## Publicar no GitHub Pages
1. Crie um repositório no GitHub e envie estes arquivos para a raiz (branch `main`).
2. Vá em **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
4. Salve. O site ficará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Editar
- Link de agendamento: procure por `maapp.com.br/clinic` em `index.html`.
- Cores: variáveis no início do `<style>` (`--rose`, `--plum`, `--bg`...).
