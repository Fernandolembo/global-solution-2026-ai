# global-solution-2026-ai

#  Mission Control AI - Global Solution 2026

**Disciplina:** Prompt and Artificial Intelligence  
**Turma:** 1º Ano - Ciência da Computação  
**Integrantes:**
* Fernando Henrique Lembo de Arruda Camargo — RM: 570228
* Ryan Barreto — RM: 574126


---

##  Descrição do Projeto
Este projeto é um sistema de monitoramento inteligente para missões espaciais. Ele simula dados de telemetria (temperatura, energia e comunicação) e utiliza o modelo de linguagem **Llama 3.2 1B** (via Ollama) para analisar situações críticas em tempo real. O sistema possui lógica de decisão autônoma que ativa protocolos de segurança e gera alertas visuais quando parâmetros operacionais saem da normalidade.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **IA Generativa:** Llama 3.2 1B (Ollama)
* **Ambiente:** Google Colab
* **Bibliotecas:** `ollama`, `subprocess`, `random`, `time`

##  Demonstração do Sistema

### Cenário 1: Operação Normal
Aqui o sistema monitora a missão em estado estável.
![Dados da missão](assets/dados_missao.png)

### Cenário 2: Alerta Crítico
Exemplo de quando a IA detecta falha na energia ou superaquecimento.
![Alerta crítico](assets/alerta_critico.png)

---

##  Como Executar
1. Acesse o nosso notebook através do link: 
   [**Abrir no Google Colab**](LINK_DO_SEU_COLAB_AQUI)
2. Certifique-se de executar as células de instalação (zstd e Ollama) no início.
3. Execute o bloco de simulação para ver a IA analisando os dados da missão.

## 📺 Vídeo de Demonstração
Assista à apresentação completa do projeto e funcionamento da IA:  
[**Clique aqui para assistir ao vídeo**](LINK_DO_SEU_VIDEO_AQUI)
