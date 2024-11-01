# Imersão Alura ao Google Gemini

### Módulo 2 - Engenharia de Prompt

#### Definição
Engenharia de prompt é  saber conversar com inteligências artificiais(IA). Saber formula instruções, perguntas para ter o melhor resultado possivel da pergunta realizada, para a IA seja ela Google Gemini, ChatGPT dentre outras.

<strong> Camadas do Gemini </strong>
- Engenhária de Prompt
- Parametros de Execução
- Configurações de Segurança
- Redução Intriseca do modelo para informações inventadas ou alucinadas

#### Acessando o Google IA Studio.
 - Necessário ter uma conta no Google;
 - Link: https://aistudio.google.com/app/prompts/new_chat;
 - Conforme a imagem a seguir, selecione a "Create New Prompt",
 - Ao lado direito da tela, clique em "Model" e selecione a versão da IA, que deseja utilizar.
   
   ![image](https://github.com/user-attachments/assets/7083303c-c746-4110-8a52-937faeb825c2)



### Módulo 3 - Explorando parametros do Google IA Studio
Dentro do Google IA Studio  existem dois tipos de prompts:
- Chatprompt: Projetado para executar tarefas bem definidas.
- Freedom Chat: Voltado para conversas abertas e espontâneas. Ele é como um amigo virtual com quem você pode conversar sobre qualquer assunto.

#### Temperautra: 
![image](https://github.com/user-attachments/assets/eae18576-80bb-4ecb-8dc8-834bea5c4aa2)
<p> Forma com que a resposta será retornada, no prompt de dialogo com a IA. </p> 


#### Safety Setings
![image](https://github.com/user-attachments/assets/f3af8701-242c-4d57-aa78-ca3b54a2abff)
<p>Controle de respostas, contra ódio e afins.</p>

#### Advanced Settings | TOP K
![image](https://github.com/user-attachments/assets/ae72d4fd-61dd-40b0-8066-f759cf31d732)
<p>Controle de respostas do tipo de palavras usadas em respostas de maneira resumida. Exemplo: Mas/Porém/Contudo e afins e quero contar apenas com 2.</p>

#### Advanced Settings | TOP B
<p>Define a probabilidade agregada, ou seja, 20% então o modelo irá escolher a soma de palavras que chegue nesse 20% setados(1 palavra 15%/2 palavra 4%/3 palavra 1 %).</p>

#### Trabalhando com imagem, video, audio ou arquivo
<p> Para trabalhar com imagem, video, audio ou arquivo basta selecionar a opção deseja conforme imagem a seguir e fazer a pergunta para a IA.</p>

![image](https://github.com/user-attachments/assets/3e7f0154-94ab-4e83-922c-3e6173e7c318)

#### Criando a API Key
- Clique em  Get API Key;
- Clique em Create API Key;

  ![image](https://github.com/user-attachments/assets/7ead1a9c-f92f-42a1-a44a-f527b4881237)

### Módulo 4 - Criando seu próprio seu Chatbot com o Gemini API

<p> Documentação: https://ai.google.dev/gemini-api/docs/quickstart?hl=pt-br&lang=python </p>

<p>Código anexado no resposittório</p>
