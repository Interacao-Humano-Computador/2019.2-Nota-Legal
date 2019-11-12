# Avaliação Heurística

## 1. Status do sistema
### Verificação
    O site informa ao usuário a situação atual do sistema? Essa informação é útil?
### Grau de severidade
    (X) 0 - Sem importância
    ( ) 1 - Cosmético
    ( ) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    ( ) Obstáculo
    ( ) Ruído
### Perspectiva do usuário
    ( ) Problema Geral
    ( ) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    ( ) Problema Principal
    ( ) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário digita na barra de pesquisa algo que não existe no site

    Causa: O site informa que não encontrou resultados para a expressão digitada. De certa forma, o sistema realmente alerta o usuário da situação atual

    Efeito sobre o usuário: Nenhum

    Efeito sobre a tarefa: Nenhum

    Correção possível: Existem alguns pequenos problemas que serão descritos nos próximos tópicos

---

## 2. Compatibilidade do sistema com o mundo real
### Verificação
    A linguagem do site é acessível, sem jargões ou termos técnicos?
### Grau de severidade
    ( ) 0 - Sem importância
    (X) 1 - Cosmético
    ( ) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    ( ) Obstáculo
    (X) Ruído
### Perspectiva do usuário
    ( ) Problema Geral
    (X) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    ( ) Problema Principal
    (X) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário acessa regiões do site que são detalhadas, como "Cidadão"

    Causa: Existem sim termos técnicos como tributos e outras questões governamentais, porém eles são bem explicados e o usuário não precisa de conhecimentos específicos (de economia, por exemplo) para entender o que estã acontecendo. Qualquer usuário com uma simples leitura do texto compreende bem do que se trata. Entretanto, algumas regiões defeituosas do site exibem mensagens de erro, com termos de desenvolvedores, muito confusas para o usuário (essa situação é descrita melhor no tópico 5)

    Efeito sobre o usuário: Confusão caso acesse alguma região problemática, mas nenhum problema ao acessar regiões que funcionam como o esperado

    Efeito sobre a tarefa: Mensagens de erro não ajudam muito o usuário a corrigir o problema

    Correção possível: Sobre as regiões que funcionam bem, não há necessidade de mudanças, mas nas mensagens de erro é necessária uma reformulação com termos mais claros e amigáveis ao usuário leigo em desenvolvimento de software 

---

## 3. Controle do usuário e liberdade
### Verificação
    O usuário se sente no controle do sistema? O sistema se comporta como esperado?
### Grau de severidade
    ( ) 0 - Sem importância
    (X) 1 - Cosmético
    ( ) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    ( ) Obstáculo
    (X) Ruído
### Perspectiva do usuário
    (X) Problema Geral
    ( ) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    ( ) Problema Principal
    (X) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuáro clica no ícone "Estabelecimentos"

    Causa: Uma nova aba do navegador é aberta, o que é um comportamento inesperado

    Efeito sobre o usuário: Desconforto pois era esperado que a página carregasse na mesma aba do navegador

    Efeito sobre a tarefa: Nenhum

    Correção possível: Os comportamentos da pagina não devem surpreender o usuário, então todas as páginas devem ser carregadas na mesma aba do navegador

---

## 4. Consistência e padrões
### Verificação
    Existe um padrão nas telas do site? Este padrão é seguido em todos os lugares possíveis?
### Grau de severidade
    ( ) 0 - Sem importância
    ( ) 1 - Cosmético
    (X) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    ( ) Obstáculo
    (X) Ruído
### Perspectiva do usuário
    (X) Problema Geral
    ( ) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    ( ) Problema Principal
    (X) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário primeiro clica no ícone "Legislação", e depois no ícone "Sorteio"

    Causa: Alguns links abrem uma nova aba do navegador sem necessidade, enquanto outros abrem na mesma aba. Ou seja, existem inconsistências nos links. Além disso, alguns ícones estão disponíveis em determinadas partes do site mas em outras não: por exemplo, o ícone "Mídia" é acessível a partir da tela de cadastro, mas não é acessível a partir da tela inicial

    Efeito sobre o usuário: Desconforto pois era esperado que a página carregasse na mesma aba do navegador

    Efeito sobre a tarefa: Nenhum

    Correção possível: Todos os links do site devem ser carregados na mesma aba, salvo em casos muito específicos.

---
### Verificação
    A acessibilidade do site é consistente? Usuários com necessidades especiais conseguem utilizar todas as páginas do site?
### Grau de severidade
    ( ) 0 - Sem importância
    ( ) 1 - Cosmético
    ( ) 2 - Simples
    (X) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    (X) Obstáculo
    ( ) Ruído
### Perspectiva do usuário
    ( ) Problema Geral
    ( ) Problema Preliminar
    (X) Problema Especial
