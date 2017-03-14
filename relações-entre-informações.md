# **5. Relações entre Informações**

## **5.1 Sobrestar Processo**

Esta funcionalidade deve ser utilizada apenas quando houver determinação formal para interrupção do trâmite do processo, seja dentro do próprio processo ou a partir de outro processo. O sobrestamento faz com que a contagem do tempo do processo fique suspensa, até que seja retirado o sobrestamento.

Para sobrestar é necessário clicar no número do processo e selecionar o ícone: 

![](/assets/image0180.png)

> a. Quando a determinação de interrupção do trâmite do processo constar formalmente no próprio processo, selecione a opção **"Somente Sobrestar"**, preencha o campo**"Motivo"** e salvar:
> 
> ![](/assets/image0181.png)

> b. Quando a determinação de interrupção do trâmite do processo constar formalmente em outro processo também existente no SEI, selecione a opção**“Sobrestar vinculando a outro processo”**. O sistema abre o campo**“Processo para Vinculação”**, no qual deve ser informado o número do processo que tenha determinado seu sobrestamento. Ao clicar em![](/assets/image0182.png), automaticamente preencherá o campo **“Tipo”** com o respectivo tipo de processo a ser vinculado. O campo **“Motivo”** deve ser preenchido e depois salvar:
> 
> ![](/assets/image0183.png)

Ao selecionar a opção **"Processos Sobrestados"** no menu principal, o sistema relaciona os processos da unidade que se encontram sobrestados e as informações relativas ao sobrestamento: usuário que efetivou o sobrestamento; data; motivo; e o número do processo na coluna**“Vinculação”**, caso o processo tenha sido sobrestado vinculado a outro processo:

> ![](/assets/image0184.png)

Para remover o sobrestamento, basta o usuário selecionar o processo e clicar no botão ![](/assets/image0185.png) ou selecionar o ícone![](/assets/image0186.gif) **"Remover Sobrestamento"** no quadro que contém a relação de processos sobrestados.

![](/assets/barra_dicas_correta.png)

1. Somente é possível sobrestar um processo que esteja aberto apenas na unidade que efetuará a operação.
2. Não há regra para o tempo limite em que um processo deva permanecer sobrestado.
3. Processos sobrestados saem da tela de **"Controle de Processos"**. Para que sejam visualizados, deve ser acessado o menu **"Processos Sobrestados"**.

![](/assets/barra_fechamento.png)

## **5.2 Relacionar Processos**

A funcionalidade![](/assets/image0187.png) é utilizada para agrupar processos que possuam alguma ligação entre si \(por exemplo, informações complementares\), porém, autônomos.

Caso existam processos relacionados, com o processo aberto, logo abaixo da árvore de documentos aparecem os tipos de processos que possuem relacionamentos, visíveis para todas as unidades:

![](/assets/image0188.png)

Ao clicar no tipo de processo, o sistema mostrará os números de processos relacionados com aquele tipo. Ao clicar em um dos números, o sistema abrirá o processo correspondente e o processo anterior passa a figurar como relacionado ao processo ora aberto. Ou seja, o relacionamento é nos dois sentidos.

![](/assets/image0189.png)

Para relacionar processos é necessário estar com um dos processos aberto e, antes, saber o número dos processos a serem relacionados. Na barra de menu do processo, deve-se selecionar o ícone ![](/assets/image0187.png):

![](/assets/image0190.png)

Em seguida é aberta tela para informar o número do **“Processo Destino”** e, ao clicar em ![](/assets/image0182.png), o sistema confirma a existência do processo no SEI e automaticamente preenche o campo **“Tipo”**, habilitando o botão ![](/assets/image0192.png).

![](/assets/image0193.png)

Ao clicar no botão, o sistema mostra um quadro com a lista de processos relacionados:

![](/assets/image0194.png)

Para cancelar o relacionamento, basta selecionar o ícone ![](/assets/image0195.png)na coluna **“Ações”** do referido quadro.

![](/assets/barra_dicas_correta.png)

1. Não há hierarquia entre processos relacionados. Ao contrário da anexação, um processo não passa a fazer parte do outro e o vínculo pode ser desfeito a qualquer tempo.
2. É possível relacionar vários processos em sequência, inserindo número após número.

![](/assets/barra_fechamento.png)

## **5.3 Anexar Processos**

A anexação de processos é uma funcionalidade que permite juntar de maneira permanente processos do mesmo tipo, com o mesmo interessado e com o mesmo objetivo, uma vez verificado que as informações deveriam ou podem estar agregadas em um processo único.

![](/assets/image0196.png)

Como regra, o processo mais novo é anexado ao processo mais antigo, de modo que o mais novo passa a compor a árvore de documentos do mais antigo. No processo anexado será indicado o processo principal:

![](/assets/image0197.png)

Para anexar um processo, é necessário saber o número a ser anexado. Deve-se selecionar o processo que receberá o anexado e, ao abrir a tela do processo, selecionar o ícone ![](/assets/image0200.png):

![](/assets/image0199.png)

Na tela seguinte deverá ser preenchido o campo **“Processo”** com o número que será anexado \(processo mais recente\) e clicar em ![](/assets/image0191.png). Automaticamente o SEI preenche o campo **“Tipo”** com o respectivo tipo de processo a ser anexado e habilitar o botão ![](/assets/image0200.png). Ao clicar nesta opção, o SEI informará que somente o Administrador do Sistema pode cancelar a operação:

![](/assets/image0201.png)

Após em ![](/assets/image0202.png)a anexação é efetivada. O SEI mostrará a tela **“Anexação de Processos”**com um quadro listando os processos anexados. O processo anexado aparecerá na árvore de documentos do processo principal:

![](/assets/image0203.png)

![](/assets/barra_dicas_correta.png)

1. A anexação deverá ser utilizada quando houver necessidade de unificação permanente de processos do mesmo tipo, com o mesmo interessado e com o mesmo objetivo e, portanto, deverão ser tratados de forma conjunta. Uma vez anexado a um processo principal, o processo acessório deixa de ter independência, não sendo mais possível nenhuma ação isolada, tal como inclusão de novos documentos.
2. Para que a anexação possa ser realizada, o processo a ser anexado deve estar aberto somente na unidade que efetuará a operação.
3. Ao ser realizada a operação de anexação, os relacionamentos do processo anexado são mantidos. Basta clicar no ícone do processo anexado\(na árvore de documentos do processo principal\) e selecionar a opção**“Clique aqui para visualizar este processo em uma nova janela”**. Os relacionamentos serão mostrados abaixo da árvore de documentos do processo anexado.
4. A operação de anexação não pode envolver processos sigilosos.
5. Caso o processo a ser anexado tenha nível de acesso **"Restrito"**, o processo principal será "contaminado" por esse nível \(mesmo comportamento quando um documento restrito é anexado a um processo com nível de acesso **"Público"**\).
6. O processo a ser anexado não pode ter processos anexos a ele.
7. Quando um processo anexado se encontra em bloco de reunião disponibilizado para outras unidades, deixa de ser possível a visualização de minutas do processo. No entanto, a informação sobre a anexação fica visível na tela do processo \(para saber mais sobre blocos de reunião, consulte:[Bloco de Reunião](https://softwarepublico.gov.br/social/sei/manuais/manual-do-usuario/8.-assinaturas/#02)\).

![](/assets/barra_fechamento.png)
