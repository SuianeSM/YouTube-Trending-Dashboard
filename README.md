📊 YouTube Trending Dashboard — Análise de Vídeos em Alta
Sobre o Projeto

Este projeto automatiza a análise de vídeos em tendência no YouTube para apoiar decisões de marketing na agência Sterling & Draper. A ideia é simples: parar de responder as mesmas perguntas toda semana e entregar um dashboard interativo que resolve isso em segundos.

🎯 Objetivo Principal

Analisar o histórico de vídeos em alta no YouTube e responder rapidamente:

Quais categorias entram em tendência com mais frequência?

Como essas tendências se distribuem entre países?

Quais categorias se destacam nos Estados Unidos em comparação a outras regiões?

O dashboard é pensado para uso diário por gerentes de planejamento de anúncios.

📌 Dados Utilizados

Fonte: tabela agregada trending_by_time (exportada como CSV).

Campos principais:

record_id — identificador do registro

region — país / região

trending_date — data e hora da tendência

category_title — categoria do vídeo

videos_count — número de vídeos em alta

Atualização dos dados: 1x por dia (UTC).

🧱 Estrutura do Dashboard
Filtros Globais

Filtro de data e hora

Filtro de país

Ambos afetam todos os gráficos e tabelas.

Visualizações

Histórico de Tendências (valores absolutos)

Gráfico de áreas empilhadas

Eixo X: data/hora

Eixo Y: número de vídeos em alta (videos_count)

Quebra por categoria

Histórico de Tendências (% do total)

Gráfico de áreas empilhadas

Mostra a participação percentual das categorias ao longo do tempo

Vídeos em Alta por País

Gráfico de pizza

Mostra a distribuição relativa de vídeos em tendência por região

Vídeos em Alta por País e Categoria

Tabela de destaque (heatmap)

Colunas: países

Linhas: categorias

Valores: número absoluto de vídeos em tendência

🛠️ Ferramenta Utilizada

Tableau

O dashboard foi publicado publicamente e testado em diferentes navegadores para garantir acesso irrestrito.
Link: https://public.tableau.com/views/ProjetoSprint12_17654074880460/Dashboard?:language=pt-BR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

📈 Análises Respondidas com o Dashboard

Categorias mais recorrentes em tendências.

Diferenças claras de consumo entre regiões.

Categorias especialmente populares nos EUA.

Comparação entre preferências dos EUA e de outros países.

Esses insights foram consolidados em uma apresentação curta, com gráficos extraídos diretamente do dashboard.

🚀 Entregáveis

Dashboard interativo no Tableau Public.

Relatório com respostas às perguntas de negócio.

Visual consistente com foco em leitura rápida e decisão.
