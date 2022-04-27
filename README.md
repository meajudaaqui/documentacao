# Concepção do Projeto

## Escopo

O sistema tem por objetivo geral auxiliar aos usuários a verificarem o status em tempo real de serviços e aplicações na web.

O sistema tem como sua tela inicial um conteúdo dinâmico onde veremos os últimos casos de instabilidades/falhas e ou serviços e aplicações mais pesquisados no momento.
O sistema deve permitir que qualquer usuário navegue por todas as páginas, e consiga buscar e selecionar o serviço e/ou aplicação que deseja verificar o status. O usuário terá como opção ver o status atual, ver o status semanal e ou por determinado período que assim desejar.
O sistema irá possibilitar o usuário reportar caso tenha passado por uma instabilidade ou problemas relacionados, efetuando seu cadastro, para assim efetuar o seu reporte.
Ao realizar o cadastro no sistema, o usuário terá a opção de criar reportes indicando título, aplicação e uma breve descrição do ocorrido, além, da possibilidade de anexar prints, por fim poderá também marcar para receber um e-mail a partir do momento que for detectado uma normalidade no sistema.
O sistema deverá permitir a geração de relatórios específicos para cada aplicação/serviço, relatórios por períodos e relatórios por tipos de falhas.
A implementação do sistema trará aos usuários um melhor retorno para identificação de problemas, além de conter um histórico datado das  falhas ocorridas detectadas.

Vale salientar que o sistema não entregará certeza absoluta pois funcionará em sua grande forma analisando relatórios em tempo real e também baseado em relatos de usuários

## Casos de Uso 

### Caso 1
#Usuário se cadastrar 


Ator(es): Usuário do sistema


Descrição: O usuário se inscreve na plataforma para fazer uso da mesma


Gatilho: Ter acesso a plataforma


Pré-condições: Plataforma funcionando e usuário com acesso a plataforma


Pós-condições: Usuário cadastrado na plataforma


Fluxo principal (esboço): 


1 - Usuário acessa a plataforma


2 - Usuário acessa a opção "Cadastre-se" na tela


3 - Usuário preenche os campos com seus dados


4 - Usuário confirma seus dados 


5 - Usuário é cadastrado



### Caso 2
#Registrar problemas em um serviço 
Ator(es): Usuário do sistema
Descrição: O usuário relata problema ou incidente em um serviço
Gatilho: Ter algum incidente no serviço em questão
Pré-condições: Plataforma funcionando, usuário cadastrado e logado, serviço listado na plataforma
Pós-condições: Registro concluído sobre incidente no serviço
Fluxo principal (esboço):
1 - Usuário logado acessa a opção "Reporte um incidente"
2 - Usuário preenche os campos relacionados ao serviço e descreve o incidente
3 - É gerado um novo report sobre o serviço 

### Caso 3
#Solicitar relatório
Ator(es): Usuário do sistema
Descrição: O usuário solicita um relatório gerado pela plataforma
Gatilho: Usuário interessado em saber as condições do serviço
Pré-condições: Plataforma funcionando, registro de incidentes antigos no serviço em questão
Pós-condições: Relatório gerado pela plataforma
Fluxo principal (esboço):
1 - Usuário logado acessa a página do serviço desejado na plataforma
2 - Usuário solicita um relatório através da opção "Gerar relatório"
3 - Um relatório é gerado e baixado pelo dispositivo do usuário

## Requisitos Funcionais

- [ ] Se Conectar com o Nosso Banco de Dados
- [ ] Incluir Registros
- [ ] Validar Registros
- [ ] Criar conta
- [ ] Authenticar conta
- [ ] Gerar Relatorios
- [ ] Enviar mensagem no telegram

## Requisitos Não Funcionais

- [ ] Funcionar em todos os Navegadores
- [ ] Garantir integridade dos dados
- [ ] Estar na Lingua Portuguesa 
- [ ] Deve Proteger Dados Sensiveis
- [ ] Funcionamento 24/7
