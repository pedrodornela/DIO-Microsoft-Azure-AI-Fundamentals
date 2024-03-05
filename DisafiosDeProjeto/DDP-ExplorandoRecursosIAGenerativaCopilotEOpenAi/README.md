<h1>
<a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/87d332d0-5198-4a2f-b159-38c8c2976954.png">
</a>
Trabalhando com Machine Learning - Explorando os Recursos de IA Generativa com Copilot
</h1>

## [Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html) utilizada para a criação do passo a passo a seguir e demais ***insights***. 

### A prática deste Desafio ajudou a ter uma noção do quão prático as ferramentas de IAs Generativas estão se tornando, com seus diversos usos e aplicações.

## Passo a passo:

## Faça login no Microsoft Copilot

- Abra [copilot.microsoft.com](https://copilot.microsoft.com/?azure-portal=true) e entre com sua conta pessoal da Microsoft. 

- Na parte inferior da tela, você verá uma janela **Pergunte-me qualquer coisa** . À medida que você insere prompts na janela, o Copilot usa todo o thread da conversa para retornar respostas.

## Utilizando prompts para gerar respostas

- Digite o prompt: 

        1 - What are 3 pros and cons of traveling in the winter? - Quais são os pros e contras de viajar no inverno?

        2 - Find me 3 more pros - Me traga mais 3 pros.

        3 - Where are 3 places I can go to find fewer crowds? - Quais são os lugares onde posso encontrar menos multidões.

    ![imagem pesquisa](/DisafiosDeProjeto/DDP-ExplorandoRecursosIAGenerativaCopilotEOpenAi/output/imagem_pesquisa.png)

- Você verá Searching for:… e Generating… aparecer antes da resposta.

- Veja que o Copilot **"Guarda em memória temporária"** o último prompt, podendo assim deixar que o usuário gere mais prompts que estejam relacionados com os anteriores, como os exemplos 1 e 2. 

- Observe que o final das respostas contém links das fontes.


## Utilizando prompts para gerar imagens

- Digite o prompt:

        Create an image of an elephant eating a hamburger. - Crie uma imagem de um elefante comendo um haburguer.

    ![imagem elefante](/DisafiosDeProjeto/DDP-ExplorandoRecursosIAGenerativaCopilotEOpenAi/output/imagem_pesquisa.png)
        
    Observe que uma mensagem que tentarei criar que… aparece antes que o Copilot retorne uma resposta.

    É importante notar que a resposta pode parecer semelhante, mas não igual. Isso ocorre porque as respostas são variadas.

- Na resposta, há um texto na parte inferior que diz “Powered by DALL-E”. Considere como o DALL-E é baseado em grandes modelos de linguagem, à medida que sua entrada de linguagem natural gera imagens.

- Retorne ao chat do Copilot clicando no ícone do Microsoft Bing no canto superior direito da tela.


## Utilizando prompts para gerar código

-  Digite o prompt: 

        Use Python to create a list. - Use o Python para criar uma lista.

    ![codigo python](/DisafiosDeProjeto/DDP-ExplorandoRecursosIAGenerativaCopilotEOpenAi/output/codigo_python.png)

- Digite o prompt: 
        Translate that into C#. - Traduza aquilo para C#.

    ![codigo traduzido para c#](/DisafiosDeProjeto/DDP-ExplorandoRecursosIAGenerativaCopilotEOpenAi/output/objeto_c_sharp.png)

Observe como você não precisou especificar o que é “aquilo”, como o Copilot sabe para se referir ao histórico de conversas.


## Outros exemplo de prompts e suas respectivas respostas (textos, imagens, códigos):

### Exemplo 1:
- Input:

        Me traga 10 valores da sequência de fibonacci.

- Output:
![Me traga 10 valores da sequência de fibonacci](/DisafiosDeProjeto/DDP-ExplorandoRecursosIAGenerativaCopilotEOpenAi/output/fibonacci.png)

### Exemplo 2:

- Inputs:

        - Crie uma imagem de 1 artista marcial de kung fu do futuro, mantendo as características das roupas padrões.

        - Faça o artista marcial lutando com o robocop


- Outputs:
![artista marcial](/DisafiosDeProjeto/DDP-ExplorandoRecursosIAGenerativaCopilotEOpenAi/output/artista_marcial.png)

    ![artista marcial e robocop](/DisafiosDeProjeto/DDP-ExplorandoRecursosIAGenerativaCopilotEOpenAi/output/artista_marcial_e_robocop.png)


### Exemplo 3:

- Input:

        - Crie um objeto em C#, que contenha os atributos Id, Nome, SobreNome, Idade, Sexo.

        - Traduza este código para Python.


- Outputs:
![objeto c#](/DisafiosDeProjeto/DDP-ExplorandoRecursosIAGenerativaCopilotEOpenAi/output/objeto_c_sharp.png)

    ![objeto Python](/DisafiosDeProjeto/DDP-ExplorandoRecursosIAGenerativaCopilotEOpenAi/output/objetoPython.png)