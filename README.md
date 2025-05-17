# Assistente Virtual para Cuidados com Bebê e Agendamento de Vacinas

Este projeto é um assistente virtual desenvolvido para oferecer suporte a pais e responsáveis por bebês, fornecendo informações sobre cuidados com bebês, agendamentos de vacinas, e também oferecendo frases motivacionais. O assistente também permite agendar vacinas diretamente no Google Calendar e interagir com o usuário por meio de chat.

## Funcionalidades

- **Informações sobre cuidados com bebês**: Fornece dicas de cuidados com bebês com base na idade do bebê (sono, alimentação, brincadeiras, vacinas, etc.).
- **Agendamento de vacinas**: Permite ao usuário agendar vacinas recomendadas para a idade do bebê no Google Calendar.
- **Frases motivacionais**: O assistente oferece frases motivacionais para os pais ou responsáveis.
- **Chat de apoio**: O assistente oferece um chat interativo onde os pais podem tirar dúvidas ou desabafar.
- **Opções de ajuda**: O assistente oferece três opções de ajuda no início da interação:
  1. Chamada de vídeo com especialista online.
  2. Catálogos de Ebook.
  3. Tirar dúvida e desabafar.

## Pré-requisitos

Antes de rodar o código, certifique-se de que você tenha as seguintes bibliotecas instaladas:

- `google-auth`
- `google-api-python-client`
- `google-auth-httplib2`
- `google-auth-oauthlib`
- `pandas`
- `google.colab`

Você pode instalar as bibliotecas necessárias com o seguinte comando:

```bash
pip install --upgrade google-auth-oauthlib
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
pip install pandas
Como usar
Clone o repositório:
Clone este repositório para o seu ambiente local ou para o Google Colab.

bash
Copiar
Editar
git clone https://github.com/seu-usuario/assistente-virtual-bebe.git
cd assistente-virtual-bebe
Autenticação do Google Calendar:
O código usa a API do Google Calendar para agendar eventos. Para usar, é necessário autenticar o acesso à sua conta do Google e fornecer um token de autenticação. O código irá guiá-lo durante o processo de autenticação automaticamente.

Executando o Assistente Virtual:
Após a configuração, execute o script para iniciar o assistente virtual:

python
Copiar
Editar
assistente_virtual()
Interaja com o Assistente:
O assistente irá oferecer opções de ajuda logo no início:

1: Chamada de vídeo com especialista online.

2: Catálogos de Ebook.

3: Tirar dúvida e desabafar (inicia uma interação de chat).

Contribuindo
Sinta-se à vontade para contribuir com melhorias no código! Para contribuir:

Faça um fork do repositório.

Crie uma branch para a sua funcionalidade (git checkout -b minha-nova-funcionalidade).

Faça suas alterações e envie um pull request.

Licença
Este projeto é licenciado sob a MIT License.

Contato
Se você tiver dúvidas ou sugestões, entre em contato comigo:

E-mail: caroline.zep@gmail.com

GitHub: https://github.com/carolinezep

