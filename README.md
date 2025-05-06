
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet: https://padlet.com/viniciussian/kanban-uafrrybncz92z4fy <br>
[Link para o excalidraw]( https://excalidraw.com/#room=f1d87532f9bbabaea1f4,NYTZh_8ymW2AHqC0TZn36g)

## 1. Introdução

***1.1.  Nome do Grupo***

Indicar o nome e github dos integrantes do grupo

Grupo 9

Integrantes: veterano00, Tgardelli, gustavolovizotto, diegocorteL33T, JoaoTrindade1404

***1.2.  Nome do Sistema***

HandControl

***1.3.  Propósito do Sistema***

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela *`HandControl`*, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema `HandControl` é permitir o controle de volume de um dispositivo (como computador ou mídia player) via gestos das mãos
capturados por uma câmera, oferecendo uma forma mais natural, rápida e acessível de interação com a máquina, especialmente útil para pessoas com dificuldade de usar dispositivos físicos.

***1.2.  Público Alvo***

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes... *<descrever aqui se existir mais interessados e que participarão do desenvolvimento do sistema>*

***1.3. Descrição dos usuários***

Usuários em geral que buscam mais praticidade;

Pessoas com deficiência motora ou mobilidade reduzida;

Profissionais que trabalham com som/mídia e querem controle por gestos;

Pessoas interessadas em tecnologias inovadoras e interfaces naturais.

***Personas:***

*<Imagem, arquivo (PDF), link com as Personas.>*

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

| Código  | Requisito Funcional Formulado                                                                                                                                                                                   |
|---------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [RF01]  | O sistema **deve captar** as imagens da câmera **em tempo real com no mínimo 30 FPS** para alimentar o processamento dos gestos.                                                                              |
| [RF02]  | O sistema **deve utilizar** a biblioteca OpenCV **para capturar e processar** as imagens, realizando o pré-processamento dos dados visuais.                                                                     |
| [RF03]  | O sistema **deve detectar e reconhecer** os gestos **com uma precisão mínima de 85% e baixa latência** para garantir respostas imediatas.                                                                      |
| [RF04]  | O sistema **deve mapear** os gestos reconhecidos **aos comandos pré-definidos** que permitam ações como aumentar ou diminuir o volume, pausar, avançar e retroceder vídeos.                                 |
| [RF05]  | O sistema **deve fornecer** feedback visual e/ou sonoro **imediatamente após a identificação e execução de um gesto** para confirmar a ação executada.                                                     |
| [RF06]  | O sistema **deve permitir** a configuração e personalização dos gestos e de suas respectivas ações **oferecendo uma interface amigável** para facilitar essa tarefa.                                   |
| [RF07]  | O sistema **deve emitir** alertas **em caso de falha na captura ou no processamento das imagens** para informar o usuário sobre possíveis problemas operacionais.                                       |
| [RF08]  | O sistema **deve possibilitar** o cadastro e a autenticação de usuários **por meio de telas de login e registro, incluindo a autenticação via Facebook e Google** para garantir o acesso seguro.          |
| [RF09]  | O sistema **deve oferecer** um módulo tutorial **com vídeos e áudios explicativos** para auxiliar novos usuários no processo de aprendizagem do uso da plataforma.                                       |
| [RF10]  | O sistema **deve permitir** a integração **com softwares externos, tais como plataformas educacionais e leitores de tela** para ampliar a inclusão digital dos usuários.                                  |
| [RF11]  | O sistema **deve registrar e manter** logs **das ações e dos eventos de reconhecimento de gestos** para fins de auditoria e suporte técnico.                                                                 |

***2.2. Requisitos Não Funcionais***

*<Link, imagem, arquivo com os requisitos não funcionais.>*

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