### Perspectiva da tarefa
    (X) Problema Principal
    ( ) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário está na tela de login

    Causa: Não há as opções de acessibilidade presentes em outras páginas, o que pode atrapalhar ou impossibilitar o acesso de usuários com necessidades especiais

    Efeito sobre o usuário: Frustração, irritação

    Efeito sobre a tarefa: Dificuldade ou impossibilidade de realizar login

    Correção possível: Padronizar, assim como nas outras páginas, a acessibilidade ao usuário

---

## 5. Prevenção de erros
### Verificação
    Caso o usuário acesse alguma região defeituosa do sistema ou algum link quebrado, a mensagem de erro é clara? O sistema auxilia o usuário caso alguma funcionalidade não funciona como deveria?
### Grau de severidade
    ( ) 0 - Sem importância
    ( ) 1 - Cosmético
    ( ) 2 - Simples
    (X) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    (X) Barreira
    ( ) Obstáculo
    ( ) Ruído
### Perspectiva do usuário
    (X) Problema Geral
    ( ) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    (X) Problema Principal
    ( ) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário acessa o ícone "Mídia" a partir da tela de cadastro

    Causa: É exibida uma mensagem de erro com termos muito técnicos e apenas pessoas com conhecimento considerável em programação podem compreender. Claramente o público alvo do sistema não tem obrigação de saber sobre estes termos técnicos.

    Efeito sobre o usuário: Confusão, pois a tela não é muito agradável e os termos utilizados por desenvolvedores de software geralmente são estranhos para leigos

    Efeito sobre a tarefa: O usuário não consegue acessar o ícone "Mídia"

    Correção possível: Em primeiro lugar, o link para "Mídia" deveria ser corrigido, para assim o usuário poder acessar esta parte do site. Mas se não for possível pelo menos deve-se reorganizar a mensagem de erro para ser mais intuitiva e clara para o usuário do sistema.

---

## 6. Reconhecimento ao invés de lembrança
### Verificação
    O site mantém o usuário informado sobre sua localização?
### Grau de severidade
    ( ) 0 - Sem importância
    (X) 1 - Cosmético
    ( ) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    ( ) Obstáculo
    (X) Ruído
### Perspectiva do usuário
    ( ) Problema Geral
    (X) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    ( ) Problema Principal
    (X) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário clica no ícone "Cidadão"

    Causa: Não há nenhum indicador sobre onde o usuário está, ao contrário de outras partes do site, como "Dúvidas"

    Efeito sobre o usuário: Leve desorientação

    Efeito sobre a tarefa: Nenhum

    Correção possível: Criar um padrão em todo o site para orientar seus usuários, principalmente os iniciantes

---

## 7. Flexibilidade e eficiência de uso
### Verificação
    Existe algum tipo de personalização para atender usuários de perfis diferentes? Existem atalhos para agilizar a utilização do site por usuários mais experientes?
### Grau de severidade
    ( ) 0 - Sem importância
    ( ) 1 - Cosmético
    (X) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    ( ) Obstáculo
    (X) Ruído
### Perspectiva do usuário
    ( ) Problema Geral
    (X) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    ( ) Problema Principal
    (X) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário, na página inicial, tenta personalizar algum aspecto qualquer do site ou acessar uma determinada região mais rapidamente

    Causa: Existe uma leve personalização do tamanho da fonte e de contraste de cores, o que facilita o acesso ao site por usuários com algum tipo de problema de vista. Entretanto, existem poucos atalhos explícitos para usuários experientes. O mapa do site, por exemplo, pode ser uma ferramenta interessante mas ela não tem uma acessibilidade muito boa. Uma outra opção de atalho é pelo navegador mas isso está fora do escopo do site

    Efeito sobre o usuário: Acessibilidade melhorada para usuários com problemas de vista, perda de eficiência para usuários experientes

    Efeito sobre a tarefa: Acessibilidade para uns e perda de eficiência para outros

    Correção possível: A acessibilidade poderia ser ainda melhor se tivesse suporte para usuários com daltonismo. Sobre a questão da eficiência, poderia ser mais fácil e rápido acessar o mapa do site

---

## 8. Estética e <i>design</i> minimalista
### Verificação
    A organização do site é boa? As informações mais importantes são facilmente acessíveis?
### Grau de severidade
    ( ) 0 - Sem importância
    ( ) 1 - Cosmético
    (X) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    ( ) Obstáculo
    (X) Ruído
### Perspectiva do usuário
    ( ) Problema Geral
    (X) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    ( ) Problema Principal
    (X) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário entra na página inicial do site

    Causa: Algumas promoções e anúncios não são prioridades, porém recebem muito destaque. Além disso, a paleta de cores pode confundir um pouco, dificultando o acesso a áreas relevantes, como cadastro

    Efeito sobre o usuário: Leve desorientação e distração

    Efeito sobre a tarefa: Pequena perda de eficiência

    Correção possível: É necessário que áreas não tão importantes não recebam tanto detalhamento, e que outras áreas importantes sejam bem mais destacadas para acesso rápido

