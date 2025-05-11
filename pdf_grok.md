# Prompt base para gerar um PDF com cara de artigo científico no Grok da xAI

```
<função>
Você atuará como um pesquisador científico experiente. Sabe a importância de conferir um assunto por meio de várias fontes, a fim de evitar fake news e, consequentemente, a produção de conteúdos com erros.
</função>
<contexto>
A premissa da minha pesquisa é um termo que estava nos assuntos em alta do LinkedIn Notícias: 
"Agenda lotada é produtividade?"
</contexto>
<tarefa>
1. Analise os seguintes posts abaixo:
Post de Bárbara Silva
https://www.linkedin.com/posts/mentorabarbara_a-agenda-lotada-parece-um-s%C3%ADmbolo-de-status-activity-7326576731341901824-O5J3/?utm_source=share&utm_medium=member_desktop&rcm=ACoAACHvXJYBKyTyP1ggw536I9ZWCnCwD7LTax0
Artigo de Rafa Ribeiro
https://www.linkedin.com/pulse/burnout-quando-press%C3%A3o-deixa-de-ser-exce%C3%A7%C3%A3o-e-se-torna-rafa-ribeiro-rryxf/?trackingId=aW0ZuA4hTOK2U9QednOaQA%3D%3D
Post de Mariana de Souza Becker
https://www.linkedin.com/posts/marianadesouzabecker_como-deixar-sua-agenda-menos-sobrecarregada-activity-7325882106067226624-F6EL?utm_source=share&utm_medium=member_desktop&rcm=ACoAACHvXJYBKyTyP1ggw536I9ZWCnCwD7LTax0
Post de Karina Ikeda
https://www.linkedin.com/posts/karinaikedacoach_gestaetoeficiente-lideranaexaconsciente-empresaerriasdesucesso-activity-7325836881689030658-fNiB/?utm_source=share&utm_medium=member_desktop&rcm=ACoAACHvXJYBKyTyP1ggw536I9ZWCnCwD7LTax0
Post de Dra. Adriana Pereira
https://www.linkedin.com/posts/dra-adriana-pereira-a5069b22a_voc%C3%AA-ainda-acredita-que-agenda-cheia-%C3%A9-sin%C3%B4nimo-activity-7325457988889022464-q2nR/?utm_source=share&utm_medium=member_desktop&rcm=ACoAACHvXJYBKyTyP1ggw536I9ZWCnCwD7LTax0
2. Gere um artigo a partir da análise da etapa 1, cujo formato de saída terá **OBRIGATORIAMENTE** a seguinte estrutura: 
Título: Crie um título de até 60 caracteres.
Autor(es): Coloque o nome xAI.
Resumo: Apresente um resumo conciso do estudo, destacando os objetivos, metodologia, principais resultados e conclusões. Terá até 200 palavras.
Palavras-chave: Coloque aqui 5 palavras-chave que tenham a ver com a pesquisa.
Introdução: Contextualize o tema, apresente a problemática, justifique a relevância do estudo e estabeleça os objetivos da pesquisa. Inclua uma breve revisão da literatura para situar o leitor no estado atual do conhecimento sobre o assunto. Terá até 300 palavras.
Metodologia: Descreva detalhadamente os procedimentos adotados na pesquisa, incluindo o tipo de estudo, métodos de coleta e análise de dados, instrumentos utilizados e aspectos éticos considerados. A clareza nessa seção é fundamental para permitir a replicação do estudo por outros pesquisadores. Terá até 200 palavras.
Resultados: Apresente os dados obtidos de forma objetiva, utilizando tabelas, gráficos e figuras para facilitar a compreensão. Evite interpretações ou discussões nesta seção; concentre-se na exposição dos achados. 
Discussão: Interprete os resultados, relacionando-os com a literatura existente. Analise as implicações dos achados, reconheça as limitações do estudo e sugira direções para pesquisas futuras. 
Conclusão: Resuma os principais resultados e destaque a contribuição do estudo para a área de conhecimento. Evite introduzir novas informações nesta seção. Terá até 200 palavras.
Referências: Liste **todos os links** e demais referências utilizadas para este artigo seguindo o padrão de formatação da ABNT. 
3. Em seguida, reflita sobre o que você gerou e revise minuciosamente para conferir se está tudo de acordo. Mantenha um rigor crítico científico e jornalístico sobre a pesquisa.
4. Exporte o resultado do artigo realizado na etapa 2 como um PDF. Inclua um Índice dentro do PDF para facilitar a navegação pelo documento.
<regras>
Verifique fontes confiáveis sobre o assunto. Analise criticamente o texto gerado, a fim de questionar a veracidade da abordagem do tema, principalmente levando em conta possíveis dados de pesquisas. 
</regras>
</tarefa>
```


