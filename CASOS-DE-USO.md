# Requisito funcional
> * Requisito A.1: O sistema irá permitir que o usuário possa fazer um cronograma para controle de atividade a serem feitas, desde que tenham atividades que o mesmo irá colocar no sistema para ser a base desse cronograma

# Descrição do caso de uso
|UC-001|Cronograma de atividades|
|-|-|
|Requisitos Relacionados| Requisito A.1 |
|Descrição Detalhada| O usuário terá a opção de criar um cronograma para controlar e monitorar as atividades a serem feitas e definir prazos para elas, afim de ter maior organização e entendimento do seu time para com o projeto.|
|Pré-Condições| - O usuário deve possuir um plano ativo no BuildApp; Deve registrar as tarefas a serem realizadas.|
|Pós-Condição de Sucesso | O usuário terá um cronograma totalmente organizado|
|Pós-Condição de Falha| Rejeita a data inserida.|
|Atores Principais| Gerente de Projeto|
|Atores Secundários| Nenhum.|
|Gatilho| Selecionar a opção criar cronograma.|
|Casos Incluídos| Nenhum.|

##  Fluxo Principal 

**UC-001: Cronograma de atividades.**
| Passo | Ação |
|-|-|
| 1 | O usuário faz a autenticação no software através da tela de acesso.|
| 2 | Escolhe a função criar novo cronograma.|
| 3 | Seleciona o tipo de cronograma desejado.|
| 4 | Insere as tarefas a serem realizadas.|
| 5 | Designa datas para a realização.| 
| 6 | O usuário finaliza o cronograma ao clicar em "finalizar"|

## Fluxo Alternativo

**UC-001: Cronograma de atividades.**
| Passo | Ação |
|-|-|
| 1.1 | O usuário esquece a senha.|
| 1.2 | O mesmo a redefine utilizando a função "Esqueci a senha".|
| 4.1| A quantidade mínima de tarefas não é atingida.|
| 4.2 | O usuário adiciona mais tarefas para que satisfaça o mínimo.|
| 5.1 | O usuário designa datas passadas| 
| 5.2 | Uma mensagem de texto é gerada pedindo a mudança para uma data posterior a atual.|
| 5.3 | O usuário designa datas novas com período à frente da data atual.| 

# Requisito funcional
> * Requisito A.2: O usuário deverá poder separar os arquivos em áreas específicas dentro do software para melhor organização, desde que estas áreas tenham sido criadas e tenha arquivos para separar por tarefa.

# Descrição do caso de uso
|UC-002|Separar Arquivos|
|-|-|
|Requisitos Relacionados| Requisito A.2 |
|Descrição Detalhada| O usuário terá suporte da IA para ter separação de arquivos em sua devida pasta em cada categoria para facilitar o trabalho e ter uma maior organização em cima do projeto.|
|Pré-Condições| O usuário deve ter a versão premium do BuildApp; Ter os Arquivos.|
|Pós-Condição de Sucesso | Terá os Arquivos em cada área correspondida.|
|Pós-Condição de Falha| A IA irá cancelar o processo e irá solicitar que o usuário selecione os arquivos novamente.|
|Atores Principais| Usuário do Aplicativo.|
|Atores Secundários| Nenhum.|
|Gatilho| O usuário usar o sistema para selecionar os arquivos. |
|Casos Incluídos| Nenhum.|

##  Fluxo Principal
**UC-002: Separar Arquivos**

| Passo | Ação |
|-|-|
| 1 | O usuário se autentica no site/app.|
| 2 | O usuário seleciona os arquivos para a separação.|
| 3 | a IA moverá cada arquivo para sua pasta correspondida.|
| 4 | O usuário entrará em cada pasta para realizar as tarefas.|
| 5 | O usuário terminará todas as atividades do dia.| 

## Fluxo Alternativo

**UC-002: Separar Arquivos.**
| Passo | Ação |
|-|-|
| 1.1 | O usuário não pagou a mensalidade.|
| 1.2 | Efetuar pagamento para ativar o plano novamente e poder autenticar.|
| 2.1 | IA não reconheceu todos os arquivos.|
| 2.2 | Os arquivos que não foram selecionados ou identificados pela IA não serão mudados e uma mensagem de aviso será mostrada.|
| 3.1 | A quantidade mínima de tarefas não é atingida.|
| 3.2 | O usuário adiciona mais tarefas para que satisfaça o mínimo.|
| 5.1 | O usuário faz apenas uma pasta.|
| 5.2 | A IA irá alertar que existe apenas uma pasta e não tem outro local para mover.|

# Requisito funcional
> * Requisito A.3: Permitir que os usuários adicionem comentários e notas às fotos enviadas para o sistema, melhorando a documentação das tarefas e a comunicação entre os membros da equipe.

