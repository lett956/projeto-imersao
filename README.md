# Tutor Virtual Personalizado

O Tutor Virtual Personalizado é um programa de inteligência artificial (IA) desenvolvido para auxiliar alunos em suas jornadas de aprendizado. Ele oferece funcionalidades como avaliação de conhecimentos prévios, criação de planos de aprendizado e resposta a dúvidas.

## Requisitos

Para executar o programa, você precisa instalar a biblioteca `google-generativeai`. Você pode instalar os requisitos executando o seguinte comando:

!pip install -q -U google-generativeai


## Configuração

Antes de utilizar o Tutor Virtual Personalizado, é necessário configurar a chave de API para acessar os serviços de geração de texto da Google. A chave de API deve ser fornecida no formato de uma variável de ambiente chamada `SECRET_KEY`.

## Funcionalidades

### 1. Avaliar Conhecimentos

Esta funcionalidade permite que o aluno avalie seus conhecimentos prévios em um determinado assunto. O programa gera perguntas sobre o assunto especificado e solicita respostas ao usuário. Em seguida, verifica as respostas fornecidas pelo usuário e fornece feedback sobre a precisão das respostas.

### 2. Criar Plano de Aprendizado

Com esta funcionalidade, o aluno pode solicitar a criação de um plano de aprendizado para um determinado conteúdo. O programa utiliza inteligência artificial para gerar um plano de estudos personalizado, levando em consideração o conteúdo especificado pelo usuário.

### 3. Responder Dúvidas

O Tutor Virtual Personalizado também permite que o aluno faça perguntas e receba respostas sobre qualquer assunto. O programa utiliza inteligência artificial para compreender a pergunta do aluno e fornecer uma resposta apropriada.

## Uso

Após configurar a chave de API e instalar as dependências necessárias, você pode executar o programa chamando a função `menu()`. Isso iniciará o menu principal, onde o usuário pode selecionar uma das opções disponíveis.
