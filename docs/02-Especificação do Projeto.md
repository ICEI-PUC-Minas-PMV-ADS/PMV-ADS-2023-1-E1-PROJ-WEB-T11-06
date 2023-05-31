# Especificações do Projeto
Produto Final

Website e Aplicativo

Estratégia

Será a principal ferramenta de conexão entre doador e receptor de medicamentos e aparelhos de saúde. Deve ser simples e fácil de usar.

Descrição do produto

O site deve ser desenvolvido em html e css para possibilitar a visualização em dispositivos móveis. Deve ser fácil de usar e rápido para carregar. Deve permitir ainda que catálogos de remédios e equipamentos de saúde sejam facilmente atualizados.
Usuários devem conseguir se cadastrar com facilidade porém o site deve conter verificação de segurança. 

As áreas que o site deve conter são:

* Home: Mostruario principal com as principais atualizações do site .

* Pesquisa: A listagem de remédios e aparelhos de saúde que podem ser visualizados que são doados através do site. “Caso não tenha para doação irá ficar com a cor cinza” 
Doadores por região como bairro município ou estado. 

* Remédios disponíveis: Formulário para buscar remédios e aparelhos de saúde que tem disponível para doação.

* Contato: Dúvidas, soluções e sugestões será respondida via e-mail em até 24 horas uteis via e-mail. 

Principal diferencial a ser conquistado

O melhor site especializado em doar remédios e equipamentos de saúde


## Personas

Pedro França Costa tem 33 anos é suporte de informática da ONG Mais Saude. Pensa em se desenvolver profissionalmente através de um mestrado fora do país.
Recebe grande quantidade de remédios da populaçao e do SUS e deseja doar com urgênia para liberar espaço na ONG. 

Fernanda Lucia Mota tem 28 anos é estudante de advocacia e está desempregada no momento. Sonha em ser advogada criminal. No momento está desempregada e necessita de remédios para se tratar de doenças emocionais e mentais. Como está desempregada ela cuida da sua mãe que é paraplegica. 

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Pedro França Costa  | Doar remédios                      | 1 - Evitar desperdícios milionários em medicamentos que passaram do prazo de validade.
|Pedro França Costa  | Doar remédios                      | 2 - Apoiar e proteger pessoas que precisam 
|Pedro França Costa  | Doar remédios                      | 3 – Liberar e adquirir espaço logico na ONG
|Pedro França Costa  | Doar equipamentos de saúde         | 1 – Socorrer quem necessita de tratamento ou recuperação da saúde
|Pedro França Costa  | Doar equipamentos de saúde         | 2 – Liberar e adquirir espaço logico na ONG

|EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE`|PARA ... `MOTIVO/VALOR`                 |
|---------------------|-----------------------------------|----------------------------------------|
|Fernanda Lucia Mota  | Receber remédios                  | 1 - Está desempregada.
|Fernanda Lucia Mota  | Receber remédios                  | 2 - Necessita tratar de síndrome do pânico, borderline e depressão. 
|Fernanda Lucia Mota  | Receber equipamentos de saúde     | 1 – Mãe necessita de cadeira de rodas
                                                      
## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID   | Descrição do Requisito  | Prioridade |
|-----|-----------------------------------------|----|
|RF-01| Login de acesso do usuário | ALTA | 
|RF-02| O site deve exibir a localização no MAPA do doador e dar baixa no estoque online quando o usuário retirar o mesmo | ALTA |
|RF-03| O site irá oferecer uma funcionalidade de pesquisa para permitir ao usuário localizar um medicamento específico | ALTA |
|RF-04| O site deve ter um interface de fácil acesso para os usuários | ALTA |
|RF-05| O site irá conter um mostruário com os medicamentos disponíveis | MÉDIA | 
|RF-06| O site irá permitir ser acessado tanto no desktop quanto no celular e em APK | MÉDIA | 
|RF-07| O site deverá conter uma recomendação de remédios mais pesquisados para facilitar a busca | MÉDIA | 
|RF-08| O site deve permitir feedback do doador e do usuário | BAIXA |
|RF-09| O site deve permitir função de APOIO ao software com PIX | BAIXA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada | ALTA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  MÉDIA | 
|RNF-003| O site deve ser compatível com os principais navegadores (Google Chrome, Firefox, Microsoft Edge) |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
