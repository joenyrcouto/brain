---
id: 99 Regras
format: html
aliases: []
tags: []
---

# Explicação conceitual

1. 00 Notas Rápidas – O Ponto de Captura Rápida  
 * O que é: O local para toda a desordem inicial.  
 * Como usar: Use esta pasta para capturar qualquer coisa rapidamente, sem se preocupar com formato, título ou organização. Notas de aula, ideias de madrugada, links, pensamentos soltos. O objetivo é a velocidade e o baixo atrito.  
 * Por quê: Para não interromper o fluxo de uma aula ou de um pensamento. A captura e a organização são atividades distintas e devem ser feitas em momentos diferentes.  
 * Mandamento: Esta pasta deve ser processada e esvaziada regularmente. Seu estado ideal é o vazio.  
   
1. 10 Notebook (Lm) – A Mesa de Trabalho Ativa  
 * O que é: O local onde o diálogo com os notebooklm acontece.  
 * Como usar: Para cada caderno, aqui onde será salvo os insight e questões resolvidas
   
1. 20 Permanentes – O Arquivo de Conhecimento Destilado  
 * O que é: O coração do meu conhecimento. As minhas ideias atômicas e refinadas.  
 * Como usar: Quando um insight da pasta 10 amadurecer, transforme-o em uma nota aqui. Uma nota permanente deve seguir 3 regras:  
   * Atômica: Abordar apenas uma ideia, conceito ou modelo.  
   * Com minhas palavras: O conteúdo deve ser 100% autoral, escrito da forma como eu entendo.  
   * Conectada: Deve linkar para outras notas permanentes relacionadas e para a nota de processamento que a originou.  
 * Por quê: É o ato de reformular e conectar que solidifica o aprendizado a longo prazo. Este é o meu Zettelkasten pessoal, a base para futuros trabalhos e ideias.  
   
1. 30 Mapas Do Conhecimento (MOCs) – O Atlas do Meu Cérebro  
 * O que é: Meus índices e sumários sobre grandes temas.  
 * Como usar: Crie e mantenha notas que servem como um hub central para um tópico (ex: "MOC - Álgebra Linear"). Adicione links para as Notas Permanentes relevantes à medida que elas são criadas.  
 * Por quê: Para fornecer uma estrutura de alto nível ao conhecimento, facilitar a navegação, revelar conexões entre sub-tópicos e identificar lacunas no meu entendimento.  
   
Manutenção do Sistema  
 * O Fluxo é Sagrado: Respeite o fluxo 00 -> 10 -> 20 -> 30. Evite pular etapas.  
 * Como usar o banco de questões e Spaced repetation : *completar*

Para a biblioteca basta criar o acervo dentro de `99 Arquivos brutos/biblioteca` com o template de acervo. O acervo pode ser referência dentro de outras notas 
# Configurações essenciais

## Instalar os Plugins Essenciais:  
   * Vá para Configurações > Community plugins > Browse.  
   * Instale e habilite os seguintes plugins:  
     * Templater: Para gerenciar e inserir seus templates dinâmicos.  
     * Dataview: Para criar as listas e tabelas automáticas.  
     * PDF++: Para a funcionalidade de linkar seleções de PDF.  
     * Tasks: Para agregar todas as suas tarefas (- [ ]).  
     * Spaced Repetition: Para os flashcards de revisão.  
       
 * Configurar o Templater:  
   * Vá para Configurações > Templater.  
   * Template folder location: Aponte para a sua pasta de templates.  
   * Trigger Templater on new file creation: Ative esta opção. Isso é crucial. Garante que, ao criar um novo arquivo, o Templater aplique o template correto automaticamente.  
   * Folder Templates: Configure regras para aplicar templates específicos a pastas específicas. Isso automatiza todo o processo:  
     * Clique em "Add new folder".  
     * Folder: 00_CaixaDeEntrada -> Template: 99_Sistema/Templates/Tpl-Captura  
     * Folder: 20_Processamento -> Template: 99_Sistema/Templates/Tpl-Fonte  
     * Folder: 30_Permanentes -> Template: 99_Sistema/Templates/Tpl-Permanente  
     * Folder: 40_MapasDoConhecimento -> Template: 99_Sistema/Templates/Tpl-MOC 
        
 * Configurar o Dataview:  
   * Vá para Configurações > Dataview.  
   * Enable JavaScript Queries: Ative esta opção.  
   * Enable Inline JavaScript Queries: Ative esta opção.  
   * Isso garante que todas as queries nos seus templates funcionem corretamente.  
     
 * Configurar o Spaced Repetition:  
   * Vá para Configurações > Spaced Repetition.  
   * Em Flashcard Tags, adicione a tag que você definiu no template, por exemplo: `#revisao`.  
   * Isso diz ao plugin para procurar por flashcards em qualquer nota que contenha essa tag.  
 
