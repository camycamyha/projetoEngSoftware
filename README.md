# uHelp
  uHelp é uma plataforma criada para auxiliar pessoas comuns a resolver problemas técnicos do dia a dia, através de consultas online com especialistas das mais diversas áreas. 
  
  A plataforma consiste em um site e em um aplicativo no qual o usuário poderá entrar em contato com especialistas técnicos já presentes em outras plataformas, como o YouTube por exemplo, solicitando por uma consultoria que ocorre no formato de uma reunião por chamada de vídeo online, onde o mesmo poderá tirar dúvidas e resolver seus problemas técnicos por conta própria, recebendo a orientação de como diagnosticar e resolver qualquer situação. 

  O objetivo do uHelp é oferecer um espaço onde profissionais e clientes possam estabelecer uma comunicação segura e facilitada, oferecendo métodos alternativos na prestação de serviços.
  
  A dinâmica de funcionamento do uHelp é simples: pessoas que já disponibilizam seus conhecimentos técnicos em outras redes sociais em função de auxiliar outros em suas possíveis dificuldades diárias, possuirão um perfil profissional na plataforma uHelp, onde poderão disponibilizar seus serviços de forma individual e online, conseguindo novos clientes sendo remunerado por cada atendimento.

## Participantes 

- Camila Martinz Queiroz 

- Jesley Domingues Sales 

- Lívia Sanches Gonzaga de Camargo 

- Nicole das Chagas Cardoso 

- Renan Nunes Mion 

- Sara Gongora 

## Tecnologias 

- HTML/CSS 

- SQL 

- JavaScript 

- Java 

## Público Alvo 
Pessoas acima de 18 anos que estejam buscando solucionar problemas do dia a dia por conta própria ou que queiram compartilhar seu conhecimento para ajudar na criação de conteúdo da plataforma e fornecer consultorias virtuais.

## Principais Dores 
- Resolução de problemas de forma especializada;
- Atendimento imediato conforme necessidade;
- Navegação intuitiva e de fácil localização de categorias;
- Mecanismo para a realização de denúncias de conteúdos inapropriados;
- Levantamento de feedback dos usuários;
- Filtragem da criação de conta para criadores de conteúdo;
- Listagem de consultores disponíveis no momento desejado.

## Forma de Monetização 
- Anúncios dentro da plataforma;
- Consutoria virtual paga;
- Assinatura da plataforma.

# Briefing uHelp

## Resumo: Sistema de Consultoria Virtual

- Especialista em diversas áreas postam diariamente vídeos dando dicas e ensinando procedimentos básicos de suas áreas nas redes sociais, como no YouTube por exemplo. Para muitos, criar esse tipo de conteúdo online se tornou sua ocupação e fonte de renda principal, chegando até mesmo a prestar serviços de consultoria online. Esses profissionais trabalham criando e postando vídeos, divulgando informações e conversando com seus clientes através das redes sociais. 
  
- Muitas vezes essa comunicação é feita de forma informal, através de meios de comunicação digitais comuns, sem nenhum controle ou regulamentação que padronize esse processo e facilite na hora de estabelecer acordos entre o consultor e o cliente.

- Na primeira versão do projeto será desenvolvida uma plataforma na qual os clientes poderão agendar consultorias online com o profissional de sua preferência. Esse processo será feito de forma eficaz e intuitiva, garantindo assim um acordo justo e formal entre prestador de serviço e comprador.

## Requisitos da primeira versão (MPV):

- A plataforma funcionará 24h por dia, com exceção dos momentos necessários para manutenção. Apenas as consultorias terão data e hora determinadas por cada consultor na plataforma.
  
- Cada consultor disponibiliza as datas e os horários que estarão disponíveis para consultas, podendo ser acessado através do perfil do profissional, quando o cliente solicitar uma consulta.  

- Um profissional pode estar ativo ou inativo na plataforma.

- O sistema não deve permitir agendar uma consultoria em data e horário que não estejam previamente   disponibilizadas pelo consultor. Assim como o sistema não deve permitir o agendamento de duas consultorias na mesma data e horário. 

- Tanto o cliente quanto o consultor podem solicitar pelo cancelamento da consultoria já marcada.

- O sistema permitirá que o cliente dê um feedback depois que a consultoria for finalizada. 

- A plataforma só permitirá o agendamento de consultoria para consultores que estiverem ativos no sistema. 

- A plataforma não deve permitir agendar em datas no passado. 

## Observações:
- Cadastro de usuário: Nome, e-mail, senha e telefone.

- Cadastro de consultor: Nome, e-mail, senha, telefone e conta bancária.

- O agendamento deverá ter: Id do usuário, Id do consultor, valor, data e horário.

- Cancelamento de consultoria: Caso o consultor cancele, retorna o pagamento ao usuário. Caso o usuário cancele, deduz 10% de taxa de cancelamento.

- Duração da consultoria: Quando o horário da consultoria estiver próximo do fim, o sistema emitirá uma notificação para ambas as partes.

- Listagem de consultorias: O consultor poderá ver todas as consultorias agendadas e suas principais informações.

- Feedback: Após uma consultoria, o usuário poderá dar até 5 estrelas de avaliação e fazer um comentário, se desejado.

## Dois perfis:

#### Usuário/Cliente 

- Pode acessar todo o conteúdo do site, incluindo     textos e vídeos dos consultores do site. 
- Permite agendar, cancelar e reagendar consultorias. 
- Realizar pagamentos pela própria plataforma. 
- Dar feedbacks para a plataforma e profissionais. 

#### Consultor 

- Pode fazer uploads de conteúdo no formato de texto e vídeo de própria autoria na plataforma.
- Acessar outros conteúdos do site.
- Permite agendar, cancelar e reagendar consultorias.
- Receber pagamento. 
- Consultar estatísticas do perfil e o extrato de pagamento. 
- Determinar data e hora que ficará disponível para atender a novas consultorias.
- Contato com clientes que solicitaram consultoria.

## Responsividade:

- Utilizar uma abordagem de responsividade no design para garantir que o site funcione bem em uma ampla variedade de dispositivos, desde computadores desktop até smartphones e tablets.  

- Layout fluído que se ajusta automaticamente ao tamanho da tela do dispositivo. Isso significa que elementos, como vídeos, blocos de informação e menus, se redimensionam e reorganizam conforme necessário para preencher o espaço disponível. 

- Um design adaptativo oferecendo diferentes experiências para o usuário em diferentes tamanhos de tela, por exemplo, em telas menores o menu principal pode ser substituído por um menu de hamburgueres, que são três linhas horizontais para economizar espaço.  

- Compatibilidade com dispositivos móveis.  

- Imagens e vídeos otimizados para carregamento rápido e exibição adequada em várias resoluções de telas para ajudar a melhorar o desempenho da página, independentemente do dispositivo. 

- Vídeos responsivos para se ajustarem automaticamente ao tamanho da tela, redimensionam-se conforme necessário para se encaixar na largura do contêiner em que estão incorporados.  

- Chamada de vídeo pelo site para garantir a segurança tanto do usuário quanto do consultor.  

## Casos de Uso

<img src="docs\usecase\use-cases.png" alt="Casos de uso">

## Modelo Conceitual

<img src="docs\modConceitual\Modelo Conceitual.png" alt="Modelo Conceitual">

## Protótipo da Tela Principal em Baixa Fidelidade

<img src="docs\prototipoTelas\tela1.jpg" alt="Tela Principal Menu">

<img src="docs\prototipoTelas\tela2.jpg" alt="Tela Principal Pesquisa">
