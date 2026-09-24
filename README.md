# 🎲 Ecossistema Taverna Web

> **Plataforma web integrada para gerenciamento e imersão em campanhas de RPG de mesa.**

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)

---

## 🏰 Sobre o Projeto

O **Taverna Web** é uma solução completa para mestres e jogadores que desejam centralizar suas mesas de RPG (VTT & Gerenciador de Campanhas) em um único ambiente moderno, ágil e acessível diretamente pelo navegador. 

Seja para gerenciar investigações em cenários paranormais contemporâneos ou orquestrar combates táticos contra as forças de um lorde demônio em mundos de fantasia sombria, a plataforma elimina a sobrecarga de ferramentas externas. O sistema reúne em uma única interface: fichas de personagens interativas, controle de rodadas, mapas táticos com tokens dinâmicos, rolagem de dados em tempo real, biblioteca de regras em PDF e trilha sonora imersiva.

---

## 🏗️ Arquitetura e Repositórios

Nosso projeto adota uma arquitetura de **Multirepos** para garantir a separação de responsabilidades, escalabilidade e facilidade de testes em contêineres isolados. 

Explore os repositórios oficiais da organização:

### 🖥️ [taverna-web-frontend](https://github.com/Taverna-Web/taverna-web-frontend)
Responsável pela interface do usuário e experiência visual (UI/UX).
- **Tecnologias:** Vite, JavaScript/TypeScript, React/Vue (A definir).
- **Foco:** Consumo da API, renderização do grid de batalha, interatividade da ficha de personagem e player do Spotify.

### ⚙️ [taverna-web-backend](https://github.com/Taverna-Web/taverna-web-backend)
Responsável pelas regras de negócio, persistência e comunicação em tempo real.
- **Tecnologias:** .NET 10 (ASP.NET Core), Entity Framework, SignalR / WebSockets.
- **Foco:** Banco de dados relacional, autenticação, lógica matemática do rolador de dados e endpoints RESTful.

*(Nota: Para instruções de instalação, configuração de ambiente e execução local, consulte o arquivo `README.md` individual de cada repositório acima).*

---

## ✨ Funcionalidades Principais

- **Autenticação & Multi-Campanhas:** Criação e gestão de contas com suporte para alternar entre múltiplas campanhas persistidas.
- **Fichas Interativas:** Edição de fichas de personagens e NPCs, com controle dinâmico de atributos, inventário e condições.
- **Painel do Mestre & Combate:** Controle de ordem de iniciativa, gerenciamento de turnos e rastreamento de status.
- **Mapas Táticos & Tokens Virtuais:** Suporte para upload de mapas com grid tático e manipulação em tempo real via WebSockets.
- **Biblioteca Integrada:** Upload e leitor de manuais em PDF com pesquisa rápida integrada.
- **Rolador de Dados Confiável:** Suporte a dados poliédricos padrão, modificadores e fórmulas customizadas.
- **Trilha Sonora Integrada (Spotify API):** Conexão com o Spotify para controle de playlists e efeitos sonoros diretamente da mesa.

---

## 🗺️ Roadmap de Desenvolvimento

- [ ] Concepção da arquitetura multirepo e documentação central (Você está aqui 📍)
- [ ] Construção dos contêineres e comunicação inicial (Vite ↔ .NET)
- [ ] Sistema de Autenticação e Gestão de Usuários
- [ ] Módulo de Criação de Campanhas e Fichas de Personagem
- [ ] Implementação de WebSockets para rolagem de dados e sincronização
- [ ] Painel do Mestre: Rastreador de combate e iniciativa
- [ ] Sistema de Mapas de Batalha com Tokens Dinâmicos
- [ ] Integração com Spotify API e Leitor de PDF

---

## 🤝 Como Contribuir

Contribuições para a Taverna são muito bem-vindas! Como nosso sistema é modular, você pode contribuir diretamente para a stack que tem mais afinidade.

1. Escolha o repositório (`frontend` ou `backend`) onde deseja atuar.
2. Faça um **Fork** do repositório escolhido.
3. Crie uma branch para a sua funcionalidade/correção (`git checkout -b feat/minha-feature`).
4. Commit suas alterações e envie para o GitHub.
5. Abra um **Pull Request** detalhando as mudanças arquiteturais.

---

## 📄 Licença

O ecossistema Taverna Web é distribuído sob a licença [MIT](LICENSE).

---

## 🧙 Autores e Mantenedores

Desenvolvido por **Bruno Ribeiro Viana Diniz** e equipe.
- GitHub: [@Diniz-Bruno](https://github.com/Diniz-Bruno)
- GitHub: [@ottoyshiro](https://github.com/ottoyshiro)
- GitHub: [@p08650519-creator](https://github.com/p08650519-creator)

---
*Que suas rolagens sejam sempre 20 naturais! 🎲✨*