---

### Verificação
    Existem telas ou funcionalidades desnecessárias?
### Grau de severidade
    ( ) 0 - Sem importância
    ( ) 1 - Cosmético
    (X) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    ( ) Obstáculo
    (X) Ruído
### Perspectiva do usuário
    (X) Problema Geral
    ( ) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    (X) Problema Principal
    ( ) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: Usuário está na página inicial e digita seu CPF para fazer login

    Causa: O usuário é redirecionado para outra página onde precisa inserir CPF de novo e sua senha

    Efeito sobre o usuário: Irritação, confusão

    Efeito sobre a tarefa: Perda de tempo

    Correção possível: Uma tela única para login com campos de CPF, senha e "esqueci minha senha"

---

### Verificação
    A tela de cadastro tem design minimalista? Os campos e botões estão bem posicionados/ajustados?
### Grau de severidade
    ( ) 0 - Sem importância
    ( ) 1 - Cosmético
    (X) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    (X) Obstáculo
    ( ) Ruído
### Perspectiva do usuário
    ( ) Problema Geral
    (X) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    ( ) Problema Principal
    (X) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário digita suas informações na tela de cadastro

    Causa: Os botões de confirmar e limpar dados estão mal posicionados e são muito pequenos, não são intuitivos e dificultam o uso 

    Efeito sobre o usuário: Confusão, desorientação

    Efeito sobre a tarefa: Perda de tempo e de eficiência

    Correção possível: Padronizar os dois botões ao centro da tela, logo abaixo das informações de cadastro, e aumentar o tamanho dos mesmos

---

## 9. Ajudar os usuários a reconhecer, diagnosticar e corrigir erros

### Verificação
    Ao fazer o cadastro no site, o sistema informa ao usuário sobre erros nas informações digitadas? Existe alguma dificuldade para corrigir um erro cometido?
### Grau de severidade
    ( ) 0 - Sem importância
    ( ) 1 - Cosmético
    (X) 2 - Simples
    ( ) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    ( ) Barreira
    ( ) Obstáculo
    (X) Ruído
### Perspectiva do usuário
    (X) Problema Geral
    ( ) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    (X) Problema Principal
    ( ) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: Na tela inicial o usuário digita o seu CPF

    Causa: Não há feedback para o usuário caso o CPF esteja errado ou não cadastrado

    Efeito sobre o usuário: Confusão

    Efeito sobre a tarefa: Perda de tempo

    Correção possível: Como este é um problema derivado de outro (duas telas para digitar CPF), resolver o outro problema automaticamente resolveria este. Outra solução seria dar feedback na primeira tela, apesar de não ser tão eficiente

---

## 10. Ajuda e documentação
### Verificação
    Caso o usuário tenha alguma dúvida ou dificuldade em utilizar o sistema, é fornecido algum tipo de ajuda ou suporte? O usuário consegue tirar suas dúvidas sem sair do site?
### Grau de severidade
    ( ) 0 - Sem importância
    ( ) 1 - Cosmético
    ( ) 2 - Simples
    (X) 3 - Grave
    ( ) 4 - Catastrófico
### Natureza do problema
    (X) Barreira
    ( ) Obstáculo
    ( ) Ruído
### Perspectiva do usuário
    (X) Problema Geral
    ( ) Problema Preliminar
    ( ) Problema Especial
### Perspectiva da tarefa
    (X) Problema Principal
    ( ) Problema Secundário
### Perspectiva do projeto
    ( ) Problema Falso
    ( ) Problema Novo
    ( ) Não se aplica
### Descrição do problema
    Contexto: O usuário tenta acessar o link "Perguntas frequentes"

    Causa: O usuário recebe uma mensagem de erro (podendo ser um problema para quem não sabe inglês) informando que o link está quebrado. Não é possível acessar as perguntas frequentes

    Efeito sobre o usuário: Frustração pois não é possível acessar um recurso básico que deveria estar sempre disponível

    Efeito sobre a tarefa: Não é possível tirar a dúvida relativa ao site através do link
    
    Correção possível: Disponibilização urgente de uma FAQ

---

## Referências Bibliográficas

> MACIEL, C.; NOGUEIRA, J. L. T.; CIUFFO, L. N.; GARCIA, A.C.B. (2004), “Avaliação heurística de sítios na web”.
Instituto de Computação – UFF, Niterói/RJ.

> NIELSEN, J.; MACK, R. L. Usability Inspection Methods Computer. John Wiley & Sons, New York, NY, 1994.

## Histórico de versões

| Data | Versão | Descrição | Autor(es) |
|:--:|:--:|:--:|:--:|
|10/09/19|1.0|Criação do documento|Renan Cristyan|
|03/10/19|1.1|Adição do documento no repositório|Renan Cristyan|
|12/11/19|2.0|Adição e classificação de 4 novos erros|Lucas Alexandre, Renan Cristyan|