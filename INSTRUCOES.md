# Assets visuais para o README do perfil GitHub

Ficheiros:
- `profile-header.svg`: cabeçalho horizontal (1200x300), azul-marinho e ciano.
- `section-divider.svg`: divisor gráfico discreto para separar secções.

## Como adicionar ao repositório

1. Abre o repositório especial `BleyneAlviza/BleyneAlviza`.
2. Clica em **Add file > Upload files**.
3. Extrai este pacote no computador e carrega `profile-header.svg` e `section-divider.svg` para a raiz do repositório.
4. Faz commit com a mensagem: `Adicionar elementos visuais ao perfil`.
5. No início do `README.md`, antes da animação de escrita, coloca:

```markdown
<p align="center">
  <img src="./profile-header.svg" alt="Marcelino Alviza — Software Developer" width="100%" />
</p>
```

6. Entre secções, usa:

```markdown
<p align="center">
  <img src="./section-divider.svg" alt="" width="100%" />
</p>
```

O GitHub apresenta as imagens a partir dos ficheiros guardados no próprio repositório. Não é necessário alojamento externo.

Nota: GitHub não permite CSS personalizado no README. O aspeto visual é criado com imagens, Markdown, badges e HTML permitido pelo GitHub.
