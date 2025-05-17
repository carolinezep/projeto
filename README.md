
markdown
Copiar
Editar
# Assistente Virtual para Pais e Mães de Bebês

Este projeto é um assistente virtual desenvolvido para fornecer apoio a pais e mães de bebês. Ele oferece informações sobre cuidados com bebês, agendamentos de vacinas e interação direta com um chat para tirar dúvidas ou desabafar.

## Minha Experiência como Mãe

Como mãe de duas meninas, **sei que ter uma rede de apoio para tirar dúvidas torna a maternidade mais tranquila**. Com minha segunda filha, o conhecimento prévio sobre a maternidade **me deu mais tranquilidade e me permitiu aproveitar mais cada momento**.

Este é uma **versão inicial do projeto**, e espero que ele seja útil para muitas famílias!

## Funcionalidades

- **Informações sobre cuidados com bebês**: Oferece orientações sobre sono, alimentação, brincadeiras, vacinas e desenvolvimento do bebê com base na idade.
- **Agendamento de vacinas**: Permite ao usuário agendar vacinas recomendadas para o bebê diretamente no Google Calendar.
- **Frases motivacionais**: O assistente oferece frases motivacionais para os pais ou responsáveis.
- **Chat de apoio**: Permite que o usuário tire dúvidas ou desabafe diretamente com o assistente.
- **Opções de ajuda**: O assistente oferece três opções no início da interação:
  1. Chamada de vídeo com especialista online.
  2. Catálogos de Ebook.
  3. Tirar dúvida e desabafar (inicia uma interação de chat).

## Como configurar o ambiente

### Pré-requisitos

Antes de rodar o código, é necessário instalar algumas bibliotecas. Execute os seguintes comandos:

```bash
pip install google-genai
pip install --upgrade google-generativeai
pip install google-auth-oauthlib
pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib
pip install pandas
```

### Configuração do Google API

Este assistente virtual usa a API do Google Calendar para agendar eventos. Para isso, é necessário configurar as credenciais do Google.

1. Acesse o Google Cloud Console e crie um novo projeto.

2. Habilite a API do Google Calendar.

3. Crie credenciais de tipo OAuth 2.0 Client ID e baixe o arquivo JSON das credenciais.

4. Carregue o arquivo de credenciais no Colab ou ambiente de execução.

### Configuração do Colab

No Google Colab, execute o seguinte código para configurar as credenciais:

```bash
from google.colab import userdata
os.environ['GOOGLE_API_KEY_1'] = userdata.get('GOOGLE_API_KEY_1')
os.environ['cliente_id'] = userdata.get('cliente_id')

```
Este código configura a chave de API para a autenticação necessária para interagir com o Gemini e Google Calendar 

Como usar
Clone o repositório:
Clone este repositório para o seu ambiente local ou para o Google Colab.

```bash

git clone https://github.com/carolinezep/projeto.git
cd assistente-virtual-bebe
```
Executando o Assistente Virtual:
Após a configuração, execute o script para iniciar o assistente virtual.

```bash
assistente_virtual()
```
## Interação com o assistente:
O assistente fornecerá três opções iniciais:
1. Chamada de vídeo com especialista online.
2. Catálogos de Ebook.
3. Tirar dúvida e desabafar (inicia uma interação de chat).
4. Agendamento de vacinas:
Se o assistente detectar que há vacinas recomendadas para a idade do bebê, ele perguntará se o usuário deseja agendar no Google Calendar.

## Contribuindo
Sinta-se à vontade para contribuir com melhorias no código! Para contribuir:

Faça um fork do repositório.

Crie uma branch para a sua funcionalidade (git checkout -b minha-nova-funcionalidade).

Faça suas alterações e envie um pull request.

Licença
Este projeto é licenciado sob a MIT License.

*Contato*

Se você tiver dúvidas ou sugestões, entre em contato comigo:

E-mail: caroline.zep@gmail.com

GitHub: https://github.com/carolinezep



