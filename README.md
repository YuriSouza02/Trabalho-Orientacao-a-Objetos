```markdown
# ⚓ Batalha Naval (Java Swing)

![Java](https://img.shields.io/badge/Java-17-orange.svg)
![Maven](https://img.shields.io/badge/Maven-Build-blue.svg)
![License](https://img.shields.io/badge/Licen%C3%A7a-Acad%C3%AAmica-green.svg)

Jogo clássico de **Batalha Naval** desenvolvido em Java com interface gráfica interativa utilizando **Java Swing**. Projeto desenvolvido para a disciplina de **Programação Orientada a Objetos**.

---

## 🎮 Funcionalidades

- **Interface Gráfica (GUI):** Tabuleiros visuais e dinâmicos para o jogador humano e o bot.
- **Níveis de Dificuldade:**
  - **Fácil:** Disparos totalmente aleatórios sem estratégia.
  - **Médio:** Bot busca posições adjacentes após atingir um alvo.
  - **Difícil:** Desafio avançado com lógica aprimorada de caça e destruição.
- **Geração Aleatória de Tabuleiro:** Posições e orientações dos navios sorteadas no início de cada partida.
- **Sistema de Placar e Ranking:** Persistência dos resultados dos jogadores em arquivo e exibição ao final dos jogos.

---

## 🚀 Tecnologias Utilizadas

- **Java 17 (LTS)** — Linguagem base do projeto
- **Java Swing** — Construção da Interface Gráfica de Usuário (GUI)
- **Apache Maven** — Gerenciamento de dependências e automação de build
- **Gson** — Manipulação e persistência de dados em formato JSON

---

## 🛠️ Como Executar o Projeto

### Pré-requisitos
* **JDK 17** ou superior instalado e configurado nas variáveis de ambiente (`JAVA_HOME`).
* **Apache Maven** instalado e configurado no `PATH`.

### Passos para Execução

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
   cd NOME-DO-REPOSITORIO

```

2. **Compilar e executar via Maven:**
```bash
mvn clean compile exec:java

```


3. **(Opcional) Gerar e executar o arquivo `.jar`:**
```bash
mvn clean package
java -jar target/Trabalho-1.0-SNAPSHOT.jar

```



---

## 📁 Estrutura do Projeto

```text
src/
 └── main/
      └── java/
           ├── BatalhaNaval/   # Tela principal, componentes de GUI e escutadores
           ├── control/        # Controladores e mediação de ações
           ├── IA/             # Estratégias e lógica de inteligência artificial
           ├── model/          # Regras de negócio (Jogador, Tabuleiro, Embarcação)
           └── Outros/         # Serviços de persistência em JSON e gerenciamento de placar

```

---

## 👨‍💻 Desenvolvedores

* **Yuri Alexsander Sudre Almeida Souza**
* **Rafaela da Silva Cunha**
* **Victor Aluisio dos Santos Oliveira**

---

## 📄 Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos e educacionais.

```

---

### Principais melhorias aplicadas

* **Correção de Links e Markdown:** Removido a sintaxe Markdown de link (`[...]()`) de dentro do bloco de código `bash` na etapa de clone, o que quebrava a formatação do terminal.
* **Badges de Status:** Adicionadas badges no topo para indicar visualmente a versão do Java, ferramenta de build (Maven) e o escopo da licença.
* **Limpeza de Caracteres Especiais:** Removidos espaços não-inquebráveis (`\u00a0`) que afetavam a indentação das listas.
* **Aprimoramento da Árvore de Arquivos:** Ajustada a representação visual da estrutura `src/` para manter o padrão Maven (`src/main/java/...`).
* **Padronização do Texto:** Ajustes pontuais de concordância, clareza nas descrições da IA e inclusão da verificação de variáveis de ambiente no pré-requisito do Java.

```
