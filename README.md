# KPIs e Metas — menu (Associação Volvo-Clube)

Página com o menu de botões 3D que aparece embutida na página **KPIs e Metas** do SharePoint da Associação Volvo-Clube.

🔗 Online: https://leandrormctba-volvo.github.io/kpis-metas-av/

- Os botões abrem as páginas do SharePoint (**Pesquisas de Satisfação** e **Calendário de Atividades**) na mesma aba (`target="_top"`).
- No SharePoint, a página é mostrada por uma web part **Embed** (o domínio `leandrormctba-volvo.github.io` está liberado em *HTML Field Security*).
- Para adicionar um botão novo, copie um bloco `<a class="btn3d" ...>` no `index.html` e troque o link, o ícone e os textos.

No menu principal (raiz) não há dado interno: só o menu e a logo. A página `/clube/` (abaixo) tem os nomes das pastas.

## Página inicial do Clube (`/clube/`)
🔗 https://leandrormctba-volvo.github.io/kpis-metas-av/clube/

Página inicial embutida no SharePoint da Associação Volvo-Clube: foto do Centro de Eventos, abertura animada com **CLUBE** e cartões 3D para cada área do antigo menu lateral. **Documentos** e **Logos** mostram cada pasta como botão; os botões abrem as pastas no SharePoint, na mesma aba (`target="_top"`).

> Atenção: esta página é pública e contém os **nomes das pastas** do SharePoint (decisão do responsável pelo site). Os arquivos continuam protegidos pelo login da Volvo.
> Para atualizar a lista de pastas, peça para ler novamente as pastas de Documentos e Logos no SharePoint e trocar `DOCS` e `LOGOS` no `clube/index.html`.
