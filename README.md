Claro! Aqui está um exemplo de README para o seu projeto de API de viagens, desenvolvido durante o evento NLW da RocketSeat:

---

# API de Viagens

Este projeto foi desenvolvido durante o evento NLW (Next Level Week) da RocketSeat, que aconteceu durante três dias intensivos de aprendizado e desenvolvimento. A API de Viagens permite gerenciar viagens, incluindo destinos, datas de início e fim, e atividades associadas a cada dia da viagem.

## 🚀 Sobre o Evento NLW

O NLW é um evento promovido pela RocketSeat que tem como objetivo proporcionar uma imersão total em desenvolvimento, com conteúdos práticos e desafiadores. Durante os três dias do evento, os participantes são incentivados a construir projetos do zero, aplicando as melhores práticas e tecnologias atuais.

## 📜 Funcionalidades da API

- **Gerenciamento de Viagens**: Criação, leitura, atualização e exclusão de viagens, especificando destino e datas de início e fim.
- **Gerenciamento de Atividades**: Adição de atividades dentro do período da viagem, associando-as a dias específicos entre as datas de início e fim e podendo marcar como completada ou remover a atividade.

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: C#
- **Framework**: .NET
- **Banco de Dados**: SQLite

## 📖 Documentação da API

### Endpoints

- **/Trips**
  - `GET /api/Trips` - Lista todas as viagens
  - `POST /api/Trips` - Cria uma nova viagem
  - `GET /api/Trips/{id}` - Obtém uma viagem pelo ID
  - `DELETE /api/Trips/{id}` - Deleta uma viagem pelo ID
  - `POST /api/Trips/{tripId}/activity` - Cria uma atividade da viagem
  - `PUT /api/Trips/{tripId}/activity/{acitivityId}/complete` - Completa a atividade da viagem
  - `DELETE /api/Trips/{tripId}/activity/{acitivityId}` - Delete a atividade da viagem

## 🛠️ Como Executar o Projeto

1. Clone o repositório:
   ```sh
   git clone https://github.com/michaelfaleiro/JourneyNLW.git
   ```

2. Navegue até o diretório do projeto:
   ```sh
   cd JourneyNLW
   ```

3. Instale as dependências:
   ```sh
   dotnet restore
   ```

4. Execute as migrações para configurar o banco de dados:
   ```sh
   dotnet ef database update
   ```

5. Inicie a aplicação:
   ```sh
   dotnet run
   ```

A aplicação estará disponível em `https://localhost:7098`.

## 📝 Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Espero que isso ajude! Se precisar de mais alguma coisa, estou à disposição.

