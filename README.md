# Sistema de Controle de Estacionamento

Um sistema web moderno e responsivo desenvolvido para o gerenciamento de pátio de estacionamento, construído com **TypeScript**, **HTML5** e **CSS**. O projeto foca em boas práticas de arquitetura front-end, tipagem estática rigorosa, persistência de dados local e uma interface limpa e intuitiva.

---

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estrutura semântica e acessível da aplicação.
* **TypeScript:** Superset do JavaScript que adiciona tipagem estática e interfaces, garantindo maior manutenibilidade e segurança no código.
* **CSS3:** Estilização moderna, responsiva e focada em UX (User Experience).
* **LocalStorage:** Persistência de dados diretamente no navegador do usuário, garantindo que os veículos cadastrados não se percam ao atualizar a página.
* **Ferramentas de Desenvolvimento:** VS Code, Compilador TypeScript (`tsc` em watch mode) e Live Server.

---

## ⚙️ Funcionalidades

1. **Cadastro de Veículos:** Permite registrar o nome do veículo e a placa correspondente junto ao horário exato de entrada.
2. **Listagem em Tempo Real:** Exibe os veículos estacionados em uma tabela organizada com o cálculo dinâmico do tempo de permanência.
3. **Saída de Veículos:** Botão dedicado para encerrar a estadia, calculando o tempo total que o carro permaneceu no pátio e removendo-o do sistema após a confirmação.
4. **Persistência Local:** Todos os dados inseridos são salvos automaticamente no `localStorage` do navegador.

---

## 📂 Arquitetura e Estrutura do Projeto

O projeto foi refatorado a partir de uma versão legada para adotar tipagens estritas orientadas a objetos/interfaces no TypeScript:

* **`index.html`**: Interface de usuário estruturada com tags semânticas do HTML5.
* **`style.css`**: Folha de estilos customizada com paleta de cores limpa, botões responsivos e alinhamento profissional.
* **`main.ts`**: Código-fonte principal em TypeScript contendo a lógica de negócio, manipulação do DOM e classes de controle do pátio.
* **`main.js`**: Arquivo JavaScript gerado automaticamente pelo compilador TypeScript a partir do `main.ts`.
* **`tsconfig.json`**: Configurações do compilador TypeScript.
* **`.gitignore`**: Arquivos e diretórios ignorados pelo versionamento (como módulos de dependência e arquivos temporários).

---

## 💻 Como Rodar o Projeto Localmente

Siga os passos abaixo para clonar e executar a aplicação na sua máquina:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/HigorCamposGit/Desafio-Sistema-de-Controle-de-Estacionamento.git](https://github.com/HigorCamposGit/Desafio-Sistema-de-Controle-de-Estacionamento.git)
