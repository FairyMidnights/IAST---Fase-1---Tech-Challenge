Link Repositório Git: https://github.com/FairyMidnights/IAST---Fase-1---Tech-Challenge/settings

------------------------
* Objetivo do Projeto *
------------------------
Este projeto tem como objetivo identificar os principais fatores que impactam a satisfação dos clientes de um e-commerce, utilizando o NPS (Net Promoter Score) como indicador principal de experiência.

A análise busca responder à seguinte pergunta de negócio:

- Quais fatores da jornada do cliente estão mais associados à insatisfação ?
- Quais fatores da jornada do cliente estão mais associados à redução da recompra ?
- Quais ações devem ser priorizadas para melhorar a experiência do cliente?

Além de avaliar os fatores individuais, o projeto investiga combinações de eventos críticos (atrasos, reclamações e contatos com o suporte) para identificar os pontos de ruptura da jornada do cliente.

Descrição da Base de Dados
A base contém informações de 2.500 pedidos e 19 variáveis relacionadas ao perfil dos clientes, comportamento de compra, operação logística, atendimento e satisfação.

-------------------------
* Metodologia Utilizada *
-------------------------

1. Análise Exploratória dos Dados (EDA)

Foi realizada uma avaliação inicial da base para compreender:

- Distribuição das variáveis;
- Qualidade dos dados;
- Comportamento do NPS;
- Perfil dos clientes;
- Frequência de recompra.

2. Identificação dos Fatores de Impacto

Foi analisada a relação entre as variáveis operacionais e o NPS para identificar quais fatores possuem maior associação com a satisfação dos clientes.

Os principais fatores identificados foram:

- Atraso na entrega;
- Quantidade de reclamações;
- Quantidade de contatos com o suporte;
- Tempo de resolução de problemas.

3. Análise dos Pontos de Ruptura

Além da análise individual dos fatores, foi realizada uma investigação das combinações de eventos que mais deterioram a experiência do cliente.

Foram definidas três condições de risco:

- Atraso relevante na entrega;
- Múltiplos contatos com o atendimento;
- Alto número de reclamações.
Link Repositório: https://github.com/FairyMidnights/IAST---Fase-1---Tech-Challenge/settings

A partir dessas condições, foram criados grupos representando diferentes jornadas do cliente.

Exemplos:

Código	|Significado
----------------------------------------------------
000	| Sem fatores de risco
100	| Apenas atraso
001	| Apenas reclamações
101	| Atraso + reclamações
111	| Atraso + reclamações + múltiplos contatos


Essa análise permitiu identificar as jornadas mais críticas para o negócio.

Principais Resultados:

Fatores mais associados à insatisfação
- Atraso na entrega
- Reclamações registradas
- Necessidade de múltiplos contatos com o suporte
- Tempo de resolução

Principal descoberta
- O atraso logístico mostrou-se o principal gatilho de insatisfação.

- Quando o atraso evolui para reclamações e necessidade de múltiplos contatos com o suporte, ocorre uma forte queda no NPS e praticamente desaparece a probabilidade de recompra.

Jornada mais crítica

A combinação: Atraso + Reclamações + Múltiplos Contatos