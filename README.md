# Desafio Sistema de Controle de Estacionamento

Um sistema web moderno e responsivo desenvolvido para o gerenciamento de pátio de estacionamento, construído com **TypeScript**, **HTML5** e **CSS**. O projeto foca em boas práticas de arquitetura front-end, tipagem estática rigorosa, persistência de dados local e uma interface limpa e intuitiva. Repo está abaixo, clone e melore o sistema!!

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

Como rodar a página no **VS Code (Live Server)**
O **Live Server** é uma extensão essencial para desenvolvedores Front-end. Ele cria um servidor local na sua máquina para abrir a página web.

A porta padrão: Quando você inicia o Live Server, ele geralmente roda na porta 5500 (ficando com um endereço parecido com [http://127.0.0.1:5500](http://127.0.0.1:5500) ou http://localhost:5500).

Como abrir:

No **VS Code**, instale a extensão Live Server (caso ainda não tenha).

Clique com o botão direito em cima do arquivo index.html na barra lateral de arquivos do projeto.

Selecione **Open with Live Server**.

O navegador vai abrir sozinho já atualizando em tempo real sempre que você salvar alguma alteração.

🧪 Exemplos de Uso (Massa de Testes) Para testar o fluxo de entrada e saída no sistema, utilize os dados abaixo na interface da aplicação:Veículo Placa Padrão Honda CivicABC-1234Cinza (Antigo)Toyota Corolla BRA4A21 Mercosul Volkswagen FuscaXYZ-9876 Cinza (Antigo)

Basta digitar qualquer um deles na tela, clicar em Registrar e testar o sistema de pátio!
Ao lado fica um "X" que é quando o veículo sai do estacionamento e mostra o tempo de permamencia no pátio!!

---
1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/HigorCamposGit/Desafio-Sistema-de-Controle-de-Estacionamento.git](https://github.com/HigorCamposGit/Desafio-Sistema-de-Controle-de-Estacionamento.git)

---
## 🤝 Conecte-se Comigo

<p align="center">
  <img src="https://github.com/HigorCamposGit.png" width="100px" style="border-radius: 50%;" alt="Foto de Higor de Campos" /><br />
  <b>Projeto atualizado por:</b> <a href="https://github.com/HigorCamposGit">Higor de Campos</a>
</p>

---

