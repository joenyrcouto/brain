---
id: 99 Regras
format: html
aliases: []
tags: []
---
# Explicação conceitual

[[00-rápidas-tlp]] – O Ponto de Captura Rápida  
 * O que é: O local para toda a desordem inicial.  
 * Como usar: Use esta pasta para capturar qualquer coisa rapidamente, sem se preocupar com formato, título ou organização. Notas de aula, ideias de madrugada, links, pensamentos soltos. O objetivo é a velocidade e o baixo atrito.  
 * Por quê: Para não interromper o fluxo de uma aula ou de um pensamento. A captura e a organização são atividades distintas e devem ser feitas em momentos diferentes.  
 * Mandamento: Esta pasta deve ser processada e esvaziada regularmente. Seu estado ideal é o vazio.  
   
[[01-notelm-tlp]] – A Mesa de Trabalho Ativa  
 * O que é: O local onde o diálogo com os notebooklm acontece.  
 * Como usar: Para cada caderno, aqui onde será salvo os insight.
 * A partir dela, crie os [[99-exercícios-tlp]] com suas devidas tags em `99-brutos/exercícios`.
   
[[02-zettel-tlp]] – O Arquivo de Conhecimento Destilado  
 * O que é: O coração do meu conhecimento. As minhas ideias atômicas e refinadas.  
 * Como usar: Quando um conhecimento da pasta 01 amadurecer, transforme-o em uma nota aqui de forma modular (que possa ser usado como referência por qualquer outro assunto). Uma nota permanente deve seguir 3 regras:  
   * Atômica: Abordar apenas uma ideia, conceito ou modelo.  
   * Com minhas palavras: O conteúdo deve ser 100% escrito pessoalmente, escrito da forma como eu entendo.  
   * Conectada: Deve linkar para a nota de processamento que a originou.  
 * Por quê: É o ato de reformular e conectar que solidifica o aprendizado a longo prazo. Este é o meu Zettelkasten pessoal, a base para futuros trabalhos e ideias.  
   
[[03-MOC-tlp]] – O Atlas do Meu Cérebro  
 * O que é: Meus índices e sumários sobre grandes temas.  
 * Como usar: Crie e mantenha notas que servem como um hub central para um tópico (ex: "MOC - Álgebra Linear"). Adicione links para as Notas Permanentes relevantes à medida que elas são criadas.  
 * Por quê: Para fornecer uma estrutura de alto nível ao conhecimento, facilitar a navegação, revelar conexões entre sub-tópicos e identificar lacunas no meu entendimento.  
   
Manutenção do Sistema  
 * O Fluxo é Sagrado: Respeite o fluxo 00 -> 10 -> 20 -> 30. Evite pular etapas.
   
Em `98-bases` temos nossas bibliotecas e catálogos.
 * Crie pastas para as bases dentro de `99-brutos`.
   * Para livros, basta criar [[99-Acervo-tlp]] dentro de `99-brutos/books` com o template de acervo. O acervo pode ser referência dentro de outras notas 

Em `99-brutos` é onde são salvos os arquivos brutos do vault. Imagens, áudios, vídeos etc.
 * Crie pastas para conteúdos estruturados e recorrentes, como o exemplo, temos `98-bases`.
 * Evite ficar colocando imagens ou outras coisas pesadas no vault, idealmente use links/url para mídias etc.

# Configurações essenciais

## Instalar os Plugins Essenciais:  
   * Vá para Configurações > Community plugins > Browse.  
   * Instale e habilite os seguintes plugins:  
     * Templater: Para gerenciar e inserir seus templates dinâmicos.  
     * Dataview: Para criar as listas e tabelas automáticas.  
     * Tasks: Para agregar todas as suas tarefas (- [ ]).  
     * Spaced Repetition: Para os flashcards de revisão.  
  
 * Configurar o Templater:  
   * Vá para Configurações > Templater.  
   * Template folder location: Aponte para a sua pasta de templates.  
   * Trigger Templater on new file creation: Ative esta opção. Isso é crucial. Garante que, ao criar um novo arquivo, o Templater aplique o template correto automaticamente.  
   * Folder Templates: Configure regras para aplicar templates específicos a pastas específicas. Isso automatiza todo o processo.
        
 * Configurar o Dataview:  
   * Vá para Configurações > Dataview.  
   * Enable JavaScript Queries: Ative esta opção.  
   * Enable Inline JavaScript Queries: Ative esta opção.  
   * Isso garante que todas as queries nos seus templates funcionem corretamente.  
     
 * Configurar o Spaced Repetition:  
   * Vá para Configurações > Spaced Repetition.  
   * Em Flashcard Tags, adicione a tag que você definiu no template, por exemplo, eu defini `#flashcards` para as notas [[99-exercícios-tlp]].
   * Isso diz ao plugin para procurar por flashcards em qualquer nota que contenha essa tag.  
 