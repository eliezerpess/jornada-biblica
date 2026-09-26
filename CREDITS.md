# Créditos — Jornada Bíblica

Todos os modelos 3D usados no jogo são **CC0 1.0 (domínio público)** — podem ser usados
livremente, inclusive comercialmente, sem necessidade de atribuição. Mesmo assim, fica
registrado aqui o agradecimento aos autores. Os arquivos GLB foram otimizados e embutidos
(base64) dentro do `index.html`, para que o jogo funcione offline, a partir de um único arquivo.

| O quê | Autor / pacote | Licença | Link |
|---|---|---|---|
| Personagens (base animada "Character Animated", RPG Characters) — recoloridos por personagem | Quaternius | CC0 1.0 | https://quaternius.com/packs/rpgcharacters.html · https://poly.pizza/m/DgOCW9ZCRJ |
| Ovelha animada | Quaternius (via Poly Pizza) | CC0 1.0 | https://poly.pizza/m/C39AUXUUes |
| Animais animados (alpaca→camelo, jumento, cavalo, vaca, touro, cervos, raposa, lobo, cão) | Quaternius — Ultimate Animated Animals | CC0 1.0 | https://quaternius.com/packs/ultimateanimatedanimals.html |
| Serpente | Quaternius — Easy Enemy Pack | CC0 1.0 | https://quaternius.com/packs/easyenemy.html |
| Árvores, palmeiras, arbustos, pedras, flores, grama, trigo, troncos | Quaternius — Ultimate Nature Pack | CC0 1.0 | https://quaternius.com/packs/ultimatenature.html |
| Motor 3D | three.js r149 | MIT | https://threejs.org |
| Música, ambiente, efeitos sonoros | Sintetizados em tempo real no jogo (WebAudio) | — | — |
| Voz do Narrador (opcional) | Voz pt-BR do próprio navegador (Web Speech API) | — | — |

Observações
- Os GLBs da Quaternius foram obtidos a partir das páginas oficiais dos pacotes e do repositório
  público `trebeljahr/quaternius-showcase` (o MIT desse repositório cobre só o código dele; os
  modelos continuam CC0, conforme quaternius.com — conferido em 26/09/2026).
- As árvores/plantas do Ultimate Nature Pack foram simplificadas (cerca de 1/3 dos triângulos) com
  meshoptimizer (MIT) via glTF-Transform (MIT) — ferramentas usadas só na preparação (`tools-simplify.mjs`),
  não vão dentro do jogo.
- Não foram usados modelos CC-BY (por exemplo, "Animated Wizard"/"Base Character" do Poly Pizza).
- Cenários, construções (arca, zigurates, pirâmides, casas, tendas, poços) e efeitos foram
  modelados por código dentro do próprio jogo.
