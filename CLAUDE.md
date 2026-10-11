# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

- Projeto de Pedro Mendonça, fundador de um cursinho preparatório para os Institutos Federais criado com o auxílio de IA; esta landing page apresenta e vende o cursinho ao público do IF (estudantes do 9º ano, do ensino médio e de escola pública) na internet.
- A página promove simulados, banco de questões (inclusive geradas com apoio de IA), tutor de IA, mensalidade de R$ 29,90 e uma lista de espera, que é o objetivo principal (conversão).
- Por enquanto é só HTML, em um único `index.html` com CSS e JS embutidos; mantenha assim até Pedro pedir outra estrutura.
- Identidade visual: verde e branco (cores do Instituto Federal) com detalhes em vermelho; cores e fontes ficam nos tokens de `:root`, e o vermelho é só para botões, erros e destaques.
- O formulário envia para `ENDPOINT_LISTA_ESPERA`; vazio, os dados ficam só no `localStorage` do visitante e não chegam ao dono.
- O logo é um SVG provisório (topo e rodapé), pois o logo oficial dos IFs é marca registrada; troque nos dois lugares.
- Mantenha o aviso do rodapé de que o projeto é independente e sem vínculo com os IFs ou o MEC.
- Os preços e a comparação com cursinhos tradicionais são valores de exemplo repetidos em várias seções; ao mudar um, procure os demais.
- Texto sempre em português do Brasil com acentuação completa; respeite `prefers-reduced-motion`. Remoto: github.com/pmendonca-dev/cursinho-if (`main`).
