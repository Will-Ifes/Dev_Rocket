<p align="center">
  <img src="./.github/readme-cover.svg" alt="NLW eSports: Jogos, comunidades e uma página pessoal." width="100%" />
</p>

# NLW eSports · página pessoal

Página com jogos favoritos, canais de streaming e links sociais, construída na trilha Explorer do evento Next Level Week da Rocketseat.

**HTML · CSS** · [Ver online](https://will-ifes.github.io/Dev_Rocket/)

<p align="center">
  <a href="https://will-ifes.github.io/Dev_Rocket/">
    <img src="./.github/demo.gif" alt="Demonstração da página revisada com jogos, canais e redes sociais. Clique para abrir o site." width="720" />
  </a>
  <br />
  <sub>Clique na demonstração para abrir a página publicada.</sub>
</p>

Projeto de formação da Rocketseat, personalizado durante meu aprendizado de HTML e CSS. Não representa um produto comercial.

## O que mudou na revisão

| Antes | Depois |
| --- | --- |
| Sem `h1` e título da aba "Will nlw" | Nome e bio no topo, título descritivo |
| Ícones de redes sem nome acessível e Facebook vindo de um site de terceiros, sem `alt` | Botões com ícone SVG próprio e nome visível: GitHub, LinkedIn e Instagram |
| Canais de streamers desatualizados | Rocketseat, Ei Nerd e Aqueles Caras |
| Jogos e canais só com imagem | Capa com o nome visível embaixo, lido também pelo leitor de tela |
| `target="_blank"` sem `rel` | `rel="noopener noreferrer"` em todos os links externos |
| Fundo `bg.jpg` de 517 KB | `bg.webp` de 9 KB |
| Sem foco visível e com animação sempre ligada | Foco destacado em verde e animações que respeitam `prefers-reduced-motion` |

**Validação:** axe-core sem violações e sem rolagem horizontal em 375px, 768px e 1366px.

## Explore o diferencial

| Ponto de entrada | O que observar |
| --- | --- |
| [Composição visual](styles.css) | Veja como seções e cartões organizam jogos, canais e redes sociais. |
| [Estrutura da página](index.html) | Listas e links dão forma ao conteúdo de uma página estática. |

## Destaques

- Organização do conteúdo em seções e listas de cartões.
- Imagens e links para jogos e canais de streaming.
- Estilização da página com caixas, espaçamentos e animações.

<details>
<summary><strong>Organização e código</strong></summary>

### Por dentro do código

| Arquivo | Responsabilidade |
| --- | --- |
| [`index.html`](index.html) | Conteúdo, links e estrutura semântica. |
| [`styles.css`](styles.css) | Layout e identidade visual. |

</details>

<details>
<summary><strong>Executar e consultar</strong></summary>

### Executar localmente

Clone o projeto e sirva a pasta com um servidor estático. Com Python 3 instalado:

```bash
git clone https://github.com/Will-Ifes/Dev_Rocket.git
cd Dev_Rocket
python3 -m http.server 8080
```

Abra http://localhost:8080. Não há instalação de dependências ou etapa de build.

</details>

<details>
<summary>Escopo e referências</summary>

A página é estática; imagens de terceiros dependem dos serviços de origem.

</details>

---

Mantido por **Will Oliveira** · [Perfil](https://github.com/Will-Ifes) · [LinkedIn](https://www.linkedin.com/in/wildemberg-de-jesus-oliveira/)
