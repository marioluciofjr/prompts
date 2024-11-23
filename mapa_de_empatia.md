# Prompt para gerar um mapa de empatia da persona de uma empresa

As definições do conceitos foram extraídas destes dois textos: 

+ [Mapa da empatia: o que é e 6 passos para criar um de qualidade](https://www.rdstation.com/blog/marketing/mapa-da-empatia/)
+ [Descubra o que é buyer persona e confira o guia completo para criar as suas](https://rockcontent.com/br/blog/personas/)

## Prompt

```
<definições>
## MAPA DE EMPATIA

### O que pensa e sente? 
+ Como a persona se sente em relação ao mundo?
+ Quais as suas preocupações?
+ Quais são os seus sonhos? 

## O que ouve?
+ Quais pessoas e ideias influenciam a persona?
+ Quais são suas marcas favoritas?
+ Quais produtos de comunicação consome?

### O que vê?
+ Como é o mundo em que a persona vive?
+ Como são seus amigos?
+ O que é mais comum no seu cotidiano?

### O que fala e faz?
+ Sobre o que sua persona costuma falar?
+ Ao mesmo tempo, como age?
+ Quais são seus hobbies?

### Quais são as dores?
+ Do que sua persona tem medo?
+ Quais são as suas frustrações?
+ Que obstáculos precisa ultrapassar para conseguir o que deseja?

### Quais são as suas necessidades?
+ O que é sucesso para sua persona?
+ Onde a persona quer chegar?
+ O que acabaria com seus problemas?
---

## PERSONA

Uma persona é um perfil semifictício criado para representar um segmento significativo do cliente ideal de uma empresa, baseado em pesquisa e dados reais sobre seus clientes potenciais, abrangendo demografia, comportamento e necessidades. Ela também é conhecida como buyer persona ou avatar. A persona orienta a criação de conteúdo e o Marketing Digital.
</definições>

<contexto>
{COLOQUE AQUI TODAS AS INFORMAÇÕES MAIS RELEVANTES SOBRE A SUA EMPRESA E/OU SOLUÇÕES QUE OFERECE}
</contexto>

<tarefa>
1. Com base no <contexto></contexto>, defina uma persona com as seguintes variáveis: nome, idade, o que pensa e sente, o que ouve, o que vê, o que fala e faz, quais são as dores e quais são as necessidades. Obedeça exclusivamente o formato de saída: 

+ nome: ${nome}
+ idade: ${idade}
+ pensa e sente: ${pensa-e-sente}
+ ouve: ${ouve}
+ vê: ${vê}
+ fala e faz: ${fala-e-faz}
+ dores: ${dores}
+ necessidades: ${necessidades}

2. Justifique criticamente passo a passo a sua escolha de persona com base no contexto da empresa.
</tarefa>
```
