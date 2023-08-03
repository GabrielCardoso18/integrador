# Integrador

#### Descrição do diretório .git

> Config:
- O "config" do Git refere-se às configurações do sistema, do usuário ou de um repositório específico que controlam o comportamento do Git. Essas configurações são armazenadas em arquivos de texto simples e ajudam a personalizar o ambiente de trabalho do Git de acordo com as preferências e necessidades de cada usuário.
> Head:
- No Git, o termo "HEAD" é uma referência especial que representa o commit atual em que o repositório está posicionado. Podemos dizer que o "HEAD" é uma espécie de ponteiro que aponta para a última confirmação feita no ramo (branch) em que você está trabalhando. 
Quando você cria um novo ramo ou realiza um commit, o "HEAD" é movido para apontar para o novo commit, indicando que este é o commit mais recente na linha do tempo do ramo.

> Description:
- No Git, não há um atributo ou campo chamado "description" (descrição) padrão. O Git é um sistema de controle de versão distribuído e versiona o conteúdo dos arquivos em seu repositório, bem como o histórico de commits, mas não possui uma "descrição" inerente como uma propriedade separada para repositórios ou ramos.
No entanto, você pode adicionar uma descrição personalizada ao seu repositório ou ramo, criando um arquivo chamado "README.md" ou "DESCRIPTION.md" (ou outro nome de sua preferência) e adicionando informações relevantes sobre o projeto, ramo ou diretório em que o arquivo está localizado.

> hooks:
- Em Git, "hooks" (ganchos) são scripts personalizados que você pode adicionar a um repositório para automatizar ou personalizar determinadas ações ou comportamentos antes ou depois de eventos específicos. Cada vez que ocorre um evento Git, como um commit, push, pull ou merge, o Git procura por scripts de "hooks" em pastas específicas dentro do repositório e os executa se estiverem presentes.
Os "hooks" são arquivos executáveis e permitem que você estenda as funcionalidades do Git de acordo com as necessidades do seu projeto. Eles são extremamente úteis para automatizar tarefas, realizar verificações antes de commits serem criados ou executar ações de integração contínua, por exemplo.

> Index: 
- No contexto do Git, o "index" (também conhecido como "staging area" ou "área de preparação") é uma estrutura intermediária essencial que desempenha um papel fundamental no processo de criação de commits.
Quando você faz alterações nos arquivos do seu repositório Git, essas mudanças não são imediatamente refletidas em novos commits. Em vez disso, as alterações são registradas no "index" antes de serem confirmadas como parte de um novo commit. O "index" é como um rascunho das alterações que você deseja incluir no próximo commit.

>logs:
- No Git, você pode visualizar o histórico de commits do repositório usando o comando git log. Os logs do Git mostram informações sobre todos os commits que foram feitos no repositório, permitindo que você veja quando as alterações foram feitas, quem as fez e as mensagens associadas a cada commit.

> Objects:
- Em Git, os "objects" (objetos) são os blocos fundamentais de armazenamento que formam a base do sistema de controle de versão. Eles são responsáveis por representar os dados no repositório Git e armazenar informações como o conteúdo dos arquivos, metadados e histórico de commits.

> refs:
- No contexto do Git, "refs" (referências) são ponteiros ou apontadores para commits específicos, tags ou branches. As "refs" são usadas para rastrear a história do repositório Git e ajudar a localizar commits e outros objetos importantes.
Existem vários tipos de "refs" no Git:
Branches: As "refs" de branches são ponteiros que apontam para commits específicos em um histórico de desenvolvimento. Quando você cria um novo branch, uma nova "ref" de branch é criada apontando para o commit atual. Cada vez que você faz um novo commit no branch, a "ref" é atualizada para apontar para o commit mais recente.
HEAD: O "HEAD" é uma "ref" especial que representa a posição atual do usuário no repositório. Geralmente, é um ponteiro para o branch que você está atualmente usando ou, em alguns casos, pode ser "desanexado" (detached HEAD state), o que significa que você está apontando diretamente para um commit específico, sem estar em um branch.
Tags: As "refs" de tags são ponteiros estáticos que apontam para commits específicos e são usadas para marcar versões importantes ou marcos no histórico do repositório. Ao contrário dos branches, as "refs" de tags não são atualizadas automaticamente quando novos commits são feitos.
Remotes: As "refs" de repositórios remotos apontam para os branches em repositórios remotos. Elas são usadas para rastrear o estado do repositório remoto e permitir que você atualize sua cópia local com as mudanças feitas por outros colaboradores.

O comando add é utilizado para adicionar um stage (git add .)
O comando commit serve para enviar para o repositório(git commit -m 'mensagem .git')
O comando push serve para enviar as alterações do repositório local para o github (git push)
git add . && git commit -m 'Efetua todos os comandos de uma vez .git' && git push
o touch integra.dat criou um arquivo .dat
git rm --cached integra.dat esta deletando o integra