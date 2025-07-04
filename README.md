﻿<div align="center">
  <img width="550px" src="vscode-theme-preview/GitHub Dark Default.png" />
</div>

# VS Code - Configuração Pessoal Minimalista

Este repositório contém minha configuração personalizada do Visual Studio Code, com foco em simplicidade visual, desempenho e clareza. A proposta segue princípios do ambiente Vim: mínimo, sem distrações e orientado à produtividade.

## Objetivo

Criar um ambiente de desenvolvimento limpo, silencioso e altamente legível, eliminando elementos visuais desnecessários e ruídos que atrapalham o fluxo de trabalho.

## Filosofia

Inspirado na experiência minimalista do Vim, este setup valoriza:

- A ausência de elementos visuais supérfluos
- Máxima atenção ao código
- Interface discreta e responsiva
- Navegação fluida, sem distrações

## Funcionalidades Principais

- **Formatação automática com Prettier**:  
  Arquivos são formatados ao salvar, com largura de linha limitada a 75 caracteres para melhor legibilidade.

- **Interface limpa e silenciosa**:

  - Minimapa, scrollbars, ícones, decorações e destaques visuais desativados
  - Cursor com estilo sólido e largura ajustada
  - Sem popups ou lâmpadas de sugestões (lightbulb)

- **Aparência e temas**:

  - Tema: `GitHub Dark Default`
  - Fonte: `Iosevka Comfy Duo` (Editor) e `Iosevka` (Terminal)
  - Cursor e seleção com cores sutis, sem bordas gritantes

- **Layout minimalista**:

  - Barra lateral à direita
  - Barra de atividades e menu compactos
  - Guias compactas e ocultação de ícones de editor

- **Desempenho e foco**:
  - Realce semântico e pareamento de colchetes desativados
  - Destaques de seleção e palavras semelhantes desabilitados
  - Anotações e margens ocultadas

## Estrutura

- `settings.json`: Arquivo principal com as configurações do editor.
- _(opcional)_ `extensions.json`: Pode ser incluído para listar extensões recomendadas.

## Instalação

1. Substitua o conteúdo do seu `settings.json` pelo arquivo deste repositório:

   - **Windows/Linux**:  
     `%APPDATA%\Code\User\settings.json`

   - **macOS**:  
     `~/Library/Application Support/Code/User/settings.json`

2. Instale a fonte **Iosevka Comfy Duo** para garantir a experiência visual completa.  
   → [Fonte no GitHub](https://github.com/be5invis/Iosevka)

## Considerações

Este setup é ideal para quem busca um ambiente silencioso, visualmente neutro e com comportamento previsível. Ele é adaptável e pode ser ajustado conforme o gosto pessoal de cada desenvolvedor.

## Licença

Este repositório está disponível para uso livre. Sinta-se à vontade para adaptar, copiar ou contribuir com melhorias.
