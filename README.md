# Proposta OneFit

Proposta comercial interativa para um sistema de gestão do Studio OneFit.

O projeto transforma a proposta em uma apresentação navegável no navegador. Em vez de ser apenas um documento estático, permite selecionar funcionalidades, visualizar os entregáveis por fase e recalcular automaticamente o investimento e o prazo estimado.

## O que a proposta apresenta

- O problema de administrar a operação usando muitas planilhas separadas.
- A visão de um sistema centralizado para agenda, presença, reposições, treinos, pagamentos e gestão de alunos.
- Funcionalidades organizadas em seis fases de desenvolvimento.
- Entregáveis, estimativas de duração e valores por fase.
- Comparação entre o projeto sem aplicativo e a opção com aplicativo móvel.
- Cálculo dinâmico dos totais conforme as funcionalidades são selecionadas.
- Informações sobre propriedade do código, dados, suporte e próximos passos.

## Como usar

Não há dependências ou processo de compilação.

1. Abra o arquivo `index.html` em um navegador.
2. Use os checkboxes para incluir ou remover funcionalidades da proposta.
3. Clique no número de uma fase para selecionar ou desmarcar todos os itens daquela fase.
4. Use o controle `Incluir App` no canto superior direito para comparar os valores com e sem aplicativo.
5. Use a navegação pelo teclado ou role a página para percorrer os slides.
6. Use o botão de impressão para salvar a proposta como PDF.

## Estrutura

O projeto é intencionalmente simples e autocontido:

```text
index.html    Apresentação, estilos e lógica de cálculo
```

Toda a interface, a apresentação visual e a lógica de preços e prazos estão no próprio arquivo HTML, facilitando o uso offline e o envio da proposta.

## Observações

Os valores, prazos e funcionalidades exibidos são estimativas configuradas para esta proposta. O seletor de aplicativo aplica os acréscimos previstos ao cenário com aplicativo, enquanto a Fase 1 mantém suas regras específicas de cálculo.
