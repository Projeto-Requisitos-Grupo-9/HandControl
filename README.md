
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

O objetivo do sistema `HandControl` é permitir o controle de ações de um dispositivo (como computador ou celular) via gestos das mãos
capturados por uma câmera, oferecendo uma forma mais natural, rápida e acessível de interação com a máquina, especialmente útil para pessoas com dificuldade de usar dispositivos físicos.

***1.4. 🧑‍💼 Público Alvo***

Este documento se destina a arquitetos e engenheiros de software, testadores e stakeholders.

***1.5. 👤 Descrição dos usuários***

Usuários em geral que buscam mais praticidade;

Pessoas com deficiência motora ou mobilidade reduzida;

Profissionais que trabalham com som/mídia e querem controle por gestos;

Pessoas interessadas em tecnologias inovadoras e interfaces naturais.

*** 🎭 Personas:***


# 📘 Estudo de Cenários - HandControl

## 🔍 Análise da situação atual: antes da introdução de sua solução

**1. O que as pessoas fazem?**  
Elas usam teclado e mouse convencionais para executar atividades no computador.

**2. Quais os artefatos envolvidos?**  
Teclado, mouse, softwares gráficos, sistemas operacionais, aplicativos de produtividade.

**3. O que elas precisam saber?**  
Como usar dispositivos de entrada convencionais (teclado/mouse), comandos de software, atalhos de produtividade, ergonomia.

---

## 🔄 Análise das tarefas depois: como serão executadas as suas tarefas com sua solução

**1. O que as pessoas fazem?**  
Controlam o computador por meio de gestos captados pela webcam, usando o sistema HandControl.

**2. Quais os artefatos envolvidos?**  
Webcam, sistema HandControl, softwares gráficos ou de trabalho adaptados.

**3. O que elas precisam saber?**  
Gestos compatíveis com o sistema, como configurar e usar o HandControl, noções básicas de acessibilidade digital.

---

## 🎭 Cenário: Antes

### 👨‍💻 Lucas Menezes

Lucas é um designer gráfico que passa muitas horas em frente ao computador utilizando programas como Adobe Photoshop, Illustrator e After Effects. Ele costuma alternar frequentemente entre ferramentas e janelas com o uso de teclado e mouse, o que exige movimentos repetitivos. Lucas sente que o excesso dessas ações impacta sua produtividade e provoca desconfortos físicos, como dores nos punhos.

Ele tenta resolver isso criando atalhos e usando softwares de automação, mas nem sempre os resultados são eficientes. Lucas se sente frustrado principalmente quando os softwares não respondem com precisão aos comandos, o que atrasa seu fluxo criativo.

---

### 👩‍💻 Isabela Duarte

Isabela é uma programadora Fullstack e Mobile que trabalha com demandas intensas de codificação. Ela utiliza teclado e mouse durante longas jornadas, mas sofre com uma leve lesão por esforço repetitivo (LER), o que torna a digitação e uso contínuo do mouse dolorosos. Mesmo assim, ela precisa cumprir prazos rigorosos e realizar testes frequentes no computador.

Isabela já tentou usar soluções de acessibilidade, como ditado por voz e atalhos de teclado personalizados, mas sentiu que não se adaptavam bem à sua rotina. Ela se sente limitada e, às vezes, com receio de piorar sua condição de saúde.

---

## ✨ Cenário: Depois

### 👨‍💻 Lucas Menezes

Lucas agora utiliza o sistema HandControl, que permite controlar funções do computador através de gestos realizados diante da webcam. Ao configurar gestos personalizados para alternar entre ferramentas, aplicar comandos e até acionar automações, ele consegue manter o foco criativo sem interrupções físicas. A produtividade de Lucas aumenta, e ele relata menos dores e maior fluidez em seu trabalho.

Além disso, o sistema se adapta aos seus hábitos, possibilitando que ele personalize comandos conforme seu fluxo de trabalho em softwares gráficos.

---

### 👩‍💻 Isabela Duarte

Isabela adota o HandControl como alternativa ergonômica para codificação e testes. Ao usar gestos simples para executar comandos frequentes, ela reduz consideravelmente o uso contínuo do teclado e do mouse, aliviando os sintomas da LER. Ela também valoriza a interface inclusiva do sistema, que oferece feedback visual dos gestos reconhecidos.

