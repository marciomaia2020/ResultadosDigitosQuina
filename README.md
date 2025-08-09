# ResultadosDigitosQuina

Principais Adaptações:
1. Cores da Quina:
Roxo primário: #260184 (como você especificou)
Roxo secundário: #1a0560
Modo escuro: #3d0db8
2. APIs da Quina:
API principal: https://servicebus2.caixa.gov.br/portaldeloterias/api/quina
API por concurso: https://servicebus2.caixa.gov.br/portaldeloterias/api/quina/{numero}
API completa: https://loteriascaixa-api.herokuapp.com/api/quina
3. Funcionalidades Específicas:
⚡ Sistema de cache inteligente para carregamento ultra-rápido
📊 Análise de dígitos únicos dos 5 números sorteados da Quina
🔍 Filtros avançados por quantidade de dígitos, dígito específico, range de concursos
📈 Análise de frequência e intervalos entre aparições
📋 Resumo automático com estratégias de aposta baseadas nos dados
💾 Downloads em XLS, HTML e TXT
🌙 Tema escuro/claro automático
🔄 Atualização automática a cada 5 minutos
4. Valores de Referência:
Concurso padrão: 6792 (baseado no JSON fornecido)
Estrutura: Análise dos dígitos únicos presentes nos 5 números sorteados
5. Performance:
Carregamento otimizado com cache
Busca apenas concursos novos quando possível
Fallback para API completa se necessário
Indicadores visuais de progresso
A aplicação está pronta para uso e analisará automaticamente os dígitos únicos presentes nos sorteios da Quina, mantendo o esquema de cores roxo característico desta modalidade! 💜🎰