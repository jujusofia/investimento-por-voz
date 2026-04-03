Voice Invest Assistant

Assistente de investimentos por voz que simula aplicações financeiras usando dados reais e fornece explicações automáticas.

Descrição

Este projeto é um agente financeiro inteligente que permite ao usuário falar com o sistema para simular investimentos.

O fluxo funciona da seguinte forma:

O usuário fala uma pergunta (ex: "Quero investir 1000 reais por 1 ano")
O sistema converte o áudio em texto
Interpreta os dados (valor, tempo, aportes)
Busca taxas atualizadas como CDI e Selic via API do Banco Central
Calcula a evolução do investimento
Exibe um gráfico com o crescimento
Gera uma explicação simples do resultado
Responde também em áudio
Funcionalidades
Entrada por voz
Transcrição automática de áudio
Interpretação de linguagem natural
Simulação de investimentos
Uso de dados reais (CDI e Selic)
Geração de gráficos
Explicação automática (com ou sem IA)
Resposta em áudio
Tecnologias utilizadas
Python
Whisper (transcrição de voz)
gTTS (texto para voz)
Matplotlib (gráficos)
Requests (API Banco Central)
OpenAI (opcional para explicações)
Como executar
1. Instalar dependências
pip install openai-whisper gTTS requests matplotlib openai
2. Executar o projeto

Abra no Google Colab ou ambiente local e execute o código principal.

Configuração opcional de IA

No código existe a variável:

USAR_IA = False

Se quiser usar explicações com IA:

Altere para True
Insira sua chave da OpenAI

Caso contrário, o sistema funciona normalmente em modo gratuito.

Exemplo de uso

Entrada por voz:

"Quero investir 2000 reais por 2 anos com 100 por mês"

Saída:

Gráfico de crescimento
Comparação entre CDI e Selic
Explicação simples do melhor investimento
Resposta em áudio
Estrutura do projeto
Captura de áudio
Processamento de linguagem
Coleta de dados econômicos
Simulação financeira
Geração de resposta
Possíveis melhorias
Interface web (Streamlit ou Flask)
Aplicativo mobile
Suporte a mais tipos de investimento
Perfil de investidor
Histórico de simulações
Licença

Este projeto é de uso educacional e pode ser adaptado livremente.

Autor: Juliana Oliveira

Desenvolvido como projeto de estudo em IA aplicada a finanças.
