# Aula-git

Comandos
git add
Move as alterações do diretório de trabalho para a área de staging. Assim, você tem a oportunidade de preparar um instantâneo antes de realizar o commit ao histórico oficial.

Tutoriais relacionados
Salvar alterações: git add
Aprenda o Git com o Bitbucket Cloud: copie o Repositório do Git e adicione arquivos
Usar ramificações: git merge
Inspecionar repositório: git status
Git Branch
Esse comando é a ferramenta de administração de ramificações de uso geral. Permite criar ambientes de desenvolvimento isolados em um único repositório.

Tutoriais relacionados
Usar ramificações: git branch
Usar ramificações: git checkout
Usar ramificações: git merge
Aprenda o Git com o Bitbucket Cloud: use uma ramificação do Git para fazer o merge de um arquivo
O que faz o Git Checkout
Além de verificar commits antigos e revisões de arquivos antigos, o git checkout também é a forma de navegar pelas ramificações existentes. Combinado com os comandos básicos do Git, é a maneira de trabalhar em determinada linha de desenvolvimento.

Tutoriais relacionados
Usar ramificações: git checkout
Desfazer alterações: git checkout
Comparar fluxos de trabalho: fluxo de trabalho do Gitflow
Git Clean
Remove os arquivos não monitorados do diretório de trabalho. Esse é o correspondente lógico do git reset, que (em geral) só opera em arquivos monitorados.

Tutoriais relacionados
Desfazer alterações: git clean
git clone
Cria cópia de um Repositório do Git existente. A clonagem é o modo mais comum dos desenvolvedores obterem uma cópia de trabalho de um repositório central.

Tutoriais relacionados
Git LFS
Comparar fluxos de trabalho: fluxo de trabalho de bifurcação
Configurar repositório: git clone
Git commit
Faz um commit do instantâneo preparado no histórico do projeto. Combinado com git add, esse processo define o fluxo de trabalho básico para todos os usuários do Git.

Tutoriais relacionados
Usar ramificações: git merge
Reescrever o histórico: git commit --amend
Aprenda o Git com o Bitbucket Cloud: copie o Repositório do Git e adicione arquivos
Salvar alterações: git add
git commit --amend
Informação da marcação -- amend ao git commit permite corrigir o commit mais recente. Isso é muito útil quando você esquece de preparar um arquivo ou para omitir informações importantes da mensagem do commit.

Tutoriais relacionados
Reescrever o histórico: git commit --amend
git config
Uma maneira conveniente de definir opções de configuração para a instalação do Git. Em geral, sua utilização só é necessária de modo imediato após a instalação do Git em máquina de desenvolvimento nova.

Tutoriais relacionados
Configurar repositório: git config3
Git LFS
Instalar o Git: instale o Git no Mac OS X
Instalar o Git: instale o Git no Linux
git fetch
A busca faz o download a partir da ramificação de outro repositório, junto com todos os commits e arquivos associados. Mas, não tenta integrar nada em o repositório local. Assim, você tem a oportunidade de inspecionar as alterações antes de fazer o merge no projeto.

Tutoriais relacionados
Sincronizar: git fetch
Refs e o Reflog: Refspecs
Sincronizar: git pull
git init
Inicializa novo repositório do Git. Se você quiser colocar um projeto sob controle de revisão, este é o primeiro comando que você precisa aprender.

Tutoriais relacionados
Configurar repositório: git init
git log
Permite explorar as revisões anteriores de determinado projeto. Ele oferece várias opções de formatação para exibir o commit de instantâneos.

Tutoriais relacionados
Inspecionar repositório: git log
Registro avançado do Git: filtrar o histórico de commits
Registro avançado do Git: formatação da saída do log
Tutoriais avançados do Git: visão geral
Git merge
Uma maneira poderosa de integrar alterações de ramificações divergentes. Após bifurcar o histórico do projeto com o git branch, o git merge permite unificar o histórico de novo.

Tutoriais relacionados
Merge versus rebase: passo a passo do fluxo de trabalho
Usar ramificações: git merge
Comparar fluxos de trabalho: fluxo de trabalho do Gitflow
Merge versus rebase: visão geral conceitual
git pull
É a versão automatizada do git fetch. Faz o download de ramificação de um repositório remoto e faz a mesclagem imediata na ramificação atual. É o equivalente Git do svn update.