# Descrição do caso de uso
|UC-003|Adicionar Comentários e Notas|
|-|-|
|Requisitos Relacionados| Requisito A.3 |
|Descrição Detalhada| Este caso de uso permite aos usuários inserir comentários e notas em fotos enviadas para o sistema, fornecendo informações adicionais sobre as tarefas. Isso melhora a documentação das atividades e a comunicação entre os membros da equipe.|
|Pré-Condições| Sistema online; Foto da tarefa disponível.|
|Pós-Condição de Sucesso| Foto com comentários/notas adicionadas é enviada com sucesso e armazenada no sistema.|
|Pós-Condição de Falha| Comentários/notas não são adicionados à foto. O usuário é notificado sobre a falha e a foto original permanece sem modificações.|
|Atores Principais| Usuário, gerente de projetos e supervisores.|
|Atores Secundários| Nenhum.|
|Gatilho| O usuário seleciona a opção de adicionar comentários e notas a uma foto da tarefa no sistema. |
|Casos Incluídos| Nenhum.|

##  Fluxo Principal
**UC-003: Adicionar Comentários e Notas**

| Passo | Ação |
|-|-|
| 1 | O usuário acessa o sistema online e seleciona a tarefa relevante.|
| 2 | O usuário escolhe a foto da tarefa para adicionar comentários/notas.|
| 3 | O sistema apresenta uma interface para inserção de comentários/notas.|
| 4 | O usuário insere o texto do comentário/nota e confirma a operação.|
| 5 | O sistema valida as entradas e adiciona os comentários/notas à foto.|
| 6 | O sistema armazena a foto com os comentários/notas e notifica o usuário sobre o sucesso da operação.|

## Fluxo Alternativo

**UC-003: Adicionar Comentários e Notas.**
| Passo | Ação |
|-|-|
| 1.1 | O sistema está offline ou inacessível.|
| 1.2 | O usuário recebe uma mensagem de erro indicando a indisponibilidade do sistema. O usuário tenta novamente acessar o sistema mais tarde ou contata o suporte técnico.|
| 2.1 | A foto da tarefa não está disponível.|
| 2.2 | O sistema notifica o usuário sobre a ausência da foto. O usuário seleciona outra foto ou tenta novamente mais tarde.|
| 3.1 | A interface de inserção de comentários/notas não carrega corretamente.|
| 3.2 | O sistema notifica o usuário sobre o problema na interface. O usuário recarrega a página ou contata o suporte técnico.|
| 4.1 | O texto do comentário/nota está vazio ou inválido.|
| 4.2 | O sistema solicita ao usuário que insira informações válidas. O usuário corrige o texto do comentário/nota e tenta novamente.|
| 5.1 | Ocorre um erro ao adicionar os comentários/notas à foto.|
| 5.2 | O sistema notifica o usuário sobre a falha na operação. O usuário tenta novamente ou contata o suporte técnico.|
| 6.1 | Ocorre um erro ao armazenar a foto com os comentários/notas.|
| 6.2 | O sistema notifica o usuário sobre a falha no armazenamento. A foto original permanece sem modificações e o usuário tenta novamente ou contata o suporte técnico.|


# Requisito funcional
> * Requisito A.4: O sistema permitirá que o usuário selecione o plano de assinatura que melhor se adapte às suas necessidades. Após a assinatura, o usuário terá acesso a todas as funcionalidades disponíveis no plano escolhido dentro do aplicativo BuildApp.

# Descrição do caso de uso
|UC-004|Verificar Planos|
|-|-|
|Requisitos Relacionados| Requisito A.4 |
|Descrição Detalhada| O usuário ou cliente atuentica o login no software, caso não possua plano ativo deve contratar um para utilizar as funçõesdo software. Quem contratar os serviços do software BuildApp terá três opções de assinatura e poderá escolher a que melhor se adapta às suas necessidades, definindo as funções que irá utilizar.|
|Pré-Condições| Entrar no site/app da BuildPro.|
|Pós-Condição de Sucesso| O usuário estará apto para utilizar os recursos do BuildApp.|
|Pós-Condição de Falha| O usuário terá o seu acesso negado na plataforma do BuildApp.|
|Atores Principais| Clientes|
|Atores Secundários| Nenhum.|
|Gatilho| Necessidade de um software de Gestão de Tarefas.|
|Casos Incluídos| Nenhum.|

##  Fluxo Principal
**UC-004: Verificar Planos**

| Passo | Ação |
|-|-|
| 1 | O cliente acessa a plataforma.|
| 2 | Escolhe o plano que melhor o atende.|
| 3 | Faz o pagamento do plano que escolheu.|
| 4 | Assiste o tutorial de como utilizar a plataforma.|
| 5 | O Sistema está pronto para uso e com os acessos definidos pelo plano escolhido.|