Agora, Isabela sente que pode trabalhar com mais conforto e segurança, mantendo sua produtividade sem comprometer a saúde. Ela até colabora no desenvolvimento de novas funcionalidades do sistema, sugerindo melhorias com base em sua experiência como desenvolvedora.

---

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

| Código | Requisito Funcional                    | Descrição                                                                 | Prioridade | Dependências             |
|--------|----------------------------------------|---------------------------------------------------------------------------|------------|---------------------------|
| RF01   | Controle de Volume por Gestos          | O sistema deve permitir que o usuário ajuste o volume do dispositivo utilizando gestos. | M          | RF04, RF16                |
| RF02   | Pausar/Retomar Vídeo                   | O sistema deve permitir que o usuário pause e retome a reprodução de vídeos por meio de gestos. | M          | RF04, RF16                |
| RF03   | Navegação em Mídia via Gestos          | O sistema deve permitir que o usuário avance ou retroceda conteúdos de mídia por meio de gestos. | M          | RF04, RF16                |
| RF04   | Processamento em Tempo Real            | O sistema deve processar e executar comandos gestuais imediatamente após sua detecção. | M          | —                         |
| RF05   | Mapeamento Personalizado de Gestos     | O sistema deve permitir que o usuário configure quais gestos executam quais ações. | M          | RF11, RF12                |
| RF06   | Interface Intuitiva                    | O sistema deve fornecer orientações visuais e dicas contextuais para auxiliar o uso, sem necessidade de conhecimento técnico. | C          | —                         |
| RF07   | Feedback Multimídia                    | O sistema deve fornecer feedback visual ou sonoro cada vez que um gesto for reconhecido. | S          | RF04                      |
| RF08   | Ativação/Desativação do Reconhecimento | O sistema deve permitir que o usuário ative ou desative o reconhecimento de gestos conforme sua preferência. | M          | RF04                      |
| RF09   | Cadastro de Usuário                    | O sistema deve permitir que novos usuários se cadastrem.                  | M          | —                         |
| RF10   | Autenticação do Usuário                | O sistema deve permitir que usuários efetuem login de forma segura.      | M          | RF09                      |
| RF11   | Cadastro de Gestos Personalizados      | O sistema deve permitir que o usuário registre gestos próprios por meio de imagens para comandos específicos. | M          | RF12                      |
| RF12   | Cadastro de Gestos via Câmera          | O sistema deve permitir que o usuário cadastre novos gestos capturados por meio da câmera do dispositivo. | M          | —                         |
| RF13   | Controle Sem Mouse/Teclado             | O sistema deve permitir que o usuário controle o dispositivo exclusivamente por gestos. | M          | RF01-RF05, RF16           |
| RF14   | Perfis de Gestos Customizados          | O sistema deve permitir que o usuário salve perfis de gestos para diferentes atividades ou perfis de usuário. | S          | RF05, RF09, RF10          |
| RF15   | Central de Ajuda Multimídia            | O sistema deve oferecer uma central de ajuda com FAQs e suporte visual ou sonoro para auxiliar o usuário. | S          | —                         |
| RF16   | Gestos Predefinidos                    | O sistema deve incluir gestos predefinidos para comandos como pausar vídeo, ajustar volume e avançar mídias. | M          | —                         |
| RF17   | Login com Conta Google e Facebook      | O sistema deve permitir que o usuário faça login utilizando contas do Google ou Facebook. | C          | RF18                      |
| RF18   | Integração com API OAuth               | O sistema deve integrar com a API OAuth do Google e do Facebook.         | C          | —                         |
| RF19   | Recuperação de Senha                   | O sistema deve permitir que o usuário solicite a recuperação de senha.   | M          | RF09, RF10                |
| RF20   | Redefinição de Senha                   | O sistema deve enviar um e-mail com link de redefinição de senha ao usuário. | M          | RF19                      |
| RF21   | Histórico de Gestos Realizados         | O sistema deve permitir que o usuário consulte o histórico de gestos realizados. | C          | RF04                      |
| RF22   | Ativar/Desativar Feedback Multimídia   | O sistema deve permitir que o usuário ative ou desative o feedback visual ou sonoro. | C          | RF07                      |
| RF23   | Login com Reconhecimento Facial        | O sistema deve permitir que usuários efetuem login por reconhecimento facial. | M          | RF09                      |
| RF24   | Login com Reconhecimento de Voz        | O sistema deve permitir que usuários efetuem login por reconhecimento de voz. | M          | RF09                      |
| RF25   | Tutorial Interativo e Calibração       | O sistema deve guiar o novo usuário em um tutorial inicial e permitir a calibração da câmera. | M          | RF16                      |
| RF26   | Feedback de Gesto Inválido             | O sistema deve notificar o usuário de forma visual ou sonora se um movimento não for reconhecido como um gesto válido. | S          | RF07                      |
| RF27   | Alteração de Senha                     | O sistema deve permitir que um usuário autenticado possa alterar sua própria senha. | M          | RF10                      |
| RF28   | Exclusão de Conta                      | O sistema deve permitir que o usuário delete permanentemente sua conta e todos os dados associados. | S          | RF10                      |
| RF29   | Configuração de Sensibilidade          | O sistema deve permitir ao usuário ajustar a sensibilidade do reconhecimento de gestos (ex: Preciso, Relaxado). | S          | RF04                      |
| RF30   | Seleção de Dispositivo de Câmera       | O sistema deve permitir que o usuário escolha qual dispositivo de câmera utilizar, caso haja mais de um disponível. | S          | —                         |







