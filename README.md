# Caring For My Plants

## Introdução
Este projeto Python utiliza o modelo de linguagem grande Gemini e a API do Google Generative AI para fornecer informações sobre cuidados com plantas com base em imagens. O usuário insere o nome de uma imagem de planta, e o programa usa o Gemini para analisar a imagem e oferecer sugestões de cuidados, identificar possíveis problemas e responder a perguntas relacionadas a plantas e flores.

## Configuração
1. Instale as dependências: `pip install -q -U google-generativeai`
1. Obtenha uma chave de API do Google.
1. Cole a chave de API no arquivo de configuração.
1. Monte seu Google Drive no Colab rodando essa célula:

```
from google.colab import drive
drive.mount('/content/gdrive')
```

> Defina o caminho padrão para as imagens em seu Google Drive:

```
defaultPath = '/content/gdrive/MyDrive/Plants/'  # Altere o caminho conforme necessário
```

## Utilização

1. Execute cada célula de código no Google Colab.
2. Siga as instruções para inserir o nome da imagem que deseja analisar.
3. Aguarde a resposta gerada pelo modelo, que incluirá informações sobre o cuidado da planta na imagem.

## Próximos passos
* Implementar suporte para upload de imagens locais.
* Integrar com um banco de dados de plantas para fornecer informações mais detalhadas.
* Adicionar a capacidade de fazer perguntas de acompanhamento e ter uma conversa mais natural com o modelo.

## Autor

Este código foi escrito por **Gabriel Bastos Sandim**.

## Licença

Este projeto é licenciado sob a Licença MIT. Consulte o arquivo LICENSE.md para obter detalhes.

---