## Fluxo Alternativo

**UC-004: Verificar planos.**
| Passo | Ação |
|-|-|
| 3.1 | Problemas no Pagamento.|
| 3.2 | Cliente recebe uma notificação sobre a falha no pagamento.|
| 3.3 | Efetua o pagamento novamente.|
| 4.1 | Necessidade de Treinamento Adicional|
| 4.2 | Cliente contata o suporte para receber treinamento especial.| 


# Requisito funcional
> * Requisito A.5: O sistema deve permitir que o usuário faça o diário de obra e selecione imagens para realizar o mesmo, possui a função automática onde a IA irá fazer o diário de obra apenas utilizando as informações da imagem enviada.

# Descrição do caso de uso
|UC-005|Realizar Diário de Obra|
|-|-|
|Requisitos Relacionados| Requisito A.5 |
|Descrição Detalhada| O sistema deve permitir que o usuário faça o diário de obra e selecione imagens para realizar o mesmo, possui a função automática onde a IA irá fazer o diário de obra apenas utilizando as informações da imagem enviada.|
|Pré-Condições| O colaborador deve estar autenticado no sistema - Deve possuir  as fotos da atividade.|
|Pós-Condição de Sucesso| A imagem é devidamente carregada e registrada no diário de obra.|
|Pós-Condição de Falha| A imagem não é carregada ou registrada corretamente no diário de obra.|
|Atores Principais| Usuário.|
|Atores Secundários| Nenhum.|
|Gatilho| Necessidade do colaborador de registrar visualmente uma atividade no diário de obra.|
|Casos Estendidos| UC-005.|

##  Fluxo Principal
**UC-005: Realizar Diário de Obra**

| Passo | Ação |
|-|-|
| 1 | O usuário acessa a funcionalidade de upload de imagens no diário de obra.|
| 2 | O sistema exibe a interface para seleção de imagens.|
| 3 | O usuário seleciona a imagem desejada em seu dispositivo.|
| 4 | O sistema verifica se a imagem selecionada está em um formato suportado.|
| 5 | A IA analisa a imagem e constrói o diário de obra.|
| 6 | O sistema faz o upload da imagem para o servidor.|
| 7 | O usuário finaliza a operação.|

## Fluxo Alternativo

**UC-005: Realizar Diário de Obra**
| Passo | Ação |
|-|-|
| 3.1 | O usuário não possui nenhuma foto disponível.|
| 3.2 | O usuário deve procurar fotos no dispositivo e fazer upload.|
| 4.1 | Imagem fora dos formatos suportados.| 
| 4.2 | Reenviar imagem no formato correto.|
| 7.1 | O usuário não aprova o diário de obra.|
| 7.2 | Solicitar para a IA gerar novamente.|

# Requisito funcional
> * Requisito A.6: O sistema deve permitir que o usuário tenha o Dashboard de resumo de tarefas.

# Descrição do caso de uso
|UC-006|Dashboard de Resumo de Tarefas.|
|-|-|
|Requisitos Relacionados| Requisito A.6 |
|Descrição Detalhada| Tabela com resumo das tarefas a serem feitas e descrição, como também das já realizadas, fotos e descrição do que foi feito, feito automaticamente pela IA.|
|Pré-Condições| Tarefas inseridas; Imagens inseridas|
|Pós-Condição de Sucesso| Dashboard pronto com resumo das tarefas.|
|Pós-Condição de Falha| Após a análise a IA não encontrar tarefas e cancelar o dashboard.|
|Atores Principais| Supervisor.|
|Atores Secundários| Nenhum.|
|Gatilho| Necessidade de supervisionar o andamento das tarefas.|
|Casos Incluídos| Nenhum.|

##  Fluxo Principal

**UC-006: Dashboard de Resumo de Tarefas**
| Passo | Ação |
|-|-|
| 1 | Supervisor solicita um dashboard.|
| 2 | A IA detecta as tarefas.|
| 3 | As resume de maneira simples.|
| 4 | Monta de forma com que seja cronológico.|
| 5 | Apresenta o dashboard.|

## Fluxo Alternativo

**UC-006: Dashboard de Resumo de Tarefas**
| Passo | Ação |
|-|-|
| 2.1 | IA nao encontra tarefa alguma.|
| 2.2 | Avisa o supervisor através de uma mensagem.|
| 4.1 | Datas das tarefas não inseridas|
| 4.2 | Solicita para que o supervisor reveja as datas e prazos.|




# Diagrama de Casos de Uso

![Blank diagram (3)](https://github.com/ceborba/analise-e-projeto-de-sistemas/assets/168678938/30169ae6-ea36-4550-acb5-95ae826381b6)