***2.2. Requisitos Não Funcionais***

| Código | Requisito Não Funcional                | Descrição                                                                 | Prioridade | Dependências             |
|--------|----------------------------------------|---------------------------------------------------------------------------|------------|---------------------------|
| NFR01  | Desempenho                             | O sistema deve realizar o reconhecimento de gestos em tempo real, com tempo de resposta inferior a 100 milissegundos. | M          | RF04                      |
| NFR02  | Usabilidade                            | O sistema deve possuir uma interface intuitiva, autoexplicativa e acessível. | M          | RF06                      |
| NFR03  | Confiabilidade                          | O sistema deve atingir uma taxa de acerto de reconhecimento superior a 98%, minimizando falsos positivos e negativos. | M          | —                         |
| NFR04  | Segurança                               | O sistema deve proteger por criptografia AES os dados dos usuários, incluindo informações pessoais e perfis. | M          | RF09, RF10                |
| NFR05  | Compatibilidade                         | O sistema deve ser compatível com Windows 10/11 e Ubuntu 22.04 em arquitetura Desktop. | S          | —                         |
| NFR06  | Escalabilidade                          | O sistema deve utilizar uma arquitetura que permite a inclusão futura de novos gestos e funcionalidades. | S          | —                         |
| NFR07  | Manutenibilidade                        | O software deve possuir uma estrutura modular e bem documentada, facilitando manutenções e correções. | S          | —                         |
| NFR08  | Portabilidade                           | O sistema deve conter requisitos mínimos de hardware, assegurando seu funcionamento em hardware comum. | S          | —                         |
| NFR09  | Feedback e Tratamento de Erros          | O sistema deve fornecer mensagens claras e detalhadas em caso de falhas ou problemas. | M          | —                         |
| NFR10  | Eficiência de Recursos                  | O software deve otimizar o uso dos recursos computacionais (CPU/Memória) durante a operação. | M          | —                         |
| NFR11  | Compatibilidade (Linguagem)             | O software deve ser desenvolvido utilizando a linguagem Python.           | M          | —                         |
| NFR12  | Desempenho (Hardware)                   | O sistema deve utilizar aceleração CUDA quando uma GPU NVIDIA compatível estiver disponível. | S          | NFR08                    |
| NFR13  | Responsividade da Interface             | A interface gráfica deve se adaptar automaticamente a diferentes tamanhos e resoluções de tela. | M          | RF06                      |
| NFR14  | Tolerância a Falhas                     | O sistema deve continuar funcionando parcialmente mesmo que algumas funcionalidades estejam indisponíveis. | S          | —                         |
| NFR15  | Log de Atividades                       | O sistema deve registrar logs das atividades dos usuários e do sistema para fins de auditoria e diagnóstico. | S          | —                         |
| NFR16  | Latência de Feedback                    | O tempo entre a detecção de um gesto e o feedback ao usuário não deve ultrapassar 150 milissegundos. | M          | RF07                      |
| NFR17  | Internacionalização                     | O sistema deve oferecer suporte a múltiplos idiomas, incluindo no mínimo português e inglês. | S          | —                         |
| NFR18  | Atualizações Automáticas                | O sistema deve ser capaz de receber atualizações de forma automática ou semi-automática. | C          | —                         |
| NFR20  | Isolamento de Ambiente                  | O sistema deve funcionar em sandbox ou contêiner para evitar interferências com o sistema operacional. | C          | —                         |
| NFR21  | Backup de Configurações                 | O sistema deve permitir o backup e restauração das configurações do usuário. | C          | RF14                      |
| NFR22  | Privacidade e Anonimização              | Dados sensíveis ou de identificação pessoal devem ser anonimizados nos logs do sistema. | M          | NFR15                    |
| NFR23  | Consumo em Ocioso                       | O sistema deve ter um consumo de recursos (CPU/Memória) próximo de zero quando estiver em segundo plano/ocioso. | M          | —                         |



