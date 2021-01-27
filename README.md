<p align="center">
  <img alt="default" src="https://i.imgur.com/kpPqdMT.gif" float="center"/>
</p>

<h1 align="center">Sysadmin Troubleshooting</h1>

<p align="center">
  👽 Repositório dedicado a documentar tarefas/processos do mundo de sysadmin 👽
</p>

<p align="center">
  <a href="LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-blue.svg" />
  </a>
  <a href="https://github.com/semantic-release/semantic-release">
    <img alt="semantic-release" src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg">
  </a>
  <a href="http://commitizen.github.io/cz-cli/">
    <img alt="Commitizen friendly" src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg">
  </a>
  <a href="https://github.com/lpmatos/sysadmin-troubleshooting/actions">
    <img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/lpmatos/sysadmin-troubleshooting/Scan">
  </a>
</p>

<p align="center">
  <a href="#-descrição">Description</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-objetivos">Objetivos</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tópicos">Tópicos</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## ➤ Iniciando

Se você quer usar esse repositório, a primeira coisa a ser feita é um `git clone` para a sua máquina 💻:

```bash
git clone --depth 1 <https://github.com/lpmatos/loli.git> -b main
```

Com isso você terá acesso a tudo que está aqui, localmente em seu ambiente.

## ➤ Descrição

Quais seriam os primeiros passos para se levar em consideração no início da análise de ambiente, independente se o cenário é ou não crítico? É com base na resposta para essa pergunta que esse repositório foi criado. Minha intenção aqui é falar sobre alguns comandos qualquer administrador de ambiente Linux pode usar para iniciar um troubleshooting em um servidor, independente do cenário que ele se encontra, além de abordar comandos rotineiros para quem está nesse posto.

### Cenários 🔗

- Cotidianamento, administradores de ambientes Linux estão acostumados a receber tickets de support, reclamações ou até mesmo nossos sistemas de monitoramente, que retorna feedbacks de possíveis problemas nos ambientes. Sem saber qual é o problema e sem saber nada do cenário, quais são os passos a serem feitos para validarmos a situação?
- Quais comandos mais usados por um administrador Linux para realização de Troubleshootings?

### Comandos mais usados 🎉

Em manutenções de rotina, esses comandos poderão te ajudar em algum momento, tanto para monitoramento, quanto para possíveis análises simples:


- ⮚ 📝 `ls` - Te permite lista todos os arquivos em um diretório.
- ⮚ 📝 `df` - Mostra a quantidade de espaço usada no disco rígido.
- ⮚ 📝 `du` - Ajuda a obter informações mais detalhadas sobre quais arquivos estão usando o espaço em disco em um diretório.
- ⮚ 📝 `top` - Mostra o uso da memória, CPU e outros insights importantíssimos.
- ⮚ 📝 `cd` - O change directory, te permite acessar um determinado diretório.
- ⮚ 📝 `mkdir` - Te permite criar um diretório.
- ⮚ 📝 `rm` - Com ele você irá conseguir remover aquivos ou diretórios.
- ⮚ 📝 `cat` - Concatena e imprime arquivos.
- ⮚ 📝 `vi` - Abre o editor de texto `viai`.
- ⮚ 📝 `curl` - Muito utilizado para verificar a conectividade da URL, além de ser ótimo para transferência de dados.
- ⮚ 📝 `tail` - Exibe a última parte de um arquivo.
- ⮚ 📝 `grep` - Comando para pesquisar padrões em um arquivo.
- ⮚ 📝 `env` - Define ou imprime variáveis de ambiente do sistema.
- ⮚ 📝 `netstat` - Retorna o status da sua rede. 

Para mais detalhes, veja nossa [documentação](./docs/commands.md)! 🧐

### Links 📌

- ⮚ 📂 <https://www.hostinger.com.br/tutoriais/comando-curl-linux>
- ⮚ 📂 <https://opensource.com/article/17/7/20-sysadmin-commands>
- ⮚ 📂 <https://www.devmedia.com.br/comandos-importantes-linux/23893>
- ⮚ 📂 <https://www.youtube.com/watch?v=CWUKGzL3oOw&t=6s>

## ➤ Objetivos

- ✔️ Definir os primeiros passos antes do inicio do Troubleshooting.
- ✔️ Citar os comandos mais utilizados.
- ✔️ Dar detalhes dos comandos mais utilizados.

## ➤ Tópicos

- [🗲 Iniciando](./docs/basic/1%20-%20Iniciando.md)
- [🗲 Comandos mais usados](./docs/commands.md)

## ➤ O que será aprendido? 

- Linux básico.
- Comandos default de sistemas operacionais Unix.
- Boas práticas para iniciar um processo de incidente em ambientes Linux.

## ➤ Versionamento

🚨 Ainda não temos um arquivo [**CHANGELOG.md**](CHANGELOG.md) gerado 🚨.

## ➤ Autor

👤 **Lucca Pessoa**

Fala tu!! Se você curtiu esse projeto e quiser entrar em contato comigo, esses são meus canais:

>
> * Email: luccapsm@protonmail.com
> * Website: [lpmatos](https://github.com/lpmatos)
> * Github: [@lpmatos](https://github.com/lpmatos)
> * GitLab: [@lpmatos](https://gitlab.com/lpmatos)
> * LinkedIn: [@luccapessoa](https://www.linkedin.com/in/luccapessoa/)
>

## ➤ Aviso

Esse repositório possui fins estudantis/demonstrativos, podendo ou não ser adequado para o seu projeto!

## ➤ Mostre seu suporte!

Dê uma ⭐️ se esse projeto te ajudou de alguma forma!

---

Esse [README](README.md) for criado com ❤️ por [mim](https://github.com/lpmatos) tendo inspiração no [readme-md-generator](https://github.com/kefranabg/readme-md-generator).
