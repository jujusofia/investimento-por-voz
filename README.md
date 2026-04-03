🎙️ Voice Invest Assistant

Assistente de investimentos por voz que simula aplicações financeiras usando dados reais e fornece explicações automáticas.



📌 Sobre o projeto

Este projeto é um agente financeiro inteligente que permite ao usuário realizar simulações de investimento por meio de comandos de voz.

O sistema transforma fala em texto, interpreta os dados financeiros e calcula a evolução do investimento com base em taxas reais como CDI e Selic.



⚙️ Como funciona

1. O usuário fala uma pergunta
   *Exemplo: "Quero investir 1000 reais por 1 ano"*

2. O sistema converte o áudio em texto

3. Interpreta:

   * Valor inicial
   * Aporte mensal
   * Tempo de investimento

4. Busca dados atualizados do Banco Central

5. Calcula o crescimento do investimento

6. Exibe um gráfico com a evolução

7. Gera uma explicação simples do resultado

8. Retorna a resposta em áudio



🚀 Funcionalidades

* Entrada por voz
* Transcrição automática com Whisper
* Interpretação de linguagem natural
* Simulação de investimentos
* Uso de dados reais (CDI e Selic)
* Geração de gráficos
* Explicação automática (modo híbrido: com ou sem IA)
* Resposta em áudio



🛠️ Tecnologias utilizadas

* Python
* Whisper (speech-to-text)
* gTTS (text-to-speech)
* Matplotlib
* Requests
* OpenAI (opcional)



▶️ Como executar

### 1. Instalar dependências

```bash
pip install openai-whisper gTTS requests matplotlib openai
```

### 2. Executar o projeto

* Abra no Google Colab ou ambiente local
* Execute o script principal



🧠 Modo híbrido (com ou sem IA)

O projeto funciona mesmo sem uso de IA paga.

No código:

```python
USAR_IA = False
```

Se quiser usar IA:

* Altere para `True`
* Insira sua chave da OpenAI

Caso contrário, o sistema usa lógica interna para explicar os resultados.



 💡 Exemplo de uso

**Entrada (voz):**
"Quero investir 2000 reais por 2 anos com 100 por mês"

**Saída:**

* Gráfico de crescimento
* Comparação entre CDI e Selic
* Explicação do melhor resultado
* Resposta em áudio



📁 Estrutura do projeto

* Captura de áudio
* Transcrição
* Processamento de texto
* Coleta de dados econômicos
* Simulação financeira
* Geração de resposta


 🔮 Melhorias futuras

* Interface web (Streamlit)
* Aplicativo mobile
* Suporte a mais investimentos (CDB, IPCA, etc.)
* Perfil de investidor
* Histórico de simulações



 📄 Licença

Este projeto é de uso educacional e pode ser modificado livremente.


 👨‍💻 Autor

Juliana Oliveira
