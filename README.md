# NLP

Descrição do Projeto
Este projeto implementa diversas tarefas de Processamento de Linguagem Natural (NLP) utilizando modelos Transformer da biblioteca Hugging Face. As tarefas incluem:

Análise de Sentimento 😍😡: Identificação da polaridade de textos.


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





### 2. Geração de Texto ✍🏽

Prevê a próxima palavra em uma frase com base no contexto anterior. Avaliada por métricas como perda de entropia cruzada e perplexidade. Utiliza o modelo GPT-2.


![Captura de tela 2024-08-06 215342](https://github.com/user-attachments/assets/4272f35d-7e0e-4df7-aa32-7f43123ee6ab)



### 3. Tradução 🌐

Converte texto de um idioma para outro. A qualidade é avaliada pela métrica BLEU. Pode utilizar modelos monolíngues ou multilíngues.


![Captura de tela 2024-08-06 220014](https://github.com/user-attachments/assets/7380b2f1-3f3b-47a6-9836-dbb3b6141918)



### Principais Bibliotecas Utilizadas


-   `transformers`: Implementação de modelos Transformer.
  
-   `streamlit`: Construção da interface do usuário.

-   `torch`: Operações com tensores e execução de modelos.


###  Modelo Transformer 

 > Modelos que utilizam mecanismos de atenção para processar dados sequencialmente, sendo eficazes em tarefas de NLP.

### Hugging Face Transformers 

> Biblioteca que oferece implementações de modelos de ponta como BERT, GPT-2 e T5, facilitando a aplicação de modelos Transformer.




### Contribuições são sempre bem-vindas! Siga as etapas abaixo:

  

 1. Faça um fork do projeto.
    
 2.  Crie um branch para sua funcionalidade (git checkout -b
    minha-nova-funcionalidade).
    
 3.   Commit suas alterações (git commit -am 'Adiciona nova
    funcionalidade').
    
 4.   Envie seu branch (git push origin minha-nova-funcionalidade).
    
  5.  Abra um Pull Request.


### Licença
Este projeto está licenciado sob os termos da licença MIT. 


### Contato
Para mais informações ou perguntas, entre em contato:

Nome: Gabriela Santana 

Email: gabriellareboucas6@gmail.com 

LinkedIn: https://www.linkedin.com/in/gabriela-santana-801602201/


GitHub: Gabrielasants7
