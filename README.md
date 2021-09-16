# Simple HTML and CSS Calendar Example

Nesta atividade, você modificará uma página HTML que usa atributos de estilo embutido para que, em vez
disso, use um arquivo CSS externo.
Ao concluir esta tarefa, você:
• Ganhe experiência lendo, entendendo e trabalhando com paginas HTML existentes.
• Aplique o que aprendeu sobre classes e estilo CSS
Lembre-se de que existem três maneiras de usar CSS em uma página HTML:
1. usando atributos ”estilo” embutidos em cada tag HTML
2. usando CSS interno no elemento <style> do cabeçalho da página HTML
3. usando CSS externo em um arquivo .css separado que é referido na página HTML usando a tag <link>
Nesta tarefa, o codigo-fonte HTML da página disponibilizada usa a opção 1 para exibir um calendário para
um mês específico, que inclui alguns eventos com código de cores e outros estilos. O objetivo é modificar
a página para que ela não use atributos in-line, mas use a opção 3 para incluir todo o CSS em um arquivo
externo separado.
Baixe o HTML original na pagina da disciplina e salve como ficheiro ”calendar.html” no seu computador. Ao
abri-lo em seu navegador, você verá um calendário para o mês de agosto de 2017, que inclui:
• uma foto de um cachorro no topo
• uma grade mostrando as semanas do mês no formato de domingo a sábado
• dias do calendário codificado com diferentes cores para cada evento
Ao inspecionar o codigo-fonte HTML, verá que todo o conteúdo está em uma tabela (usando a tag <table>),
que é organizada em linhas (usando <tr>) e, em seguida, em colunas (usando <th> e <td>) dentro de cada
linha. Nesta tabela, também estamos usando os elementos <thead> e <tbody>, que são elementos filhos da
<table>. Eles não foram discutidos na lição, mas são usados para simplesmente fornecer mais organização
ao conteúdo da tabela. Por fim, observe que a maioria dos elementos HTML possui um atributo ”class” que
ajuda a agrupar elementos para ”estilizar” e que a maioria também possui um atributo ”style” que especifica a
aparência do elemento usando CSS embutido.
Conforme discutido nas lições , uma das desvantagens do uso de CSS embutido é que ele pode levar a
grandes quantidades de código repetitivo, o que pode ser difícil de manter e alterar. Como você ver neste
exemplo, há muitos lugares em que o estilo foi copiado e colado para criar elementos diferentes e, se algo
mudasse, seria intensivo a alteração e manutenção manualmente.
Nesta atividade, você deve modificar ou ”refatorar” o código HTML existente para que ele use um ficheiro
CSS externo em vez de CSS embutido. Crie um arquivo calendar.css (renomea para fins de classificação!
exemplo calendar_codigoestudante.css ) E use a tag <link> no cabeçalho de calendar.html para vinculá-lo a
essa página. Em seguida, crie regras CSS em calendar.css com base nos atributos de ”estilo” dos elementos
HTML em calendar.html. Agrupe as regras com base nos atributos da ”classe” dos elementos e / ou nos
tipos de elementos HTML, mantendo exatamente as mesmas regras de estilo. Quando terminar de colocar as
regras CSS em calendar.css, exclua os atributos ”style” para todos os elementos HTML em calendar.html. Se
fizer isso corretamente, a página HTML renderizada devera ser exatamente a mesma que a página original!
Nota:
• a atividade é individual e deve ser submetida via piazza.
• ver o deadline da atividade no piazza.
• não altere os atributos de ”classe” de nenhum dos elementos HTML, pois eles serão usados nos testes
durante a avaliação.
• da mesma forma, coloque todo o CSS em um único ficheiro chamado “calendar.css” (todas em minúsculas) e verifique se está no mesmo diretório que calendar.html.
Certifique-se de que:
• não alterou o atributo ”class” de nenhum dos elementos HTML em calendar.html e removeu todos os
atributos ”style”
• não criou nenhum arquivo adicional além de calendar.css e todo o seu código CSS está em calendar.css,
que está no mesmo diretório que o arquivo calendar.html
