# 04 · Identidade visual

**Status:** 🟡 em andamento · **Dono:** Luana
**Depende de:** [01 Fundação](./01-fundacao.md)
**Alimenta:** [05 Produto](./05-produto.md), [07 Venda](./07-maquina-de-venda.md)
**Decisões abertas:** 3 → ver rodapé

---

## O símbolo

**Andorinhas.**

Desde que me entendo por gente, minha mãe desenha passarinhos no papel quando está muito pensativa.

> 🖼️ As imagens do símbolo ainda não estão no repositório. Os arquivos esperados são `assets/logo.jpeg` e `assets/logo_2.jpeg`.

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
> 🖼️ Referência pendente de publicação. Arquivo esperado: `assets/revistas_ref.jpeg`.

### Referência de post
> 🖼️ Referência pendente de publicação. Arquivo esperado: `assets/instagam_ideia_1.jpeg`.

### Links
- [Arko Mads](https://arkomov.com/arko-mads/) — referência de criativos e tráfego
- [@camilavidal](https://www.instagram.com/camilavidal/) — referência de storytelling e posicionamento

---

## Índice de arquivos de imagem

Os embeds serão ativados quando os arquivos forem adicionados à pasta `docs/assets/`.

| Arquivo | Onde aparece | O que é | Status |
|---|---|---|---|
| `logo.jpeg` | Este módulo | Símbolo — versão principal | 🔲 Pendente |
| `logo_2.jpeg` | Este módulo | Símbolo — versão alternativa | 🔲 Pendente |
| `revistas_ref.jpeg` | Este módulo | Moodboard de revistas físicas | 🔲 Pendente |
| `instagam_ideia_1.jpeg` | Este módulo | Referência de layout de post | 🔲 Pendente |
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
