# Ora Bolas (Rust)

Reescrita em Rust do projeto acadêmico **Ora Bolas**, que simula a interceptação entre um robô de futebol e uma bola em movimento, calculando grandezas cinemáticas e gerando gráficos com os resultados.

## 📖 Sobre o projeto

Este repositório é uma reimplementação em Rust do projeto originalmente desenvolvido em Python, disponível em [Projeto-Ora-Bolas-Python](https://github.com/PauloGabrielLeme/Projeto-Ora-Bolas-Python). A proposta do projeto é, dado um robô posicionado em um ponto inicial do campo e uma bola que segue uma trajetória pré-estabelecida, calcular o ponto de interceptação entre os dois e as grandezas físicas envolvidas (distância, tempo, velocidade, aceleração, forças), além de plotar os resultados em gráficos.

Nesta versão em Rust (pacote `P_Ora_Bolas`, atualmente na versão `0.3.0`), a geração dos gráficos é feita com a crate [`plotters`](https://crates.io/crates/plotters) no lugar do `matplotlib` usado na versão em Python. O objetivo do repositório é servir como exercício de prática da linguagem Rust, reaproveitando a lógica do projeto original.

> ⚠️ **Em desenvolvimento.** Este repositório ainda não possui uma descrição pública nem licença definida no GitHub. As instruções abaixo cobrem o que pôde ser confirmado a partir do `Cargo.toml`/`Cargo.lock` (nome do pacote, versão e dependências); para detalhes exatos de entrada/saída do programa, consulte o código-fonte em `src/`.

## 🛠 Tecnologias

- [Rust](https://www.rust-lang.org/) (edition 2021)
- [Cargo](https://doc.rust-lang.org/cargo/)
- [`plotters`](https://crates.io/crates/plotters) `0.3.5` — geração dos gráficos (trajetórias, posições, velocidades, acelerações etc.)

## 🗂 Estrutura do repositório

```
.
├── src/          # código-fonte do programa em Rust
├── Cargo.toml    # metadados e dependências do projeto
├── Cargo.lock
└── .gitignore
```

## 📋 Pré-requisitos

- [Rust e Cargo](https://www.rust-lang.org/tools/install) instalados (recomendado via `rustup`)

## ▶️ Como compilar e executar

```bash
git clone https://github.com/PauloGabrielLeme/Ora-Bolas-Rust.git
cd Ora-Bolas-Rust
cargo build --release
cargo run --release
```

## 🔗 Projeto relacionado

- [Projeto-Ora-Bolas-Python](https://github.com/PauloGabrielLeme/Projeto-Ora-Bolas-Python) — versão original do projeto, em Python.

## 👤 Autoria

Desenvolvido por [Paulo Gabriel Gonçalves Leme](https://github.com/PauloGabrielLeme).

## 📄 Licença

Nenhuma licença foi definida para este repositório até o momento.