Tutoriais relacionados
Sincronizar: git pull
Comparação de fluxos de trabalho: fluxo de trabalho centralizado
Git LFS
Comparar fluxos de trabalho: fluxo de trabalho de bifurcação
Git push
É o oposto de buscar (com algumas ressalvas). Permite que você mova uma ramificação local para outro repositório, o que é um modo conveniente de publicar as contribuições. É semelhante ao svn commit, mas envia uma série de commits em vez de um único conjunto de alterações.

Tutoriais relacionados
Sincronizar: git push
Refs e o Reflog: Refspecs
Comparar fluxos de trabalho: fluxo de trabalho do Gitflow
Git LFS
git rebase
Permite mover ramificações, o que ajuda a evitar commits de merge desnecessários. A história linear resultante é, em geral, muito mais fácil de entender e explorar.

Tutoriais relacionados
Merge versus rebase: passo a passo do fluxo de trabalho
Reescrever o histórico: git rebase -i
Merge versus rebase: visão geral conceitual
Reescrever o histórico: git rebase
git rebase -i
A marcação -i é usada para iniciar uma sessão de rebase interativa. Ela apresenta todos os benefícios de um rebase normal, porém, dá a oportunidade de adicionar, editar ou excluir commits durante o processo.

Tutoriais relacionados
Reescrever o histórico: git rebase -i
git reflog
O Git mantém o controle das atualizações na ponta das ramificações usando um mecanismo chamado reflog. Ele permite retornar aos conjuntos de alterações mesmo que não estejam referenciados por nenhuma ramificação ou marcação.

Tutoriais relacionados
Reescrever o histórico: git reflog
git remote
Uma ferramenta prática para administrar conexões remotas. Em vez de passar o URL completo para os comandos fetch, pull e push, ele permite usar um atalho mais significativo.

Tutoriais relacionados
Sincronizar: git remote
git reset
Desfaz as alterações nos arquivos no diretório de trabalho. A redefinição permite limpar ou remover por completo as alterações que não foram enviadas a um repositório público.

Tutoriais relacionados
Desfazer alterações: git reset
Reset, Checkout e Revert: operações no nível do commit
Redefinir, fazer checkout e reverter: operações em nível de arquivo
Desfazer alterações: git clean
git revert
Desfaz o commit de um instantâneo. Ao identificar um commit com falha, uma maneira fácil e segura de realizar a sua remoção da base de código é por meio da reversão.

Tutoriais relacionados
Desfazer alterações: git revert
Reset, Checkout e Revert: operações no nível do commit
Reset, Checkout e Revert: resumo
git status
Exibe o estado do diretório de trabalho e o instantâneo preparado. Utilize essa opção em conjunto com os comandos git add e o git commit para ver com precisão o que vai ser incluído no próximo instantâneo.

Tutoriais relacionados
Inspecionar repositório: git status
Git stash
Aprenda o Git com o Bitbucket Cloud: use uma ramificação do Git para fazer o merge de um arquivo
Aprenda o Git com o Bitbucket Cloud: copie o Repositório do Git e adicione arquivos
Terminologia
Ramificação
Uma ramificação representa uma linha de desenvolvimento independente. As ramificações funcionam como uma abstração dos processos de edição/preparação/commit discutidos em Noções básicas de Git, o primeiro módulo desta série. Você pode pensar neles como uma maneira de solicitar um novo diretório de trabalho, área de staging e histórico do projeto. Novos commits são registrados no histórico da ramificação atual, o que resulta em uma bifurcação no histórico do projeto.

Tutoriais relacionados
Aprenda o Git com o Bitbucket Cloud: use uma ramificação do Git para fazer o merge de um arquivo
Comparar fluxos de trabalho: fluxo de trabalho do Gitflow
Usar ramificações: git branch
Comparação de fluxos de trabalho: fluxo de trabalho da ramificação de funções
Fluxo de trabalho centralizado
Se seus desenvolvedores já estão confortáveis com o Subversion, o fluxo de trabalho centralizado permite a você experimentar os benefícios do Git sem precisar se adaptar a um processo todo novo. Também serve como uma transição fácil para fluxos de trabalho mais orientados ao Git.

Tutoriais relacionados
Comparação de fluxos de trabalho: fluxo de trabalho da ramificação de funções
Fluxo de trabalho de ramificação de função
O fluxo de trabalho de ramificação de funções se baseia se no fluxo de trabalho centralizado, encapsulando novas funções em ramificações dedicadas. Essa ação permite a utilização de solicitações pull como forma de discutir as alterações antes que elas sejam integradas ao projeto oficial.

