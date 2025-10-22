# Resumo
Esse já é o nosso segundo `LOG.md`, onde iremos nos aprofundar, e bastante, em outras tags e estruturas dentro do nosso HTML, como em **formulários**, **tabelas**, **imagens**, **listas**, entre outras coisas. Vamos começar

# Projeto
O código dessa versão será um pouco diferente dos códigos das outras versões, vamos refatorá-lo e começar a implementar essas novas estruturas.

# As novas estruturas
Com base no que foi dito anteriormente, vamos nos aprofundar em algumas estruturas do nosso HTML, sendo elas:

## Listas
Lista é uma forma de organizar um conjunto de itens, sejam textos, hiperlinks, ícones, etc. Esse recurso é muito usado para construir menus de navegação, blocos de textos que sejam tópicos ou quaisquer outras informações agrupadas.

Há três tipos de listas: **desordenadas**, **ordenadas** e de **definição**.

As **listas desordenadas** são iniciadas com a tag `<ul>` e cada item dessa lista é marcado com um bullet `<li>`.

As **listas ordenadas** são iniciadas com a tag `<ol>` e cada item é marcado com números `<li>`, por padrão. Para marcar os itens com letras, utilize a tag `<ol type="a">` e para marcar com números romanos, `<ol type="I">`.

As **listas de definição** são iniciadas com a tag `<dl>`, seguida de `<dt>` e `<dd>`.

<a href="/3.HTML-Avancando/pages/listas.html">Conteúdo</a>


## Formatação de texto e títulos
Além do uso da tag `<p>` para criação de textos, conheça algumas tags para criação de títulos. Atente-se que existe uma hierarquia, sendo o `<H1>` o mais importante e o `<H6>` o menos importante.

Há também algumas tags utilizadas para criar efeitos na formatação do texto.
<a href="/3.HTML-Avancando/pages/textos.html">Conteúdo</a>

## Etiquetas para links
Etiquetas para links, também chamadas de âncoras, são criadas para que o usuário, ao realizar uma ação, seja direcionado para uma página interna ou externa específica. Usar # entre aspas duplas no href (href="#")  significa que não irá direcionar para nenhum local.

É possível inserir etiquetas em qualquer elemento da página, como textos, títulos, imagens e botões. Para isso, basta utilizar a tag `<a>`, que possui um atributo de href no qual será inserido o valor referente ao endereço para onde o usuário será direcionado ao clicar.

### Atributo Target
Conheça o atributo target que pode ser inserido na tag `<a>` e que ***define em qual página será aberta a referência chamada***.Observe as variações do atributo target:

- **target="_self"**: abre na mesma página (é o padrão, se a target não for definida);
- **target="_blank"**: abre uma nova página;
- **target="_parent"**: abre em seu elemento pai, ou seja, no próximo nível acima; caso não haja um próximo nível, adota o padrão (self);
- **target="_top"**: abre na janela toda.

## Tabela
Tabela é uma forma de apresentar um conjunto de dados, de modo agrupado em *linhas* e *colunas*. A tabela é iniciada pela tag `<table>`, seguida da tag `<tr>`, que representa as **linhas**, e é **formada pelas células**, representadas pela tag `<td>`.

Assim como outras tags do body, podemos **estilizar a tabela por meio dos atributos**. Essa estilização pode ser *interna* (dentro da tag ou aninhada na tag head) ou *externa* (utilizando CSS).

## Formulários
Um formulário permite a interação entre o usuário e o sistema; dessa forma, é possível fazer a coleta de dados do público e enviá-los a um servidor para serem processados e salvos em um banco de dados, por exemplo. Um formulário deve conter um **campo de texto** (input), **checkbox** (caixa de seleção), **RadioButton** ou **botão**.

Para isso, no layout, é necessário conter os campos com as informações que o desenvolvedor deseja obter, atentando-se para deixar o formulário objetivo, para que o usuário não gaste muito tempo e/ou desista do preenchimento.

Na imagem, temos um exemplo de um formulário para realizar um cadastro, em que se solicita o preenchimento dos campos de **nome completo**, **e-mail**, **empresa**, **telefone**, **UF**, **cidade**, **assunto**, **categoria de usuário** e **mensagem**. Esses dados são salvos em um banco de dados e, por meio da lógica de uma linguagem de programação, são resgatados e confirmados se existem, para liberar o acesso.

O *formulário* pode ser utilizado para que o usuário **entre em contato com a empresa**, em uma **enquete**, em um **cadastro de login**, na **recuperação de uma senha**, na **alteração de dados**, entre outros.

Você pode iniciar com uma estrutura mais simplificada, apenas abrindo a tag `<form>`. **A tag `<label>` é utilizada para representar uma legenda**. O `for` é um atributo da tag cujo objetivo é permitir que, quando o *usuário clique na palavra nome*, *selecione o input* (caixa de texto), pois o ==valor do id é igual== ao valor do `for`. **Caso o id seja diferente do valor do `for` ou vice-versa, quando o usuário clicar no nome, não selecionará o input**. ==O input é o campo de entrada do usuário.==