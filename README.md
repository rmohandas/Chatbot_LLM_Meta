💬 Chatbot_LLM_Meta
Chatbot Médico com Agendamento Inteligente

Este projeto implementa um chatbot médico com inteligência artificial, desenvolvido para agendar consultas automaticamente com base nas mensagens do usuário. A IA entende a especialidade médica desejada, oferece datas disponíveis e finaliza o agendamento, tudo via uma interface conversacional amigável.

🚀 Tecnologias Utilizadas
Camada	Tecnologia
Frontend	ReactJS, Tailwind CSS, Lucide Icons
Backend	Spring Boot, Spring AI, Eureka
IA	Modelo open source da Meta (LLM)
Mensageria	Apache Kafka
Bancos de Dados	MongoDB (contexto/chat), PostgreSQL (agendamentos)

💡 Funcionalidades
🤖 Chatbot com avatar personalizado (Zé do Caixão)

🧠 Interpretação de mensagens com LLM

📅 Agendamento automático de consultas

🗂 Histórico de conversas com status (digitando, enviado, erro)

📤 Integração com backend via API moderna

🔁 Escalável e preparado para microsserviços

📁 Estrutura do Projeto (resumida)
bash
Copiar
Editar
Chatbot_LLM_Meta/
├── frontend/                  # React app (interface do chatbot)
│   └── src/
│       └── components/
│       └── views/
├── backend/                   # Spring Boot app
│   └── src/
│       └── main/java/
│       └── resources/
├── docs/                      # Documentação e diagramas
├── docker/                    # Arquivos Docker e compose (futuro)
└── README.md
⚙️ Como Executar
Pré-requisitos:
Node.js e npm

Java 17+

Docker e Docker Compose (opcional)

MongoDB e PostgreSQL

Frontend:
bash
Copiar
Editar
cd frontend
npm install
npm run dev
Backend:
bash
Copiar
Editar
cd backend
./mvnw spring-boot:run
📌 Status do Projeto
🚧 Em desenvolvimento ativo
📆 Funcionalidade de confirmação de agendamento em testes
💬 Integração com modelo Meta finalizada
