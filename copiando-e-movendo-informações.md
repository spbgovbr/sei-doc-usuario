# 9. Copiando e Movendo Informações

## 9.1 Duplicar Processo

A funcionalidade de duplicação pode ser usada quando é necessário utilizar os documentos de um processo como modelos para um novo processo, por meio do ícone ![](/assets/icone_duplicar_processo.png)

![](/assets/detalhe_duplicar_processo.png)

Não se confunde com uma cópia do processo porque, ao serem duplicados, os **documentos perdem as assinaturas**. O sistema gera um novo NUP para o processo duplicado assim como gera nova numeração para os documentos. Todas as assinaturas e ciências são perdidas (para saber mais sobre assinaturas e ciência, consulte: [Assinaturas](https://softwarepublico.gov.br/social/sei/manuais/manual-do-usuario/8.-assinaturas) e [Ciência](https://softwarepublico.gov.br/social/sei/manuais/manual-do-usuario/4.-trabalho-colaborativo)).

O sistema duplica documentos externos, mas não duplica e-mails que fazem parte da árvore de documentos do processo e minutas de outras unidades (as minutas produzidas na unidade que efetua a duplicação são duplicadas).

![](/assets/detalhe_docs_duplicar_processo.png)

Para duplicar um processo, basta selecionar o processo a ser duplicado, clicar no ícone 

![](/assets/icone_duplicar_processo.png)

O sistema abrirá a tela **“Duplicar Processo”**. A tela contém um campo para preenchimento do nome do interessado e um quadro pré-selecionando todos os documentos que poderão ser duplicados. Devem-se selecionar os documentos que serão duplicados ou manter a pré-seleção com as duplicações possíveis. Clicar em duplicar.

![](/assets/processo_duplicado.png)

## 9.2 Mover Documentos Externos

Obs: Funcionalidade ativada apenas para unidades de protocolo.

O SEI disponibiliza um modo de mover documentos externos de um processo para outro. Os documentos gerados no sistema não são movidos, mas podem ser referenciados em outros documentos, de modo que seja inserido um link que permita a visualização do documento, não importa em que processo estiver (para saber mais sobre a inserção de links, consulte:Referenciar Documentos ou Processos).

Para mover um documento externo, deve ser selecionado o ícone ![](/assets/icone_mover_documento.png)

![](/assets/detalhe_mover_documento.png)

O sistema abrirá uma tela em que deverá ser inserido o número do processo de destino. Ao clicar em ![](/assets/icone_pesquisar.png) automaticamente o SEI vai preencher o campo “Tipo” com o respectivo tipo de processo de destino, habilitará o campo “Motivo” e o botão ![](/assets/icone_mover_doc_externo.png)

![](/assets/detalhe_mover_doc_externo.png)

No processo de origem fica registrado o motivo da remoção e o processo de destino do documento:

![](/assets/info_doc_movido.png)


![](/assets/detalhe_doc_movido.png)

Já, o processo de destino, receberá o documento recebido em sua árvore. O registro da transferência fica disponível na consulta ao andamento do processo.

![](/assets/detalhe_historico_doc_movido.png)


## 9.3 Alterar a Ordem dos Documentos

O SEI permite a alteração da ordem dos documentos na árvore de documentos de um processo. Esta funcionalidade serve para corrigir inserções de documentos que, dispostos em sequência cronológica, acabem dificultando o entendimento das informações de um processo. A alteração da ordem dos documentos no processo não pode ser realizada por usuário com perfil básico, devendo ser solicitado a usuário com perfil de Administrador. A operação ficará registrada no histórico do processo.
