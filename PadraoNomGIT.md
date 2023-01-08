
NOMENCLATURA DOS REPOS:

XXX-YYYYY-ZZZZZ

XXX = Sigla que identifica a solução / Nome do Projeto / Plataforma (prefixo de 3 posições).
YYYYYY = Nome do sub-produto do Projeto.
ZZZZZZ = Tecnologia / função no projeto

Exemplo: FLX-SALDO-SERVICE


ESTRUTURA BASICA DE DIRETÓRIOS:

src: A pasta do código-fonte! No entanto, em linguagens que usam cabeçalhos (ou se você tiver uma estrutura para seu aplicativo), não coloque esses arquivos aqui.

test: Testes de unidade, testes de integração... acesse aqui.

config: Deve ser a configuração local relacionada à configuração na máquina local.

build: Esta pasta deve conter todos os scripts relacionados ao processo de construção (PowerShell, Docker compose…).

dep: Este é o diretório onde todas as suas dependências devem ser armazenadas.

doc: A pasta de documentação.

res: Para todos os recursos estáticos em seu projeto. Por exemplo, imagens.

samples: Fornecendo “Hello World” e código Co que suporta a documentação.

ferramentas (tools): Diretório de conveniência para seu uso. Deve conter scripts para automatizar tarefas no projeto, por exemplo, criar scripts, renomear scripts. Geralmente contém arquivos .sh, .cmd, por exemplo.

Arquivos ESPECIAIS DO GIT:

Arquivo README : READMEor README.txtor README.mdetc. é um arquivo que responde o quê, porquê e como do projeto. O GitHub reconhecerá e exibirá automaticamente os READMEvisitantes do repositório. Aqui está uma lista incrível para arquivos leia-me mais profissionais.

LICENSE File : LICENSEor LICENSE.txtor LICENSE.mdetc. é um arquivo que explica o licenciamento legal, como quaisquer direitos, restrições, regulamentos etc.

CHANGELOG File : CHANGELOGor CHANGELOG.txtor CHANGELOG.mdetc. é um arquivo que descreve o que está acontecendo no repositório. Aumentos de número de versão, atualizações de software, correções de bugs... são exemplos do conteúdo do arquivo.

CONTRIBUTORS File : CONTRIBUTORSor CONTRIBUTORS.txtor CONTRIBUTORS.mdetc. é um arquivo que lista as pessoas que contribuíram para o repositório.

AUTHORS File : AUTHORSor AUTHORS.txtor AUTHORS.mdetc. é um arquivo que lista as pessoas que são autores importantes do projeto, como as pessoas legalmente relacionadas com a obra.

SUPPORT File: SUPPORT or SUPPORT.txtor SUPPORT.mdetc. é um arquivo que explica como um leitor pode obter ajuda com o repositório. O GitHub vincula este arquivo na página "Novo problema".

Arquivo de SEGURANÇA: SECURITY descreve as políticas de segurança do seu projeto, incluindo uma lista de versões que estão sendo mantidas com atualizações de segurança. Ele também fornece instruções sobre como seus usuários podem enviar um relatório de vulnerabilidade. Para mais detalhes, consulte o seguinte link .

Arquivo CODE_OF_CONDUCT: CODE_OF_CONDUCT é um arquivo que explica como se envolver em uma comunidade e como resolver quaisquer problemas entre os membros da comunidade do seu projeto. Aqui estão alguns exemplos .

CONTRIBUTING File: CONTRIBUTING é um arquivo que explica como as pessoas devem contribuir e que pode ajudar a verificar se as pessoas estão enviando solicitações pull bem formadas e abrindo problemas úteis. O GitHub vincula esse arquivo na página "Novo problema" e na página "Nova solicitação pull". Isso ajuda as pessoas a entender como contribuir.

AGRADECIMENTOS Arquivo:ACKNOWLEDGMENTS ou ACKNOWLEDGMENTS.txtou ACKNOWLEDGMENTS.mdetc. é um arquivo que descreve trabalhos relacionados, como outros projetos que são dependências, ou bibliotecas, ou módulos, ou possuem seus próprios direitos autorais ou licenças que você deseja incluir em seu projeto.

Arquivo CODEOWNERS: CODEOWNERS é um arquivo que define os indivíduos ou equipes responsáveis ​​pelo código em um repositório. Os proprietários de código são solicitados automaticamente para revisão quando alguém abre uma solicitação pull que modifica o código de sua propriedade. Quando alguém com permissões de administrador ou proprietário habilitou revisões obrigatórias, ele também pode, opcionalmente, exigir a aprovação de um proprietário de código antes que o autor possa mesclar uma solicitação pull no repositório.

Ficheiro FUNDING : funding.ymlé um ficheiro para angariar fundos ou apoiar o seu projecto.

Arquivo ISSUE_TEMPLATE: quando você adiciona um modelo de problema ao seu repositório, os colaboradores do projeto verão automaticamente o conteúdo do modelo no corpo do problema. Os modelos personalizam e padronizam as informações que você deseja incluir quando os contribuidores abrem questões. Para adicionar vários modelos de problema a um repositório, crie um ISSUE_TEMPLATE/diretório na raiz do projeto. Nesse ISSUE_TEMPLATE/diretório, você pode criar quantos modelos de pendências precisar, por exemplo ISSUE_TEMPLATE/bugs.md. Esta lista contém vários modelos para problemas e pull requests.

Arquivo PULL_REQUEST_TEMPLATE: quando você adiciona um PULL_REQUEST_TEMPLATEarquivo ao seu repositório, os colaboradores do projeto verão automaticamente o conteúdo do modelo no corpo da solicitação pull. Os modelos personalizam e padronizam as informações que você gostaria de incluir quando os contribuidores criam pull requests. Você pode criar um PULL_REQUEST_TEMPLATE/subdiretório em qualquer uma das pastas com suporte para conter vários modelos de pull request.