# Prompt "RaR com CoT", inspirado no artigo ["Rephrase and Respond: Let Large Language Models Ask Better Questions for Themselves"](https://arxiv.org/html/2311.04205v2)

```
<pergunta>
{COLOQUE AQUI SUA PERGUNTA}
</pergunta>

<tarefa>
Pense passo a passo para resolver cada etapa da tarefa: 

1. Reformule a pergunta para captar um contexto mais abrangente e completo sobre o tema. O título dessa etapa será "Reformulação".
2. Responda detalhadamente a pergunta reformulada da etapa 1. O título dessa etapa será "Resposta".
3. Justifique sua resposta detalhada da etapa 2 com uma lógica didática. O título dessa etapa será "Justificativa".

<regra>
Seu resultado deve conter apenas o que eu solicitei. Caso contrário você sofrerá uma penalidade.
</regra>

<formato>
O formato de saída será em texto com delimitadores, títulos formatados em H1 e subtítulos formatados em H2.
</formato>
</tarefa>
```
