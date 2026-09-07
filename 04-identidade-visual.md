# 04 · Identidade visual

**Status:** 🟡 em andamento · **Dono:** Luana
**Depende de:** [01 Fundação](./01-fundacao.md)
**Alimenta:** [05 Produto](./05-produto.md), [07 Venda](./07-maquina-de-venda.md)
**Decisões abertas:** 3 → ver rodapé

---

## O símbolo

**Andorinhas.**

Desde que me entendo por gente, minha mãe desenha passarinhos no papel quando está muito pensativa.

![Logo Rosaninha — versão principal](./assets/logo.jpeg)
*`./assets/logo.jpeg` — versão principal do símbolo*

![Logo Rosaninha — versão alternativa](./assets/logo_2.jpeg)
*`./assets/logo_2.jpeg` — versão alternativa*

---

## Paleta: Céu das Andorinhas

Azul claro como cor dominante, verde floresta herdado da Raiz Viva, dourado mostarda como acento sutil, e off-white de papel de jornal como base.

| Cor | Código | Uso |
|-----|--------|-----|
| Azul claro (médio) | `#8CA0BE` | DOMINANTE |
| Azul claro (pastel) | `#C8D8E5` | DOMINANTE — respiro |
| Verde floresta | `#3F5A3E` | HERANÇA RAIZ VIVA |
| Dourado mostarda | `#B08A3E` | ACENTO SUTIL |
| Off-white jornal | `#EDEDDE` | BASE |
| Tinta | `#22303D` | TEXTO |

> ⚠️ O hex da Tinta veio como `#2231D` no material original — cinco dígitos, hex inválido. `#22303D` é a leitura do azul-escuro da prancha. Conferir no arquivo de origem antes de aplicar.

---

## Tipografia

> 🔲 **Pendente** — definir as fontes finais. Aguardando as fotos das revistas de referência.

Direção já definida:

| Papel | Estilo | Exemplo de aplicação |
|---|---|---|
| **Título** | Serifada editorial | "Casa com apreço" |
| **Corpo** | Sans legível | "O passo a passo pra você organizar sua rotina sem peso, capítulo por capítulo." |
| **Destaque** | Serifada itálica | *"Onde o pé passa, é ali que se cuida primeiro."* |

---

## Referências visuais

### Revistas físicas de banca
![Referência de revistas físicas](./assets/revistas_ref.jpeg)
*`./assets/revistas_ref.jpeg` — direção editorial, diagramação e respiro de página*

### Referência de post
![Referência de post para Instagram](./assets/instagam_ideia_1.jpeg)
*`./assets/instagam_ideia_1.jpeg` — layout e composição de post*

### Links
- [Arko Mads](https://arkomov.com/arko-mads/) — referência de criativos e tráfego
- [@camilavidal](https://www.instagram.com/camilavidal/) — referência de storytelling e posicionamento

---

## Índice de arquivos de imagem

Caminhos relativos à pasta `./assets/`. Para os embeds funcionarem, os arquivos precisam estar lá.

| Arquivo | Onde aparece | O que é | Status |
|---|---|---|---|
| `logo.jpeg` | Este módulo | Símbolo — versão principal | ✅ |
| `logo_2.jpeg` | Este módulo | Símbolo — versão alternativa | ✅ |
| `revistas_ref.jpeg` | Este módulo | Moodboard de revistas físicas | ✅ |
| `instagam_ideia_1.jpeg` | Este módulo | Referência de layout de post | ✅ |
| `paleta_final.png` | Este módulo | Prancha da paleta aplicada | 🔲 A exportar |
| `mockup_capa.png` | [08 Lançamento](./08-lancamento.md), Bloco 2 | Mockup 3D do ebook | 🔲 A produzir |

> ⚠️ O nome `instagam_ideia_1.jpeg` está sem o "r" (instag**r**am). Se renomear, atualizar as referências acima.

> ℹ️ **Portabilidade**: embeds relativos funcionam no GitHub, Obsidian e VS Code, mas quebram se o `.md` sair da pasta sem as imagens. Quando a AWS estiver de pé ([06 Infra](./06-infraestrutura.md)), vale subir pro S3 e trocar por URLs.

---

## Decisões abertas

| Decisão | Contexto |
|---|---|
| Tipografia definitiva | Bloqueada pelas fotos das revistas de referência |
| Moodboard com as revistas físicas | Montar a partir de `revistas_ref.jpeg` |
| Template de capa e de posts | Depende da tipografia |
