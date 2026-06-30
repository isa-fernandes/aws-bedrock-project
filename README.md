# AWS Bedrock - Exercício 1

Visualização do resultado: [abrir `output.mp4`](output.mp4)

Este repositório reúne notebooks de estudo com exemplos práticos de uso do AWS Bedrock para geração de texto e vídeo.

## Conteúdo

- `genai-exercise1-text1.ipynb`: primeiro exemplo de geração de texto.
- `genai-exercise1-text2.ipynb`: segundo exemplo de geração de texto com streaming/resposta incremental.
- `genai-exercise1-video.ipynb`: exemplo de geração de vídeo a partir de prompt textual.

## Pré-requisitos

- Python 3.10+.
- `boto3` instalado.
- Credenciais AWS configuradas localmente.
- Permissões adequadas para usar Amazon Bedrock, Amazon S3 e os modelos escolhidos nos notebooks.

## Como usar

1. Abra o projeto no VS Code ou no Jupyter Notebook.
2. Selecione o kernel Python desejado.
3. Execute os notebooks na ordem que fizer sentido para o estudo.
4. Ajuste região, modelo e buckets S3 conforme o seu ambiente AWS.

## Observações

- O notebook de vídeo grava a saída em um bucket S3 configurado no código.
- Antes de executar, confirme se a sua conta tem acesso aos modelos do Bedrock usados nos exemplos.
- Arquivos temporários do Jupyter e do VS Code não devem ser versionados.

## Estrutura

```text
.
├── genai-exercise1-text1.ipynb
├── genai-exercise1-text2.ipynb
└── genai-exercise1-video.ipynb
```