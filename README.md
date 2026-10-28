# Site pessoal – Gustavo Silveira Silva (versão com várias páginas)

Exemplo de site pessoal feito **somente com HTML e CSS** para a turma
**HTML e CSS – Criação de Websites (202600084) – Senac PR**.

Nesta versão, cada item do menu abre **uma página própria**.

## Estrutura

```
index.html          → página inicial (perfil + atalhos)
sobre.html          → sobre mim e formação
experiencia.html    → linha do tempo profissional
competencias.html   → competências em etiquetas
projetos.html       → projetos em grade (Grid)
contato.html        → LinkedIn, formulário e perguntas frequentes
style.css           → um único CSS para todas as páginas
img/perfil.svg      → troque pela sua foto
```

## Diferenças em relação à versão de uma página

| Uma página | Várias páginas |
|---|---|
| `href="#sobre"` (âncora) | `href="sobre.html"` (outro arquivo) |
| um único `index.html` | um arquivo `.html` por página |
| um `h1` no site | um `h1` em cada página |
| — | menu marca a página atual com `aria-current="page"` |

O cabeçalho, o rodapé e o `style.css` são **iguais em todas as páginas**:
se mudar o menu, mude em todos os arquivos.

## Como publicar no GitHub Pages

1. Crie um repositório **público** no GitHub.
2. Clique em **Add file → Upload files** e envie todos os `.html`, o `style.css` e a pasta `img`.
3. Vá em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)` e clique em **Save**.
4. Em alguns minutos o site estará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

A página inicial **precisa** se chamar `index.html`.

## Para usar como modelo

- Troque os textos pelos seus dados profissionais e a foto em `img/`.
- **Não publique** CPF, endereço, telefone pessoal ou dados de outras pessoas (LGPD).