***2.3. Perguntas***

# Roteiro Simplificado de Entrevista – HandControl

## 1. Sobre o uso de tecnologia

1.1. Você pode nos contar um pouco sobre como usa computadores ou celulares no dia a dia?  
(Aberta)

1.2. Com que frequência você usa computador?  
☐ Nunca ☐ Raramente ☐ Às vezes ☐ Frequentemente ☐ Sempre

1.3. Já usou algum recurso de acessibilidade, como comandos de voz ou leitores de tela?  
☐ Sim ☐ Não  
Se sim, qual? (Aberta)

---

## 2. Dificuldades e necessidades

2.1. Quais dificuldades você tem ao usar mouse ou teclado?  
(Aberta)

2.2. Já usou algum software de acessibilidade? Qual?  
(Aberta)

2.3. Você se sentiria seguro usando um sistema que reconhece gestos pela webcam?  
☐ Sim ☐ Não  
Por quê? (Aberta)

2.4. Já deixou de fazer alguma tarefa no computador por dificuldade de uso? Qual?  
(Aberta)

2.5. O que você costuma fazer quando tem dificuldades no computador?  
☐ Procuro tutoriais na internet  
☐ Peço ajuda a alguém  
☐ Tento resolver sozinho  
☐ Outro: ___________

---

## 3. Preferências e expectativas

3.1. O que você esperaria de um sistema como o HandControl?  
(Aberta)

3.2. Você prefere usar mouse/teclado ou acha que o controle por gestos seria mais fácil? Por quê?  
(Aberta)

3.3. Quais dessas características são mais importantes em um sistema de acessibilidade?  
☐ Facilidade de uso  
☐ Segurança  
☐ Compatibilidade com programas  
☐ Personalização  
☐ Outro: ___________

---

## 4. Interface e usabilidade

4.1. Você se sente confortável em usar a webcam do computador?  
☐ Sim ☐ Não

4.2. Você teria dificuldade para fazer gestos com a mão na frente da câmera? Por quê?  
(Aberta)

4.3. Já usou algum app ou jogo com reconhecimento de movimento pela câmera? Como foi?  
(Aberta)

---

## 5. Priorização de Funcionalidades (RF)

> Use a escala **MoSCoW** para indicar a prioridade:  
> - **M (Must)**: Essencial  
> - **S (Should)**: Importante  
> - **C (Could)**: Opcional  
> - **W (Won’t)**: Não necessário

5.1. Controle de Volume por Gestos (RF01): [M/S/C/W]  
5.2. Pausar/Retomar Vídeo por Gestos (RF02): [M/S/C/W]  
5.3. Mapeamento Personalizado de Gestos (RF05): [M/S/C/W]  
5.4. Cadastro de Gestos via Câmera (RF12): [M/S/C/W]  
5.5. Login com Conta Google/Facebook (RF17): [M/S/C/W]  
5.6. Histórico de Gestos Realizados (RF21): [M/S/C/W]  
5.7. Outro recurso importante? Qual? (Aberta)

---

## 6. Priorização de Requisitos Não Funcionais (NFR)

> Avalie a importância de cada item de 1 (nada importante) a 5 (muito importante):

6.1. Resposta rápida do sistema: [1–5]  
6.2. Interface simples e acessível: [1–5]  
6.3. Segurança e privacidade: [1–5]  
6.4. Funcionar em diferentes dispositivos: [1–5]  
6.5. Usar em desktop e mobile: [1–5]  
6.6. Suporte a mais de um idioma: [1–5]  
6.7. Backup e restauração de configurações: [1–5]

