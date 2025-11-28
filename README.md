# 🚀 TicFlow - Ecossistema Inteligente de Gestão de Chamados

> **Status:** Concluído ✅ | **Backend:** .NET 8 + IA Generativa | **Banco:** SQL Server

Bem-vindo ao repositório de apresentação do **TicFlow**. Este projeto é uma solução completa para modernizar o suporte técnico corporativo, utilizando Inteligência Artificial para triagem e resolução automática de problemas.

🔒 *Nota: Este é um repositório de vitrine. O código-fonte original é privado por motivos de propriedade intelectual.*

---

## 📂 O que você vai encontrar aqui?

Organizamos os materiais de demonstração nas pastas acima:

### 🎥 1. Demonstração Web (`/01-Demonstracao-Web`)
Vídeos mostrando a interface Web utilizada pelos colaboradores para abrir chamados e interagir com a IA via navegador.

### 📱 2. Demonstração Mobile (`/02-Demonstracao-Mobile`)
Vídeos do aplicativo Flutter (Android), demonstrando a experiência nativa, notificações e a facilidade de uso em campo.

### 📄 3. Documentação da API (`/03-Documentacao-Tecnica`)
Um arquivo PDF detalhado explicando a arquitetura do Backend, incluindo:
* **Segurança:** Como funciona o JWT e o reset de senha.
* **Inteligência Artificial:** Como a IA analisa, classifica e sugere soluções (RAG).
* **Atores:** A diferença entre os usuários do sistema.
* **Swagger:** Prints dos endpoints reais utilizados.

---

## 📱 & 💻 Ecossistema Frontend

O TicFlow foi projetado para ser multiplataforma, garantindo acesso rápido tanto para quem está no escritório quanto em campo.

### **Mobile (App do Colaborador)**
Desenvolvido para garantir agilidade na abertura de chamados.
* **Tecnologia:** **Flutter** & **Dart**.
* **Destaques:** Interface nativa e fluida, consumo eficiente da API REST e foco na experiência do usuário (UX).

### **Web (Painel do Colaborador)**
Uma interface leve e acessível de qualquer navegador.
* **Tecnologia:** **HTML5**, **CSS3** e **JavaScript (Vanilla)**.
* **Destaques:** Desempenho otimizado sem a necessidade de frameworks pesados, manipulação direta do DOM e integração via Fetch API.

---

## 🛠️ Resumo Técnico do Backend

O "motor" que faz tudo isso funcionar e conecta os frontends foi construído com tecnologias de ponta:

* **ASP.NET Core 8 Web API:** Alta performance e segurança.
* **Arquitetura em 3 Camadas:** Separação limpa entre API, Domínio e Infraestrutura.
* **Entity Framework Core (Code-First):** Gestão moderna de banco de dados.
* **Integração OpenAI/Gemini:** Serviço customizado para processamento de linguagem natural.
* **Segurança:** Implementação robusta de Autenticação e Autorização (JWT).

---
*Desenvolvido como Trabalho de Conclusão de Curso (TCC).*
