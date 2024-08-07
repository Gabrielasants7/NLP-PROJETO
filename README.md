# NLP

Descrição do Projeto
Este projeto implementa diversas tarefas de Processamento de Linguagem Natural (NLP) utilizando modelos Transformer da biblioteca Hugging Face. As tarefas incluem:

Análise de Sentimento 😍😡: Identificação da polaridade de textos.

Classificação de Tópicos 📚: Categoriza textos em classes predefinidas usando aprendizado zero-shot.

Geração de Texto ✍🏽: Predição da próxima palavra em uma sequência textual.

Tradução 🌐: Tradução de textos entre diferentes idiomas


## Índice
       1. Descrição do Projeto
      
       2. Instalação
       
       3. Como Usar

       4. Tarefas de NLP
       
       5. Análise de Sentimentos
       
       6. Classificação de Tópicos
       
       7. Geração de Texto

       8. Tradução

       9. Principais Bibliotecas Utilizadas
       
       10. Modelo Transformers
       
       11. Hugging Face Transformers

       12. Contribuindo
       
       13. Licença
       
       14. Contato


   
## Instalação

Clone o repositório:



```bash
git clone https://github.com/Gabrielasants7/NLP-PROJETO.git
cd NLP-PROJETO

```


## Crie um ambiente virtual 

(Opcional mas recomendado)



```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

```
    
## Instale as dependências




```bash
pip install -r requirements.txt
```


   

## Como Usar

Execução do script principal





```bash
streamlit run app.py
```
    

   > ### Acesse a aplicação no navegador

Após rodar o comando acima, acesse o link fornecido no terminal, normalmente `http://localhost:8501`.  

## Tarefas de NLP

 ### 1. Análise de Sentimento 😍😡

Identifica a polaridade de um texto, determinando se a opinião expressa é positiva, negativa ou neutra.

![Captura de tela 2024-08-06 214627](https://github.com/user-attachments/assets/99e3f0b8-54c4-4bf3-8aa7-0e7f4a08b746)



### 2. Classificação de Tópicos 📚

Categoriza sequências em classes predefinidas utilizando "classificação zero-shot". O Zero-Shot Learning (ZSL) permite classificar textos em categorias que não foram vistas durante o treinamento.

![Captura de tela 2024-08-06 214958](https://github.com/user-attachments/assets/0db5a9be-d8a6-4750-a1ef-966bc087cfa4)



### 3. Geração de Texto ✍🏽

Prevê a próxima palavra em uma frase com base no contexto anterior. Avaliada por métricas como perda de entropia cruzada e perplexidade. Utiliza o modelo GPT-2.


![Captura de tela 2024-08-06 215342](https://github.com/user-attachments/assets/4272f35d-7e0e-4df7-aa32-7f43123ee6ab)




