<div align="center">

# Readme Maker

Gerador simples de README.md para projetos que precisam de documentação limpa, rápida e sem cara de texto automático.

[![License](https://img.shields.io/github/license/Guto-Edu/README_Maker?style=flat-square&color=1769e0)](LICENSE)
[![Stars](https://img.shields.io/github/stars/Guto-Edu/README_Maker?style=flat-square&color=1769e0)](https://github.com/Guto-Edu/README_Maker/stargazers)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-1769e0?style=flat-square)
![Feito com](https://img.shields.io/badge/feito%20com-HTML%2C%20CSS%20e%20JS-0b57c0?style=flat-square)

[Ver projeto online](https://guto-edu.github.io/README_Maker/) · [Repositório](https://github.com/Guto-Edu/README_Maker)

</div>

---

## Sobre

O **Readme Maker** é uma página web feita para gerar arquivos `README.md` de forma rápida, organizada e fácil de editar.

A proposta é simples: você preenche as informações principais do projeto, escolhe as seções que fazem sentido e recebe um README pronto para copiar ou baixar. Sem cadastro, sem instalação obrigatória, sem painel pesado e sem depender de ferramenta externa.

Este README também foi criado seguindo o próprio fluxo do gerador: base do projeto, stack, conteúdo, badges, autoria e resultado final em Markdown.

* **Tipo:** Aplicação web estática
* **Status:** Em desenvolvimento
* **Versão:** 1.0.0

---

## Stack

* HTML
* CSS
* JavaScript
* Markdown
* GitHub Pages

---

## Funcionalidades

* Geração automática de README.md
* Preview do Markdown gerado
* Cópia rápida para a área de transferência
* Download do arquivo `README.md`
* Salvamento de rascunho no navegador
* Seleção de seções opcionais
* Badges para licença, stars, forks, issues, versão e último commit
* Bloco de autoria com avatar do GitHub
* Layout claro, limpo e responsivo

---

## Por que esse projeto existe?

README bom não precisa parecer anúncio. Ele precisa fazer alguém entender:

* O que o projeto faz
* Como rodar
* Quais tecnologias usa
* Quem criou
* Como contribuir
* Qual é o status do desenvolvimento

O **Readme Maker** nasceu para acelerar essa parte sem transformar a documentação em um texto genérico demais.

---

## Acessando online

Quando publicado com GitHub Pages, o projeto pode ser acessado pelo navegador:

```txt
https://dudadepb6.github.io/readme-maker/
```

> Se você usar outro nome de repositório, troque `readme-maker` na URL pelo nome correto.

---

## Rodando localmente

Como o projeto é feito com HTML, CSS e JavaScript puro, você não precisa instalar dependências.

**Clone o projeto**

```bash
git clone https://github.com/dudadepb6/readme-maker.git
cd readme-maker
```

**Abra o arquivo principal**

Abra o arquivo `index.html` diretamente no navegador.

Se estiver usando VS Code, também pode abrir com a extensão **Live Server** para testar como uma página local.

---

## Como usar

1. Abra o projeto no navegador
2. Preencha a base do projeto:

   * Nome
   * Usuário do GitHub
   * Frase curta
   * Descrição
   * Tipo, status, licença e versão
3. Informe a stack e os comandos principais
4. Escreva funcionalidades, uso, estrutura e roadmap
5. Escolha as seções e badges que deseja incluir
6. Clique em **Gerar README**
7. Copie o Markdown ou baixe o arquivo `README.md`

---

## Estrutura do projeto

```txt
readme-maker/
├── index.html
├── README.md
└── LICENSE
```

Caso você separe CSS e JavaScript futuramente, uma estrutura legal seria:

```txt
readme-maker/
├── index.html
├── README.md
├── LICENSE
├── assets/
│   └── preview.png
├── src/
│   ├── styles.css
│   └── script.js
└── docs/
    └── screenshots/
```

---

## Publicando no GitHub Pages

A forma mais simples de deixar o projeto acessível é usando **GitHub Pages**.

### 1. Crie um repositório público

Sugestão de nome:

```txt
readme-maker
```

### 2. Coloque os arquivos na raiz

O arquivo principal precisa estar como:

```txt
index.html
```

Exemplo:

```txt
readme-maker/
├── index.html
├── README.md
└── LICENSE
```

### 3. Envie para o GitHub

```bash
git init
git add .
git commit -m "feat: adiciona gerador de readme"
git branch -M main
git remote add origin https://github.com/dudadepb6/readme-maker.git
git push -u origin main
```

### 4. Ative o GitHub Pages

No repositório:

1. Vá em **Settings**
2. Entre em **Pages**
3. Em **Build and deployment**, escolha **Deploy from a branch**
4. Em **Branch**, selecione:

   * Branch: `main`
   * Folder: `/root`
5. Clique em **Save**

Depois disso, o GitHub vai gerar uma URL parecida com:

```txt
https://dudadepb6.github.io/readme-maker/
```

---

## Screenshots

Adicione aqui uma imagem real do projeto.

```md
![Preview do Readme Maker](./assets/preview.png)
```

Sugestão: tire um print da tela com o formulário e o resultado gerado embaixo.

---

## Roadmap

* [ ] Adicionar tema escuro
* [ ] Permitir escolher modelos diferentes de README
* [ ] Criar botão para copiar apenas seções específicas
* [ ] Melhorar o preview de Markdown
* [ ] Adicionar opção de idioma inglês
* [ ] Criar exemplos prontos para preencher o formulário
* [ ] Separar CSS e JavaScript em arquivos próprios
* [ ] Adicionar imagem de preview no repositório

---

## Contribuição

Contribuições são bem-vindas.

1. Faça um fork do projeto
2. Crie uma branch para sua alteração:

```bash
git checkout -b minha-melhoria
```

3. Faça o commit:

```bash
git commit -m "feat: adiciona minha melhoria"
```

4. Envie para o seu fork:

```bash
git push origin minha-melhoria
```

5. Abra um Pull Request

---

## Boas práticas para contribuir

Antes de abrir um Pull Request, confira:

* O layout continua responsivo
* O gerador não quebrou a saída em Markdown
* Os botões de copiar, baixar e salvar rascunho continuam funcionando
* O texto gerado não ficou genérico demais
* O projeto continua simples de rodar

---

## Autor

<div align="center">
  <a href="https://github.com/dudadepb6">
    <img src="https://github.com/dudadepb6.png" width="86" style="border-radius: 50%;" alt="Maria Eduarda" />
    <br />
    <strong>Maria Eduarda</strong>
  </a>
  <br />
  <span>Criadora do Readme Maker</span>
</div>

---

## Licença

Este projeto está sob a licença **MIT**.

Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<div align="center">

Feito por [Maria Eduarda](https://github.com/dudadepb6)

Se esse projeto te ajudou, deixe uma estrela no repositório.

</div>
