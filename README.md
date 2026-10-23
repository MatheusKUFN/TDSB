# Tower Defense Sandbox

Protótipo inicial de um jogo 3D em primeira pessoa, executado no navegador.

## Como jogar

- **W, A, S, D** ou setas: movimentação
- **Mouse**: olhar ao redor
- **Espaço**: pular
- **Shift**: correr
- **Esc**: liberar o mouse e pausar

## Executar localmente

Como o jogo usa módulos JavaScript, abra a pasta com um servidor HTTP local. Por exemplo, com Python instalado:

```bash
python -m http.server 8000
```

Depois acesse http://localhost:8000.

Não precisa instalar uma engine: o Three.js é carregado por CDN, então é necessário ter conexão com a internet ao abrir o jogo.

## Arquivos

- `index.html`: jogo completo (cena 3D, controles, HUD e física básica de pulo).
