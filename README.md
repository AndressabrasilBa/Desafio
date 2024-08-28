# Desafio-Alura

Codificador e Decodificador de Texto
Este é o primeiro challenge que desenvolvi durante o programa ONE - Oracle Next Education. O objetivo do desafio era colocar em prática os conhecimentos adquiridos em HTML, CSS e JavaScript ao criar um codificador/decodificador de texto. Recebemos orientações através de cards no Trello e um modelo de estilização proposto no Figma.

Meu Projeto
Procuro sempre manter meu código bem organizado para facilitar futuras modificações e garantir que outros possam compreendê-lo facilmente.

Alterações no HTML:
Personalizei o ícone, o título e a descrição da página.
Modifiquei o header, adicionando um link ao logo para que, ao clicar nele, a página seja recarregada. Acho essa funcionalidade interessante para a navegação.
Ajustei o aviso de "apenas letras minúsculas e sem acento" para aparecer somente se o usuário digitar letras maiúsculas ou acentuadas.
Configurei a textarea que exibe o resultado da codificação/decodificação como readonly para evitar que o usuário edite o conteúdo acidentalmente e cause problemas ao tentar codificar/decodificar novamente.
No footer, adicionei meu nome e links para minhas redes sociais.
Modificações no CSS:
Alterei a fonte para "Montserrat light 300", ajustando o tamanho e o espaçamento das linhas.
Modifiquei as cores do fundo, aplicando um gradiente de azul-claro para azul-escuro, e ajustei as sombras.
Implementei animações nos links e botões, utilizando transform e opacity.
Personalizei o ponto de exclamação antes das mensagens de erro (com ::before) e a imagem de fundo da textarea quando não há texto (com
).
Ajustei o layout da página para se adaptar a dispositivos móveis.
Modificações no JavaScript:
Criei a função de codificação, que separa os caracteres do texto em um array (usando texto.value.split), faz a substituição com forEach, e retorna o resultado com .join("").
Desenvolvi a função de decodificação utilizando um array com as chaves de codificação e o método replaceAll(chave[i][1]).
Implementei uma função para validar o texto inserido, garantindo que apenas letras minúsculas e sem acento sejam aceitas.
Adicionei uma função para exibir uma mensagem de erro caso nenhum texto seja inserido.
Criei uma função para que, ao copiar o texto codificado/decodificado, as textareas sejam limpas e o campo de entrada seja focado, facilitando a digitação de um novo texto pelo usuário.
