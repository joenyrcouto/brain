---
tipo: moc
tags:
  - moc
  - "#review"
---

## Estrutura Principal (Curadoria Manual)  
*(Aqui você organiza os links para as Notas Permanentes mais importantes de forma lógica, como um sumário de livro. Crie seções, adicione comentários.)*  
  
- **Fundamentos**  
  - [[Link para a nota fundamental 1]]  
  - [[Link para a nota fundamental 2]]  
- **Tópicos Avançados**  
  - [[Link para a nota avançada 1]]  
  
## Todas as Notas Relevantes
  
```example
dataview  
TABLE WITHOUT ID file.link as "Nota", criado_em as "Criado em"  
FROM "30 Permanentes"  
WHERE contains(file.tags, "área/xxx") AND contains(file.tags, "tópico/xxx")  
SORT criado_em ASC
```