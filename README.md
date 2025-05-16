
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

🔗[Link do Padlet](https://padlet.com/viniciussian/kanban-uafrrybncz92z4fy) <br>
🔗[Link para o excalidraw]( https://excalidraw.com/#room=f1d87532f9bbabaea1f4,NYTZh_8ymW2AHqC0TZn36g)

## 1. 📌 Introdução

***1.1.  👥 Nome do Grupo***

Indicar o nome e github dos integrantes do grupo

Grupo 9

Integrantes:

👤 veterano00

👤 Tgardelli

👤 gustavolovizotto

👤 diegocorteL33T

👤 JoaoTrindade1404

***1.2.   💻 Nome do Sistema***

HandControl

***1.3.  🎯 Propósito do Sistema***

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela *`HandControl`*, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema `HandControl` é permitir o controle de volume de um dispositivo (como computador ou mídia player) via gestos das mãos
capturados por uma câmera, oferecendo uma forma mais natural, rápida e acessível de interação com a máquina, especialmente útil para pessoas com dificuldade de usar dispositivos físicos.

***1.2. 🧑‍💼 Público Alvo***

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes... *<descrever aqui se existir mais interessados e que participarão do desenvolvimento do sistema>*

***1.3. 👤 Descrição dos usuários***

Usuários em geral que buscam mais praticidade;

Pessoas com deficiência motora ou mobilidade reduzida;

Profissionais que trabalham com som/mídia e querem controle por gestos;

Pessoas interessadas em tecnologias inovadoras e interfaces naturais.

*** 🎭 Personas:***

<div>
<img src="./Screenshot_1.png" >
<img src="./Screenshot_2.png">
</div>

***Análise da situação atual: antes da introdução de sua solução***

*`1. O que as pessoas fazem?`*
*`2. Quais os artefatos envolvidos?`*
*`3. O que elas precisam saber?`*

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

*`1. O que as pessoas fazem?`*
*`2. Quais os artefatos envolvidos?`*
*`3. O que elas precisam saber?`*

***Cenário: Antes***

*<Preencher com o cenário idealizado antes da aplicação do seu sistema.>*

***Cenário: Depois***

*<Preencher com o cenário idealizado depois da aplicação do seu sistema.>*

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

| Código | Requisito Funcional                              | Descrição                                                                                                         | Dependências                                                                                   |
|--------|--------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| RF01   | Controle de Volume por Gestos                    | O sistema deve permitir que o usuário ajuste o volume do dispositivo utilizando gestos.                         | RF04, RF16                                                                                     |
| RF02   | Pausar/Retomar Vídeo                             | O sistema deve permitir que o usuário pause e retome a reprodução de vídeos por meio de gestos.                 | RF04, RF16                                                                                     |
| RF03   | Navegação em Mídia via Gestos                    | O sistema deve permitir que o usuário avance ou retroceda conteúdos de mídia por meio de gestos.                | RF04, RF16                                                                                     |
| RF04   | Processamento em Tempo Real                      | O sistema deve processar e executar comandos gestuais imediatamente após sua detecção.                          | —                                                                                              |
| RF05   | Mapeamento Personalizado de Gestos               | O sistema deve permitir que o usuário configure quais gestos executam quais ações.                              | RF11, RF12, RF14                                                                               |
| RF06   | Interface Intuitiva                              | O sistema deve fornecer orientações visuais e dicas contextuais para auxiliar o uso, sem necessidade de conhecimento técnico. | —                                                                              |
| RF07   | Feedback Multimídia                              | O sistema deve fornecer feedback visual ou sonoro cada vez que um gesto for reconhecido.                        | RF04                                                                                           |
| RF08   | Ativação/Desativação do Reconhecimento de Gestos | O sistema deve permitir que o usuário ative ou desative o reconhecimento de gestos conforme sua preferência.    | RF04                                                                                           |
| RF09   | Cadastro de Usuário                              | O sistema deve permitir que novos usuários se cadastrem.                                                         | —                                                                                              |
| RF10   | Autenticação do Usuário                          | O sistema deve permitir que usuários efetuem login de forma segura.                                              | RF09                                                                                           |
| RF11   | Cadastro de Gestos Personalizados                | O sistema deve permitir que o usuário registre gestos próprios para comandos específicos.                       | RF12                                                                                           |
| RF12   | Cadastro de Gestos via Câmera                    | O sistema deve permitir que o usuário cadastre novos gestos capturados por meio da câmera do dispositivo.       | —                                                                                              |
| RF13   | Controle Sem Mouse/Teclado                       | O sistema deve permitir que o usuário controle o dispositivo exclusivamente por gestos, sem mouse ou teclado.   | RF01, RF02, RF03, RF04, RF05, RF16                                                             |
| RF14   | Perfis de Gestos Customizados                    | O sistema deve permitir que o usuário salve perfis de gestos para diferentes atividades ou perfis de usuário.   | RF05, RF09, RF10                                                                               |
| RF15   | Central de Ajuda Multimídia                      | O sistema deve oferecer uma central de ajuda com FAQs e suporte visual ou sonoro para auxiliar o usuário.       | RF01–RF05, RF13, RF14, RF16                                                                    |
| RF16   | Gestos Predefinidos para Comandos Comuns         | O sistema deve incluir gestos predefinidos para comandos como pausar vídeo, ajustar volume e avançar mídias.    | —                                                                                              |
| RF17   | Login com Conta Google e Facebook                | O sistema deve permitir que o usuário faça login utilizando contas do Google ou Facebook.                       | RF18                                                                                           |
| RF18   | Integração com API OAuth                         | O sistema deve integrar com a API OAuth do Google e do Facebook.                                                 | —                                                                                              |
| RF19   | Recuperação de Senha                             | O sistema deve permitir que o usuário solicite a recuperação de senha.                                           | RF09, RF10                                                                                     |
| RF20   | Redefinição de Senha                             | O sistema deve enviar um e-mail com link de redefinição de senha ao usuário.                                     | RF19                                                                                           |
| RF21   | Histórico de Gestos Realizados                   | O sistema deve permitir que o usuário consulte o histórico de gestos realizados.                                | RF04                                                                                           |
| RF22   | Ativar/Desativar Feedback Multimídia             | O sistema deve permitir que o usuário ative ou desative o feedback visual ou sonoro.                            | RF07                                                                                           |






***2.2. Requisitos Não Funcionais***

| Código | Requisito Não Funcional    | Descrição                                                                                                                                                                               | Prioridade/Observação                                         |
|--------|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| NFR01  | Desempenho                 | O sistema deve realizar o reconhecimento de gestos em tempo real, com tempo de resposta inferior a 100 milissegundos, garantindo fluidez e interatividade.                          | Alta – essencial para a experiência do usuário.             |
| NFR02  | Usabilidade                | A interface deve ser intuitiva, autoexplicativa e acessível, permitindo que usuários com diferentes níveis de conhecimento consigam operar o sistema sem complexidade.                  | Alta – foco na experiência do usuário.                       |
| NFR03  | Confiabilidade             | O sistema precisa atingir uma taxa de acerto de reconhecimento superior a 98%, minimizando falsos positivos e negativos, e garantindo consistência na operação.                     | Alta – para assegurar confiança e eficiência.                |
| NFR04  | Segurança                  | Os dados dos usuários, incluindo configurações e perfis personalizados, devem ser protegidos por criptografia e mecanismos de autenticação robusta, prevenindo acessos não autorizados. | Alta – indispensável para proteger os usuários.              |
| NFR05  | Compatibilidade            | O sistema deve operar de maneira consistente em diferentes dispositivos e sistemas operacionais, integrando com os recursos (como câmeras e microfones) necessários ao reconhecimento. | Média – importante para alcance e flexibilidade.             |
| NFR06  | Escalabilidade             |A arquitetura adotada deve permitir a inclusão futura de novos gestos e funcionalidades, sem comprometer o desempenho ou a experiência do usuário.	Média – garantindo evolução sem retrabalho.                                 | Média – garantindo evolução sem retrabalho.                  |
| NFR07  | Manutenibilidade           | O software deve possuir uma estrutura modular e bem documentada, facilitando manutenções, correções e a implementação de melhorias futuras.                                           | Média – essencial para a longevidade do sistema.             |
| NFR08  | Portabilidade              | O sistema deve ser adaptável a diversas plataformas (desktop, mobile), com requisitos mínimos de hardware e software bem definidos, para assegurar seu pleno funcionamento.         | Média – amplia o mercado e a flexibilidade.                  |
| NFR09  | Feedback e Tratamento de Erros | Em casos de falhas ou problemas, o sistema deve fornecer mensagens claras e detalhadas, permitindo que o usuário entenda a causa e, quando possível, receba orientações para a resolução. | Alta – melhora a transparência e suporte.                    |
| NFR10  | Eficiência de Recursos     | O software deve otimizar o uso dos recursos computacionais, evitando consumo excessivo de memória e processamento, mesmo em dispositivos com hardware modesto.                        | Alta – para garantir estabilidade mesmo em dispositivos menos robustos. |
| NFR11  | Compatibilidade    | O software deve ser desenvolvido utilizando a linguagem Python                        | Alta – para garantir a compatibilidade com outras APIs |
| NFR12  | Desempenho    | O sistema deve utlizar aceleração CUDA                       | Alta – para garantir o processamento em tempo real dos gestos |


***2.3. Perguntas***

*<Arquivo com as perguntas realizadas na entrevista .>*

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

***2.5. Histórias do Usuário***

*<Imagem, arquivo (PDF), link com as Histórias de Usuário.>*

***2.6. Diagramas de Caso de Uso e Especificações***

*<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>*

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8. Matrizes de Rastreabilidade***

*<Imagem, arquivo (PDF), link com Matriz de Rastreabilidade.>*

***2.9. Protótipos***

prototipo não existe 0-0

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