---

## 7. Considerações Finais

7.1. Qual funcionalidade é mais essencial para você? Por quê?  
(Aberta)

7.2. Tem alguma funcionalidade que você considera desnecessária?  
(Aberta)

7.3. Gostaria de deixar mais algum comentário ou sugestão?  
(Aberta)



***2.4. Entrevista***

[🔗 Ver Entrevista no Google Drive](https://drive.google.com/file/d/1_38xa8RQHDIcWjzBDP3dSNnYS1Yyim1r/view?usp=sharing)

[🔗Acesse a entrevista por escrito](./Entrevista%20por%20escrito.pdf)




***2.5. Histórias do Usuário***

#### RF01 – Controle de Volume por Gestos
**Como** usuário, **eu quero** ajustar o volume do dispositivo utilizando gestos, **de modo que** eu possa aumentar ou diminuir o som sem tocar no aparelho, **porque** isso facilita o controle em situações onde o toque não é conveniente.

#### RF02 – Pausar/Retomar Vídeo
**Como** usuário, **eu quero** pausar e retomar vídeos por meio de gestos, **de modo que** eu controle a reprodução de conteúdo facilmente, **porque** isso torna o uso mais prático e acessível.

#### RF03 – Navegação em Mídia via Gestos
**Como** usuário, **eu quero** avançar ou retroceder conteúdos de mídia usando gestos, **de modo que** eu navegue entre cenas ou faixas com facilidade, **porque** isso agiliza a interação sem precisar de controle físico.

#### RF04 – Processamento em Tempo Real
**Como** usuário, **eu quero** que os gestos sejam processados em tempo real, **de modo que** o sistema responda imediatamente aos comandos, **porque** isso melhora a experiência de uso e evita atrasos.

#### RF05 – Mapeamento Personalizado de Gestos
**Como** usuário, **eu quero** configurar quais gestos executam quais ações, **de modo que** eu personalize a forma de controlar o dispositivo, **porque** isso torna o sistema mais adaptado às minhas preferências.

#### RF06 – Interface Intuitiva
**Como** usuário, **eu quero** que o sistema mostre dicas visuais e orientações, **de modo que** eu entenda como usar os gestos, **porque** isso facilita o aprendizado e uso, mesmo sem conhecimento técnico.

#### RF07 – Feedback Multimídia
**Como** usuário, **eu quero** receber feedback visual ou sonoro ao realizar um gesto, **de modo que** eu saiba que o comando foi reconhecido, **porque** isso me dá uma confirmação sobre a execução da ação.

#### RF08 – Ativação/Desativação do Reconhecimento de Gestos
**Como** usuário, **eu quero** ativar ou desativar o reconhecimento de gestos, **de modo que** eu tenha controle sobre quando o sistema está "ouvindo" gestos, **porque** isso evita comandos indesejados.

#### RF09 – Cadastro de Usuário
**Como** novo usuário, **eu quero** me cadastrar no sistema, **de modo que** eu possa acessar e configurar meus dados, **porque** isso é necessário para personalizar minha experiência.

#### RF10 – Autenticação do Usuário
**Como** usuário cadastrado, **eu quero** fazer login de forma segura, **de modo que** meus dados e configurações sejam protegidos, **porque** isso garante privacidade e segurança.

#### RF11 – Cadastro de Gestos Personalizados
**Como** usuário, **eu quero** cadastrar meus próprios gestos por meio de imagens associadas a comandos específicos, **de modo que** o sistema reconheça e execute ações com base nesses gestos personalizados, **porque** isso facilita a personalização e usabilidade.

#### RF12 – Cadastro de Gestos via Câmera
**Como** usuário, **eu quero** cadastrar novos gestos usando a câmera do dispositivo, **de modo que** o sistema aprenda meus movimentos, **porque** isso permite mais liberdade e customização.

#### RF13 – Controle Sem Mouse/Teclado
**Como** usuário, **eu quero** controlar o dispositivo apenas com gestos, **de modo que** eu não precise de mouse ou teclado, **porque** isso oferece uma experiência mais acessível e moderna.

#### RF14 – Perfis de Gestos Customizados
**Como** usuário, **eu quero** salvar perfis de gestos diferentes para diversas atividades ou perfis de uso, **de modo que** eu possa alternar facilmente entre eles, **porque** isso facilita a adaptação a diferentes contextos.

#### RF15 – Central de Ajuda Multimídia
**Como** usuário, **eu quero** acessar uma central de ajuda com FAQs e vídeos/som, **de modo que** eu tire dúvidas facilmente, **porque** isso me auxilia no uso do sistema sem depender de suporte técnico.

#### RF16 – Gestos Predefinidos para Comandos Comuns
**Como** usuário, **eu quero** usar gestos predefinidos para ações como pausar vídeo ou ajustar volume, **de modo que** eu já tenha comandos prontos para uso, **porque** isso acelera o aprendizado e a interação.

#### RF17 – Login com Conta Google e Facebook
**Como** usuário, **eu quero** fazer login com minha conta do Google ou Facebook, **de modo que** eu acesse o sistema rapidamente, **porque** isso evita criar uma nova senha e agiliza o acesso.

#### RF18 – Integração com API OAuth
**Como** sistema, **eu quero** integrar com a API OAuth, **de modo que** usuários possam autenticar com contas externas, **porque** isso melhora a conveniência e segurança.

#### RF19 – Recuperação de Senha
**Como** usuário, **eu quero** solicitar recuperação de senha, **de modo que** eu recupere o acesso ao sistema, **porque** posso esquecer minha senha.

#### RF20 – Redefinição de Senha
**Como** usuário, **eu quero** receber um e-mail com link para redefinir minha senha, **de modo que** eu possa criar uma nova, **porque** isso me ajuda a voltar a acessar minha conta.

#### RF21 – Histórico de Gestos Realizados
**Como** usuário, **eu quero** consultar o histórico de gestos realizados, **de modo que** eu veja quais comandos usei e quando, **porque** isso ajuda no acompanhamento e correções.

#### RF22 – Ativar/Desativar Feedback Multimídia
**Como** usuário, **eu quero** ativar ou desativar feedback visual ou sonoro, **de modo que** eu ajuste a resposta do sistema conforme minha preferência, **porque** isso melhora minha experiência.

#### RF23 – Autenticação por Reconhecimento Facial
**Como** usuário, **eu quero** fazer login por reconhecimento facial, **de modo que** o acesso seja automático e seguro, **porque** isso elimina a necessidade de digitar senhas.

#### RF24 – Autenticação por Reconhecimento de Voz
**Como** usuário, **eu quero** fazer login por reconhecimento de voz, **de modo que** o acesso seja mais prático, **porque** isso oferece uma alternativa segura sem senha.

#### RF25 – Tutorial Interativo e Calibração
**Como** um novo usuário, **eu quero** passar por um tutorial interativo na primeira vez que abro o aplicativo, **de modo que** eu aprenda os gestos básicos e possa calibrar a câmera para o meu ambiente, **porque** isso garante que eu consiga usar o sistema corretamente desde o início.

#### RF26 – Feedback de Gesto Inválido
**Como** usuário, **eu quero** receber um feedback claro (visual ou sonoro) quando meu gesto não for reconhecido, **de modo que** eu saiba que preciso tentar o gesto novamente, **porque** a ausência de resposta me deixa sem saber se o sistema está travado ou se eu fiz o gesto errado.

#### RF27 – Alteração de Senha
**Como** um usuário logado, **eu quero** acessar meu perfil e alterar minha senha, **de modo que** eu possa manter minha conta segura, **porque** é uma prática de segurança padrão poder atualizar minhas credenciais periodicamente.

#### RF28 – Exclusão de Conta
**Como** usuário, **eu quero** ter a opção de excluir permanentemente minha conta e todos os meus dados, **de modo que** eu tenha controle total sobre minhas informações pessoais, **porque** isso garante minha privacidade conforme as boas práticas (LGPD).

#### RF29 – Configuração de Sensibilidade
**Como** usuário, **eu quero** encontrar uma opção nas configurações para ajustar a sensibilidade do reconhecimento de gestos (ex: "Preciso" ou "Relaxado"), **de modo que** o sistema se adapte melhor à minha maneira de gesticular, **porque** isso torna a experiência de uso mais confortável e precisa para mim.

#### RF30 – Seleção de Dispositivo de Câmera
**Como** usuário que possui múltiplas câmeras, **eu quero** poder selecionar qual câmera o sistema deve usar, **de modo que** eu possa escolher a que estiver melhor posicionada, **porque** isso me dá flexibilidade e garante a melhor captura de imagem possível.


***2.6. Diagramas de Caso de Uso e Especificações***

<div>
<img src="./Diagrama de caso de usio.jpg" >
</div>

***2.7. Diagramas de Atividades***

<div>
<img src="./Diagrama de atividade.jpg" >
</div>

***2.8. Matrizes de Rastreabilidade***

# Matriz de Rastreabilidade

| ID    | Requisito                                                                 | Prioridade  | Dependências           | Fonte / Objetivo do Projeto                             | Verificação (Testes)                           | Validação (Critério de Aceite)                                                                 |
|-------|---------------------------------------------------------------------------|-------------|-------------------------|----------------------------------------------------------|------------------------------------------------|--------------------------------------------------------------------------------------------------|
| RF01  | Controle de Volume                                                        | ALTA (M)    | RF04, RF16              | Controle essencial do sistema sem periféricos            | Teste de Unidade, Teste de Integração         | O volume do SO aumenta/diminui com o gesto correspondente                                        |
| RF02  | Pausar/Retomar Vídeo                                                      | ALTA (M)    | RF04, RF16              | Controle essencial de mídia                              | Teste de Unidade, Teste de Integração         | A reprodução de vídeo é pausada/retomada com o gesto correspondente                              |
| RF03  | Navegação em Mídia                                                        | ALTA (M)    | RF04, RF16              | Controle essencial de mídia                              | Teste de Unidade, Teste de Integração         | A mídia avança/retrocede com o gesto correspondente                                              |
| RF04  | Processamento em Tempo Real                                               | ALTA (M)    | —                       | Garantir experiência de usuário fluida                   | Teste de Performance (Latência)               | O comando é executado em <100ms após a detecção do gesto                                         |
| RF05  | Mapeamento Personalizado                                                  | ALTA (M)    | RF11, RF12              | Aumentar a personalização e adaptabilidade               | Teste de UI, Teste de Unidade                 | Usuário consegue remapear a ação "Pausar" para um novo gesto                                     |
| RF06  | Interface Intuitiva                                                       | BAIXA (C)   | —                       | Reduzir a curva de aprendizado (Suporta NFR02)           | Teste de Usabilidade, Revisão de UI/UX        | Um novo usuário realiza uma tarefa básica sem ajuda externa                                      |
| RF07  | Feedback Multimídia                                                       | MÉDIA (S)   | RF04                    | Melhorar a usabilidade e confirmação da ação             | Teste de UI, Teste de Integração              | O sistema exibe um ícone ou emite um som quando um gesto é validado                             |
| RF08  | Ativação/Desativação                                                      | ALTA (M)    | RF04                    | Dar controle total ao usuário                            | Teste de UI, Teste de Unidade                 | O sistema para de responder a gestos quando a função está desativada                             |
| RF09  | Cadastro de Usuário                                                       | ALTA (M)    | —                       | Gerenciamento de perfis e configurações                  | Teste de UI, Teste de Integração              | Um novo usuário consegue criar uma conta com sucesso                                              |
| RF10  | Autenticação do Usuário                                                   | ALTA (M)    | RF09                    | Acessar configurações e perfis salvos                    | Teste de UI, Teste de Segurança               | Um usuário cadastrado consegue fazer login com credenciais válidas                               |
| RF11  | Cadastro de Gestos (Imagens)                                              | ALTA (M)    | RF12                    | Aumentar a personalização                                | Teste de UI, Teste de Integração              | O usuário consegue cadastrar um novo gesto enviando uma imagem                                   |
| RF12  | Cadastro de Gestos (Câmera)                                               | ALTA (M)    | —                       | Facilitar a personalização de gestos                     | Teste de UI, Teste de Integração              | O usuário consegue cadastrar um novo gesto usando a câmera em tempo real                         |
| RF13  | Controle Sem Mouse/Teclado                                                | ALTA (M)    | RF01–RF05, RF16         | Aumentar a acessibilidade e inovação                     | Teste de Cenário Completo                     | Um usuário consegue navegar, controlar mídia e volume usando apenas gestos                       |
| RF14  | Perfis de Gestos Customizados                                             | MÉDIA (S)   | RF05, RF09, RF10        | Melhorar conveniência para múltiplos usos                | Teste de UI, Teste de Unidade                 | Usuário consegue salvar um perfil "Jogos" e carregá-lo posteriormente                            |
| RF15  | Central de Ajuda Multimídia                                               | MÉDIA (S)   | —                       | Ajudar o usuário e reduzir suporte externo               | Revisão de Conteúdo, Teste de UI              | A central de ajuda é acessível e contém informações para as funções principais                   |
| RF16  | Gestos Predefinidos                                                       | ALTA (M)    | —                       | Garantir funcionalidade básica imediata                  | Teste de Unidade, Teste de Integração         | Os gestos padrão para volume, pausa e navegação funcionam corretamente                           |
| RF17  | Login Social                                                              | BAIXA (C)   | RF18                    | Facilitar o processo de login                            | Teste de Integração com API Externa          | Usuário consegue se autenticar com conta Google/Facebook                                         |
| RF18  | Integração com API OAuth                                                  | BAIXA (C)   | —                       | Base técnica para login social                           | Teste de Integração                           | O sistema comunica corretamente com os endpoints da API OAuth                                    |
| RF19  | Recuperação de Senha                                                      | ALTA (M)    | RF09, RF10              | Gerenciamento de conta                                   | Teste de UI, Teste de Integração              | O usuário consegue iniciar o processo de recuperação de senha                                     |
| RF20  | Redefinição de Senha                                                      | ALTA (M)    | RF19                    | Completar fluxo de recuperação de senha                  | Teste de Integração com serviço de e-mail     | O usuário recebe um e-mail válido ao solicitar a redefinição de senha                            |
| RF21  | Histórico de Gestos                                                       | BAIXA (C)   | RF04                    | Permitir auditoria e depuração pelo usuário              | Teste de UI, Teste de Integração              | O histórico exibe os últimos gestos reconhecidos e as ações executadas                           |
| RF22  | Ativar/Desativar Feedback                                                 | BAIXA (C)   | RF07                    | Aumentar personalização da experiência                   | Teste de UI, Teste de Unidade                 | O feedback multimídia para de ser exibido quando desativado                                      |
| RF23  | Login com Reconhecimento Facial                                           | ALTA (M)    | RF09                    | Método de login moderno e seguro                         | Teste de Biometria, Teste de Segurança        | Um usuário cadastrado consegue fazer login via reconhecimento facial                             |
| RF24  | Login com Reconhecimento de Voz                                           | ALTA (M)    | RF09                    | Método de login alternativo e acessível                  | Teste de Biometria, Teste de Segurança        | Um usuário cadastrado consegue fazer login via reconhecimento de voz                             |
| RF25  | Tutorial Interativo e Calibração                                          | ALTA (M)    | RF16                    | Melhorar primeira experiência do usuário                 | Teste de Usabilidade                          | Um novo usuário completa o tutorial e calibra o sistema com sucesso                              |
| RF26  | Feedback de Gesto Inválido                                                | MÉDIA (S)   | RF07                    | Reduzir frustração e ajudar no aprendizado               | Teste de UI/UX                                | O sistema exibe uma mensagem "Gesto não reconhecido" ao invés de silêncio                         |
| RF27  | Alteração de Senha                                                        | ALTA (M)    | RF10                    | Funcionalidade essencial de segurança                    | Teste de UI, Teste de Segurança               | Um usuário logado consegue alterar sua senha com sucesso                                          |
| RF28  | Exclusão de Conta                                                         | MÉDIA (S)   | RF10                    | Garantir privacidade e controle do usuário (LGPD)        | Teste de UI, Teste de Integração              | A conta e os dados do usuário são removidos do sistema após confirmação                           |
| RF29  | Configuração de Sensibilidade                                             | MÉDIA (S)   | RF04                    | Adaptar o sistema a diferentes usuários e ambientes      | Teste de UI, Teste de Unidade                 | O usuário pode alternar entre os níveis de sensibilidade "Preciso" e "Relaxado"                  |
| RF30  | Seleção de Dispositivo de Câmera                                          | MÉDIA (S)   | —                       | Melhorar compatibilidade com setups diversos             | Teste de UI, Teste de Integração              | O sistema lista as câmeras disponíveis e utiliza a que foi selecionada                           |


***2.9. Protótipos***

[Protótipo Hand Control](https://ninjamock.com/s/8Q4R7Lx)

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
