# Como publicar o portfólio no GitHub

Esta versão tem **todos os arquivos soltos, sem pastas**. Assim as imagens e os botões funcionam do mesmo jeito, seja arrastando os arquivos, seja escolhendo pelo botão "choose your files".

## Se o portfólio já foi publicado e está com erro (5 min)

O jeito mais rápido e limpo é recomeçar o repositório:

1. No repositório `portfolio`, abra **Settings**, desça até **Danger Zone** e clique em **Delete this repository**. Digite o nome que o GitHub pedir e confirme.
2. Crie de novo: **+** > **New repository** > nome `portfolio` > **Public** > **Create repository** (desta vez sem marcar o README).
3. Na página do repositório vazio, clique no link **uploading an existing file**.
4. Abra a pasta descompactada do `portfolio-github.zip`, selecione **todos os arquivos** (Ctrl + A) e arraste para a página. Confira se aparecem 18 arquivos, incluindo o `.nojekyll`; se ele não aparecer, veja a dica no fim.
5. Clique em **Commit changes**.
6. **Settings** > **Pages** > Branch **main**, pasta **/ (root)** > **Save**. Em 1 a 3 minutos o site volta no mesmo endereço.

## Primeira publicação (15 min)

1. Crie a conta em **github.com** (Sign up) com o e-mail principal do Pedro; guarde a senha no cofre do plano.
2. **+** > **New repository** > nome `portfolio` > **Public** > **Create repository**.
3. Siga os passos 3 a 6 acima.

## Depois de publicar

- Os botões de contato só aparecem quando têm link. Para ligar: abra `index.html` no GitHub, clique no lápis e troque o `#` de cada botão da seção Contato pelo link do perfil (LinkedIn, 99Freelas, Fiverr, ProZ). **Commit changes**.
- Coloque o link do site nos perfis.

## Para incluir arquivos novos (sempre na raiz, sem pastas, com estes nomes)

| Arquivo | Onde aparece |
|---|---|
| `Case_Capabilidade.png`, `Case_Pareto.png` | página do case DMAIC |
| `Relatorio_Atendimento.pdf`, `Relatorio_Atendimento.pbix`, `pagina1.png`, `pagina2.png` | página do Power BI |
| `Amostra1_PT-EN_Procedimento.pdf`, `Amostra2_EN-ES_Manual.pdf`, `aula_EN.srt`, `aula_ES.srt` | página de tradução (só os feitos pelo Pedro) |

Use **Add file > Upload files**. O botão de cada arquivo aparece sozinho quando ele chega ao repositório.

**Dica:** se o `.nojekyll` não aparecer na lista (alguns computadores escondem arquivos que começam com ponto), crie pelo GitHub: **Add file > Create new file**, nome `.nojekyll`, deixe vazio e clique em **Commit changes**.

> Nunca envie dados reais de empresas ou clientes. Tudo aqui é fictício de propósito.
