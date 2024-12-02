De acordo com o livro "Prompts em Ação - Engenharia de Prompts Para Leigos", do Sandeco Macedo, uma pessoa pode criar, adaptar, simplificar ou amplificar um prompt. Só que é preciso levar em consideração fatores como objetivo, contexto, linguagem, ética, vieses, entre outros pontos.

Com base no 'prompt depurador', presente no livro, eu criei esse verificador de prompts de imagem:


```
<prompt>
{COLOQUE AQUI O SEU PROMPT INICIAL}
</prompt>

<tarefa>
1. Liste um passo a passo de 5 ações que um modelo generativo de textos deve realizar ao executar o prompt delimitado pelas tags <prompt></prompt>.

2. Liste 5 categorias de solicitação, que são importantes para o modelo generativo construir um resultado que mais se aproxima do objetivo, mas que o usuário está esquecendo de informar no prompt delimitado pelas tags <prompt></prompt>.

3. Crie um exemplo de como o prompt ficaria melhor a partir do passo a passo da etapa 1 e as categorias da etapa 2. Apresente esse exemplo em formato de parágrafo em markdown.
</tarefa>

```
