# ClínicaMed

Sistema completo para agendamento e gestão de consultas médicas, com integração de APIs externas e autenticação segura.

## Tecnologias Utilizadas

- **Backend:** Node.js, Express, Sequelize (Postgres ou SQLite), JWT, Axios
- **Frontend:** Vue.js 3, Vite, Axios
- **APIs externas:** ViaCEP, OpenWeatherMap

## Instruções de Uso

### 1. Clonar o repositório

```sh
git clone <URL_DO_REPOSITORIO>
cd clinicamed


2. Instalar dependências

Backend

cd backend
npm install

Frontend


cd ../frontend
npm install


3. Configurar variáveis de ambiente

No backend, crie um arquivo .env com:

PORT=3001
JWT_SECRET=seu_segredo_jwt
DATABASE_URL=postgres://usuario:senha@host:porta/database
OPENWEATHER_API_KEY=sua_chave_openweather

4. Rodar o backend

cd backend
npm start

5. Rodar o frontend

cd frontend
npm run dev

6. Acessar o sistema

Frontend: http://localhost:5173
Backend: http://localhost:3001

Links de Deploy


