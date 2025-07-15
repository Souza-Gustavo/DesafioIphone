# 📱 Desafio DIO – Modelando o iPhone com UML

Este foi o desafio “Modelando o iPhone com UML”, onde representamos funcionalidades do iPhone (músicas, chamadas e internet) por meio de um diagrama UML em Mermaid.

---

## 🎥 Visão Geral

- **Objetivo**: Modelar em UML as três funções principais:
  - 🎵 **Reprodutor Musical** (`tocar()`, `pausar()`, `selecionarMusica()`)
  - 📞 **Aparelho Telefônico** (`ligar()`, `atender()`, `iniciarCorreioVoz()`)
  - 🌐 **Navegador de Internet** (`exibirPagina()`, `adicionarNovaAba()`, `atualizarPagina()`)
- **Ferramenta usada**: [Mermaid Chart](https://www.mermaidchart.com) — editor colaborativo que gera UML em texto que pode ser renderizado diretamente no GitHub.

---

## 🧩 Diagrama UML

Abaixo está o diagrama UML criado no Mermaid. Para editar, acesse o projeto original:

👉 [Editar diagrama no Mermaid Chart](https://www.mermaidchart.com/app/projects/71c07eda-2aaf-4b16-86be-3a666c58da88/diagrams/d67981b8-1819-4144-aa20-b9826474a032/version/v0.1/edit)

```mermaid
%% Colei aqui o código gerado pelo Mermaid Chart  

classDiagram
    Iphone --|> ReprodutorMusical
    Iphone --|> AparelhoTelefonico
    Iphone --|> NavegadorInternet
    class ReprodutorMusical{
      +tocar()
      +pausar()
      +selecionarMusica()
    }
    class AparelhoTelefonico{
      +ligar()
      +atender()
      +iniciarCorreioVoz()
    }
    class NavegadorInternet{
      +exibirPagina()
      +adicionarNovaAba()
      +atualizarPagina()
    }
