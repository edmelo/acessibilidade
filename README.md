# Uma Breve História da Programação

Este é um site que fiz durante meus estudos do curso Codecademy para usar e treinar os recursos HTML para acessibilidade de pessoas com deficiencia, principalmente o recurso de leitores de tela dos navegadores.

# Acessibilidade

- Usar **propriedades ARIA**, atributos alt e elementos semânticos em seu HTML é uma maneira simples de tornar seu site acessível para usuários com deficiência visual.

- Usar elementos HTML semânticos sempre que possível (como **<header>** em vez de **<div id="header">**) permitirá que os usuários de leitores de tela naveguem pelo seu site de forma mais eficiente.

- O atributo **role** é usado para comunicar informações sobre o papel de elementos específicos.
**role="presentation"** permite que um leitor de tela ignore elementos de marcação que não contêm informações úteis diretamente.

- aria-label e outras propriedades ARIA podem ser usadas para ajudar os usuários a perceber informações que são comunicadas visualmente, mas não por meio de texto.

- O atributo **alt** deve ser adicionado a cada elemento de imagem (e a todos os outros elementos que o suportam) em vez de **aria-label**. Quando usado, seu valor deve ser uma descrição útil da imagem.

- As alterações que fiz no código não alteram a aparência da página web. No entanto, elas melhoraram muito a experiência para qualquer pessoa que possa acessar a página usando um leitor de tela.

# ARIA

Accessible Rich Internet Applications (ARIA) é um conjunto de funções e atributos que definem maneiras de tornar o conteúdo da Web e os aplicativos da Web (especialmente aqueles desenvolvidos com JavaScript) mais acessíveis para pessoas com deficiências.
https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA