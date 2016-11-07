#Olá, Mundo: guia de introdução ao GitHub

O projeto **Olá, Mundo** é uma tradição de longa data na programação de computadores. É um exercício simples que o ajuda a dar os primeiros passos no aprendizado de algo novo. Vamos começar com o GitHub!
Você irá aprender como:

* Criar e usar um repository (repositório)
* Iniciar e gerenciar um novo branch (ramificação)
* Fazer alterações em um arquivo e enviá-las para o GitHub como commits (atualizações)
* Abrir e mesclar uma pull request (requisição de envio)

##O que é o GitHub?
O GitHub é uma plataforma de hospedagem de código para controle de versão e colaboração. Ela permite que você e outros usuários trabalhem em conjunto em projetos, de qualquer lugar.

Este tutorial o ensinará recursos essenciais do GitHub como _repositories_ (repositórios), _branches_ (ramificações), _commits_ (atualizações) e _Pull Requests_ (Requisições de Envio). Você criará o seu próprio repositório Olá, Mundo e aprenderá o fluxo de Requisições de Envio do GitHub, que é uma maneira de criar e revisar código.

##Nada de código
Para completar este tutorial, você precisa de uma conta no GitHub e acesso à Internet. Você não precisa saber como programar, usar linha de comando ou instalar o Git (programa de controle de versão sobre o qual o GitHub é construído).

> **Dica:** Abra este guia em uma janela (ou aba) separada do seu navegador, para que você possa acompanhá-lo enquanto completa os passos deste tutorial.

##Passo 1. Crie um Repository (Repositório)
Um _repository_ (repositório) é normalmente usado para organizar um único projeto. Repositórios podem conter pastas e arquivos, imagens, vídeos, planilhas e blocos de dados — qualquer coisa de que seu projeto precisar. Recomendamos incluir um README (LEIAME) ou um arquivo com informações sobre o seu projeto. O GitHub facilita a adição de um arquivo desse tipo cada vez que você criar um novo repositório. _Ele também oferece outras opções, como arquivos de licença._

Seu repositório ``hello-world`` pode ser um espaço onde você armazena ideias, recursos ou até mesmo compartilha e discute com os outros.

###Criar um novo repositório
1. No canto superior direito, perto do seu avatar ou identicon, clique no + e depois selecione **New repository** (Novo repositório).
2. Nomeie o seu repositório ``hello-world``.
3. Escreva uma breve descrição.
4. Selecione **Initialize this repository with a README** (Iniciar este repositório com um LEIAME).
5. Clique em **Create repository** (Criar repositório).

##Passo 2. Crie um Branch (Ramificação)
**Ramificar** é o modo de trabalhar em diferentes versões de um repositório ao mesmo tempo.

Por padrão, seu repositório tem uma ramificação chamada ``master`` (mestre, principal), considerada a ramificação definitiva. Usamos ramificações para fazer testes e edições antes de enviá-las para a ramificação ``master``.

Quando você cria uma ramificação a partir da ramificação ``master``, você está fazendo uma cópia ou registro da ``master``, como ela é neste exato momento. Se outra pessoa fizer alterações na ramificação ``master`` enquanto você está trabalhando na sua própria ramificação, você poderá incorporar essas atualizações.

Este diagrama mostra:
* A ramificação ``master`` (principal)
* Uma nova ramificação chamada ``feature`` (porque estamos fazendo uma alteração do tipo "feature" nessa ramificação
* O caminho que essa ``feature`` toma antes de ser incorporada na ramificação ``master``

Você alguma vez já salvou versões diferentes de um arquivo? Algo como:
* ``historia.txt``
* ``historia-joe-editada.txt``
* ``historia-joe-editada-revisada.txt``

As ramificações têm objetivos similares nos repositórios do GitHub.

Aqui no GitHub, nossos desenvolvedores, escritores e designers usam ramificações para manter as atualizações e correções de erro separadas de nossa ramificação ``master`` (de produção). Quando uma alteração está pronta, eles incorporam suas ramificações à ``master``.

###Criar uma nova ramificação
* Acesse o seu novo repositório ``hello-world``.
* Clique no seletor localizado no topo da lista de arquivos chamada **branch: master**.
* Digite o nome da ramificação, ``readme-edits``, dentro do campo de texto da nova ramificação.
* Selecione o campo azul **Create branch** (Criar ramificação) ou aperte "Enter" no seu teclado.

Agora existem duas ramificações, ``master`` e ``readme-edits``. Elas são exatamente iguais, mas não por muito tempo! Em seguida, adicionaremos nossas alterações na nova ramificação.

##Passo 3. Efetuar e atualizar alterações
Bravo! Agora, você está no modo de visualização de código da sua ramificação ``readme-edits``, a qual é uma cópia da ``master``. Vamos fazer algumas alterações.

No GitHub, as alterações salvas são denominadas _commits_. Cada commit possui uma _mensagem de commit_ associada, a qual é uma descrição que explica porque uma alteração específica foi feita. As mensagens de commit capturam o histórico das mudanças, para que outros contribuidores possam entender o que você fez e porquê.

###Efetuar e atualizar alterações
1. Clique no arquivo ``README.md``.
2. Clique no ícone do lápis no canto superior direito do modo de visualização do arquivo para editá-lo.
3. No editor, escreva um pouco sobre você.
4. Escreva uma mensagem de atualização que descreva suas alterações.
5. Clique no botão **Commit changes**.

Essas alterações serão aplicadas somente ao arquivo README da sua ramificação ``readme-edits``, de modo que agora ela contém um conteúdo que é diferente daquele presente na ``master``.

##Passo 4. Abra uma Pull Request (Requisição de Envio)
Boas alterações! Agora que você tem mudanças em uma ramificação diferente da ``master``, você pode abrir uma _pull request_ (requisição de envio).

Requisições de Envio são a essência da colaboração no GitHub. Quando você abre uma _pull request_, você está propondo suas alterações e requisitando que alguém a revise, considere sua contribuição e a incorpore em sua ramificação. Requisições de envio demonstram _diffs_, ou diferenças, do conteúdo das duas ramificações. As mudanças, adições e subtrações são mostradas em verde e vermelho.

Assim que você fizer um commit você pode abrir uma pull request e dar início a uma discussão, mesmo antes do código ser finalizado.

Ao usar o [sistema de @menção](https://help.github.com/articles/about-writing-and-formatting-on-github/#text-formatting-toolbar) do GitHub na mensagem da sua requisição de envio, você pode solicitar o feedback de uma pessoa específica ou de times, estejam eles a alguns passos de você ou a 10 quarteirões de distância.

Você ainda pode abrir pull requests no seu próprio repositório e incorporá-los você mesmo. Essa é uma ótima maneira de aprender o fluxo do GitHub antes de atuar em projetos maiores.

###Abra uma Pull Request para fazer mudanças no arquivo README
1. Clique na aba **Pull Request** e, na página de Pull Request, clique no botão verde **New pull request**.
2. Selecione a ramificação criada por você, ``readme-edits``, para compará-la com a ``master`` (a original).
3. Confira suas alterações nas diferenças (diffs) mostradas na página Comparação e confirme se elas estão de acordo com o que você deseja enviar.
4. Quando você estiver certo de que essas são as alterações que você quer enviar, clique no grande botão verde **Create Pull Request**.
5. Dê um título à sua pull request e uma breve descrição das suas mudanças.
6. Quando finalizar a sua mensagem, clique em **Create pull request**!

> **Dica:** Você pode usar [emoji](https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji) e [arrastar e soltar imagens e gifs](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/) sobre o campo de comentários e Pull Requests.

##Passo 5. Incorpore sua Pull Request
Nesse passo final, é hora de juntar as suas alterações — incorporando sua ramificação ``readme-edits`` à ramificação ``master``.
1. Clique no botão verde **Merge pull request** para incorporar as mudanças à ``master``.
2. Clique em **Confirm merge**.
3. Vá em frente e apague a ramificação, já que as alterações foram incorporadas, clicando no botão **Delete branch** na caixa roxa.

###Comemore!
Ao completar este tutorial, você terá aprendido a criar um projeto e fazer uma pull request no GitHub! :tada: :octocat: :zap:

Eis o que você conseguiu fazer neste tutorial:

* Criou um repositório de código aberto
* Iniciou e gerenciou uma nova ramificação
* Alterou um arquivo e atualizou as alterações no GitHub
* Abriu e incorporou uma Pull Request

Dê uma olhada no ser perfil do GitHub e você verá seus novos [quadradinhos de contribuição](https://help.github.com/articles/viewing-contributions)!

Se você quer aprender mais sobre o poder das Pull Requests, recomendamos a leitura do [Guia de Fluxo do GitHub](http://guides.github.com/overviews/flow/). Você também pode visitar a página [GitHub Explore](http://github.com/explore) e se envolver em um projeto de Código Aberto :octocat:

> **Dica:** Confira nossos outros [Guias](http://guides.github.com/) e o [Canal no YouTube](http://youtube.com/githubguides) para mais tutoriais do GitHub.

Última atualização em 7 de abril de 2016.

> **Observação:** Este tutorial é uma tradução do guia de introdução [Hello World](https://guides.github.com/activities/hello-world/), de autoria do GitHub.
