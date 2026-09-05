# Gancho da Virada

Landing page responsiva para o Gancho da Virada, desenvolvida em HTML, CSS e JavaScript em um único arquivo.

## Abrir o projeto

Abra `index.html` no navegador. Não é necessário instalar dependências, executar um build ou iniciar um servidor.

## Arquivos

- `index.html`: página completa, com estilos, scripts e fontes incorporados.
- `ds.html`: design system utilizado como referência.
- `Ajuste Conteúdo - LP.md`: copy e orientações originais da página.

## Personalização

No script ao final de `index.html`:

- Preencha `checkoutUrl` com a URL HTTPS do checkout. Enquanto estiver vazio, os botões levam à seção da oferta.
- Configure `images` para preencher os cinco espaços de imagem: `hero`, `bastidores`, `carol`, `aline` e `depoimentos`.
- Para manter a página independente de arquivos e serviços externos, utilize imagens em data URI. Atualize também os textos alternativos (`alt`).

O vídeo principal, os dados comerciais e os demais campos entre colchetes ainda precisam ser definidos. Os números de autoridade devem ser confirmados antes da publicação.

## Recursos

- Layout para mobile, tablet e desktop.
- FAQ acessível, carrossel por teclado e CTA fixo no mobile.
- Animações de entrada, progresso do mapa e preferência de movimento reduzido.
- Fontes Host Grotesk e JetBrains Mono incorporadas, com licenças incluídas no HTML.
- Sem dependências externas de execução.

## Validação

A versão atual foi conferida em larguras de 320, 375, 768, 1024 e 1440 px, com auditoria automática de acessibilidade em mobile e desktop, testes de teclado e verificação do funcionamento sem JavaScript.
