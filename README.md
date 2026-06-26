Atendimento Digital e Ouvidoria - EEEP Professor Onélio Porto

Este é um projeto de extensão feito para automatizar o processo de feedbacks escolar. Desenvolvido no Typebot, o fluxo atua como uma triagem inteligente para a ouvidoria da instituição, garantindo que as mensagens dos alunos e responsáveis sejam registradas com segurança e organização.

Este repositório serve como um portfólio prático de automação, desenvolvimento de sistemas e suporte de TI. O fluxo foi estruturado pensando não apenas na usabilidade do usuário final, mas também na segurança da informação, aplicando conceitos de validação de identidade.

Como Testar o Projeto:
Para interagir com o fluxo real e testar o funcionamento do robô na prática, acesse o link público:
[https://typebot.co/projeto-onelio-porto](https://typebot.co/projeto-onelio-porto)

Funcionalidades Principais:

* Saudação Dinâmica: O sistema avalia a variável de tempo e adapta a mensagem inicial automaticamente com base no horário do dia ("Bom dia!", "Boa tarde!" ou "Boa noite!").
* Autenticação de Identidade (PIN): Para liberar o formulário de ouvidoria, o sistema gera um código PIN aleatório de 4 dígitos usando uma função JavaScript personalizada nativa no fluxo.
* Disparo Automático de E-mail: O PIN de segurança gerado é enviado diretamente para o endereço eletrônico fornecido pelo usuário através de uma integração direta com o Gmail.
* Categorização de Demandas: O usuário pode direcionar sua mensagem para três áreas específicas de feedback: Elogios, Reclamações ou Sugestões.
* Integração de Banco de Dados: Todos os feedbacks autenticados são inseridos de forma automatizada em uma planilha do Google Sheets, registrando parâmetros como Nome, Categoria, Mensagem, E-mail e Data.
* Transbordo para Suporte: O fluxo prevê a opção de redirecionamento para o "Atendimento Humano" com a equipe de apoio caso haja essa necessidade.
* Interface Customizada: O projeto utiliza injeção de CSS personalizado para arredondar os campos de entrada de texto e aplica a fonte tipográfica "StratfordEF-Regular".

Tecnologias e Blocos Utilizados:

* Typebot (Motor de orquestração do chatbot).
* JavaScript (Bloco de código "Code" contendo a expressão matemática Math.floor para geração do PIN).
* Gmail API (Disparo automatizado de e-mails de verificação).
* Google Sheets API (Armazenamento estruturado em tabelas).
