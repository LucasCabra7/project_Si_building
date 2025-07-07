<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=66CDAA&height=120&section=header"/>

# SGMP - Sistema de Gerenciamento de Manutenção Predial 🏢🧰

Projeto desenvolvido para a disciplina de **Engenharia de Software com Orientação a Objetos (EDOO)**, utilizando a linguagem **C++** e os princípios fundamentais da **Programação Orientada a Objetos**.

---

## 📌 Objetivo

O SGMP tem como foco oferecer uma plataforma digital para **organizar, registrar e gerenciar manutenções prediais** dentro de condomínios ou edifícios. Ele visa substituir os métodos informais por um sistema rastreável e seguro, garantindo **transparência**, **controle** e **histórico de ordens de serviço (OS)**.

---

## 👨‍💻 Integrantes da Equipe

- Bruno Gabriel `<bgprs>`
- Diogo da Silva `<dsr>`
- Felipe Berardo `<fbalv>`
- Hugo José `<hjbc>`
- Lucas Cabral `<lsc>`

---

## 🧱 Tecnologias e Ferramentas

- 🖥️ Linguagem: **C++**
- 💾 Paradigma: **Programação Orientada a Objetos**
- 📋 Documentação: **Google Docs, Miro, Youtube**
- 🎨 Apresentação visual: **Canva, Miro**
- 🌐 Interface Web: **HTML + (GitHub Pages)**

---

## 🧩 Arquitetura do Sistema

O sistema é composto pelas seguintes classes:

- `Pessoa` (classe base): nome, ID, contato.
- `Morador`: herda de Pessoa; possui apartamento e bloco.
- `Técnico`: herda de Pessoa; possui especialidade.
- `OrdemDeServico`: gerencia a OS, status, datas, morador solicitante e técnico responsável.

### 🧠 Princípios de POO Aplicados

| Conceito         | Como foi aplicado                                              | Benefício                            |
|------------------|----------------------------------------------------------------|---------------------------------------|
| **Herança**       | `Morador` e `Técnico` herdam de `Pessoa`                      | Reutilização de código e hierarquia   |
| **Polimorfismo**  | Método virtual `exibirInformacoes()`                          | Flexibilidade para múltiplos perfis   |
| **Encapsulamento**| Atributos privados e acesso via métodos públicos              | Segurança e consistência dos dados    |
| **Abstração**     | Interface clara de cada classe, escondendo complexidade interna| Facilidade de uso e manutenção        |

---

## 🔄 Fluxo de Uso (Resumo)

1. O morador abre uma nova Ordem de Serviço com uma descrição do problema.
2. A OS é criada com status **"ABERTA"**.
3. Um técnico com especialidade compatível assume a OS.
4. A OS muda para **"EM ANDAMENTO"**.
5. Após a execução do serviço, o técnico finaliza a OS.
6. A OS passa para o status **"CONCLUÍDA"** com todo o histórico registrado.

---

## 🌍 Interface Web (opcional)

Você pode acessar a versão do site em:  
🔗 [](githubpages virá aqui)

> *Feita com HTML e CSS para visualização e documentação do projeto.*

---

## Passos para rodar o projeto localmente

1. Estar Utilizando o Sistema Operacional Windows

2. Clone o repositório:
```bash
https://github.com/Monkius-Maximus/Projeto-EDOO-25.1.git
```
3. Abrir o Terminal

4. Utilizar o Comando "./config" para compilar e executar o código.

## Galeria de Projetos

 ![tela inicial](https://github.com/user-attachments/assets/52e220ca-be4f-4277-963a-ec6175d42d94)
 
*Legenda: Tela inicial do programa*

![tela morador](https://github.com/user-attachments/assets/4475ca8c-3ad9-4f25-9f66-49029370e59f)

*Legenda: Visão do Morador ao Iniciar*

![morador ver os](https://github.com/user-attachments/assets/2a564335-3685-43bb-9620-6624b2f8baf6)

*Legenda: Visão do Morador ao Visualizar os apenas aos Seus Chamados*

 ![abertura da os](https://github.com/user-attachments/assets/75c65e62-cfe2-4dca-a9f1-4ee7ad6f63f5)
 
*Legenda: Visão do Morador para Abrir Ordem de Serviço*


![avaliar os](https://github.com/user-attachments/assets/6a2a962e-d0e4-4a44-b6f2-41acd9a17aef)

*Legenda: Visão do Morador para avaliar o serviço*


 ![tecnico](https://github.com/user-attachments/assets/c08d29df-af0b-49f2-bfac-7957cb44370f)

*Legenda: Visão do Tecnico ao Iniciar*

 ![tecnico visualizar](https://github.com/user-attachments/assets/d59c994f-2173-42a0-b13d-173ff6d6c517)

*Legenda: Visão do Tecnico ao Visualizar OS*

  ![tecnico acietar os](https://github.com/user-attachments/assets/5f2cd715-07f7-4df5-9894-e27b9003d643)

*Legenda: Visão do Tecnico para Aceitar Os*

 ![tecnico visualizar aceitados](https://github.com/user-attachments/assets/c1ff9850-4f98-4632-bb5f-e7785307533c)

*Legenda: Visão do Tecnico para visualizar os chaamdos*

## 📎 Links Úteis

- 📒 Miro Diagrama de Classes (Documentação): [Acessar](https://miro.com/app/board/uXjVIjGJgRI=/?share_link_id=360641450079)
- 🖼️ Video Gravação da Equipe (Documentação): [Acessar]() 

---

## 📃 Licença

Este projeto é de caráter acadêmico, sem fins lucrativos. Todos os direitos reservados aos autores.

## Equipe do Projeto

<div align="center">

  <table>
    <tr>
      <td align="center">
        <img src="https://avatars.githubusercontent.com/u/162474087?v=4" width="100px" alt="Pessoa 1"/><br/>
        <b>Bruno Ramos 1</b>
      </td>
      <td align="center">
        <img src="https://avatars.githubusercontent.com/u/155683708?v=4" width="100px" alt="Lucas Cabral"/><br/>
        <b>Lucas Cabral</b>
      </td>
      <td align="center">
        <img src="https://avatars.githubusercontent.com/u/204962998?v=4" width="100px" alt="Samuel Miranda"/><br/>
        <b>Felipe Berardo</b>
      </td>
      <td align="center">
        <img src="https://avatars.githubusercontent.com/u/149613054?v=4" width="100px" alt="Pessoa 3"/><br/>
        <b>Diogo Rodrigues</b>
      </td>
      <td align="center">
        <img src="https://avatars.githubusercontent.com/u/205383087?v=4" width="100px" alt="Pessoa 3"/><br/>
        <b>Hugo Joseph</b>
      </td>
    </tr>
  </table>

</div>

---

<p align="center">
  &copy; 2025 Universidade Federal de Pernambuco - Centro de Informática. Todos os direitos reservados.
</p>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=66CDAA&height=120&section=header"/>