Tutoriais relacionados
Comparar fluxos de trabalho: fluxo de trabalho do Gitflow
Como fazer uma solicitação pull: como funciona
Comparação de fluxos de trabalho: fluxo de trabalho da ramificação de funções
Por que usar o Git na empresa: Git para desenvolvedores
Bifurcação
Em vez de usar um único repositório do lado do servidor para atuar como a base de código "central", a bifurcação proporciona a todos os desenvolvedores um repositório do lado do servidor. Isso significa que cada colaborador não tem um, mas dois repositórios do Git: um local privado e um público do lado do servidor.

Tutoriais relacionados
Comparar fluxos de trabalho: fluxo de trabalho de bifurcação
Como fazer uma solicitação pull: como funciona
Saiba tudo sobre o Gitflow Workflow
O fluxo de trabalho do Gitflow simplifica o ciclo de lançamento usando ramificações isoladas para desenvolvimento de funções, preparação de lançamento e manutenção. Seu modelo de ramificação estrito também fornece uma estrutura indispensável para projetos maiores.

Tutoriais relacionados
Como fazer uma solicitação pull: como funciona
Comparar fluxos de trabalho: fluxo de trabalho do Gitflow
HEAD
A maneira do Git de se referir ao snapshot atual. Na estrutura interna, o comando git checkout apenas atualiza o HEAD para apontar para a ramificação ou commit especificado. Ao apontar para uma ramificação, o Git não reclama, mas quando você confirma um commit, ela muda para o estado "HEAD desvinculado".

Tutoriais relacionados
Refs e o Reflog: Refs especiais
Hooks do Git: hooks locais
Refs e o Reflog: o Reflog
Reset, Checkout e Revert: operações no nível do commit
Hook
Um script automático é executado toda vez que um evento específico ocorre em um repositório do Git. Os hooks permitem personalizar o comportamento interno do Git e acionar ações personalizáveis em pontos-chave do ciclo de vida do desenvolvimento.

Tutoriais relacionados
Hooks do Git: visão geral conceitual
Hooks do Git: hooks locais
Hooks do Git: hooks do lado do servidor
Hooks do Git
Principal
A ramificação de desenvolvimento padrão. Sempre que você cria um repositório do Git, uma ramificação chamada "main" é criada e passa a ser a ramificação ativa.

Tutoriais relacionados
Comparar fluxos de trabalho: fluxo de trabalho do Gitflow
Comparação de fluxos de trabalho: fluxo de trabalho da ramificação de funções
Git stash
Aprenda o Git com o Bitbucket Cloud: use uma ramificação do Git para fazer o merge de um arquivo
Solicitação pull
As solicitações pull são uma função que facilita a colaboração dos desenvolvedores usando o Bitbucket. Elas oferecem uma interface da web fácil de usar para discutir as mudanças propostas antes de fazer a integração ao projeto oficial.

Tutoriais relacionados
Como fazer uma solicitação pull: como funciona
Como fazer uma solicitação pull: exemplo
Comparação de fluxos de trabalho: fluxo de trabalho da ramificação de funções
Saiba mais sobre a revisão de código no Bitbucket Cloud: criar uma solicitação pull
Repositório
Uma coleção de commits, ramificações e marcações para identificar commits.

Tutoriais relacionados
Comparar fluxos de trabalho: fluxo de trabalho de bifurcação
Aprenda o Git com o Bitbucket Cloud: criar um Repositório do Git
Git LFS
Marcação
Uma referência usada em geral para marcar um ponto específico na cadeia de confirmações. Ao contrário de um head, uma marcação não é atualizada pelo comando commit.

Tutoriais relacionados
Converter
Desfazer alterações: git reset
Git stash
Salvar alterações: git add
Controle de versão
Um sistema que registra alterações em um arquivo ou conjunto de arquivos ao longo do tempo para que você possa recuperar versões específicas quando necessário.

Tutoriais relacionados
O que é controle de versão
O que é controle de versão: benefícios do controle de versão
O que é Git
Árvore de trabalho
A árvore dos arquivos que foram confirmados de verdade, em geral contendo o conteúdo da árvore de HEAD commit e quaisquer alterações locais que você fez, mas ainda não confirmou.

Tutoriais relacionados
Git stash
