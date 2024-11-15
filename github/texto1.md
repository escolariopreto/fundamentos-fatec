# Introdução ao GitHub para Iniciantes

Bem-vindo(a)! Este artigo é uma introdução detalhada ao GitHub, destinada a iniciantes que desejam aprender a usar essa poderosa plataforma de desenvolvimento colaborativo. Aqui, abordaremos os conceitos básicos, desde a criação de uma conta até o gerenciamento de repositórios e colaboração com outros desenvolvedores.

## O Que é o GitHub?

O GitHub é uma plataforma online que hospeda repositórios Git, permitindo que desenvolvedores colaborem em projetos de software. Ele combina controle de versão (fornecido pelo Git) com recursos de rede social, como seguidores, estrelas e issues (problemas).

## Pré-requisitos

- **Git**: Git é um sistema de controle de versão distribuído. Certifique-se de que o Git esteja instalado em seu computador. Você pode baixar em [git-scm.com](https://git-scm.com/).

## Sumário

- [Criando uma Conta no GitHub](#criando-uma-conta-no-github)
- [Configurando o Git Localmente](#configurando-o-git-localmente)
- [Conceitos Básicos do Git](#conceitos-básicos-do-git)
- [Criando Seu Primeiro Repositório](#criando-seu-primeiro-repositório)
- [Trabalhando com Repositórios Locais e Remotos](#trabalhando-com-repositórios-locais-e-remotos)
- [Fluxo de Trabalho Básico](#fluxo-de-trabalho-básico)
- [Colaboração no GitHub](#colaboração-no-github)
- [Recursos Adicionais](#recursos-adicionais)

## Criando uma Conta no GitHub

1. **Acesse o site do GitHub**: [github.com](https://github.com/)
2. **Clique em "Sign up"**: Preencha os campos com seu e-mail, senha e nome de usuário.
3. **Personalize sua conta**: Siga os passos para configurar suas preferências iniciais.
4. **Verifique seu e-mail**: Confirme sua conta através do link enviado para seu e-mail.

## Configurando o Git Localmente

Abra o terminal ou prompt de comando e configure seu nome de usuário e e-mail:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu-email@example.com"
```

## Conceitos Básicos do Git

- Repositório (Repo): Local onde o código do seu projeto é armazenado.
- Commit: Um snapshot do estado do seu projeto.
- Branch: Uma linha separada de desenvolvimento.
- Merge: Combinar mudanças de diferentes branches.
- Clone: Cópia de um repositório remoto para o seu computador.
- Pull: Atualizar seu repositório local com as mudanças do repositório remoto.
- Push: Enviar suas mudanças locais para o repositório remoto.

## Criando Seu Primeiro Repositório
Pelo GitHub

# 1. Clique em "New Repository": Na sua página inicial do GitHub.
# 2. Preencha os detalhes:
    - Repository name: Nome do seu repositório.
    - Description: (Opcional) Descrição do projeto.
    - Public/Private: Escolha a visibilidade.
    - Initialize this repository with a README: Marque essa opção se quiser criar um README automaticamente.
# 3. Clique em "Create repository".


## Clonando o Repositório para Seu Computador

No terminal, navegue até a pasta onde deseja armazenar o projeto e execute:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

## Trabalhando com Repositórios Locais e Remotos
Adicionando Arquivos e Fazendo Commits

# 1. Navegue até o diretório do repositório:
```bash
cd nome-do-repositorio
```

# 2. Crie ou modifique arquivos:
```bash
echo "Olá, GitHub!" > arquivo.txt
```

# 3. Adicione as mudanças para staging:
```bash
git add arquivo.txt
```

# 4. Faça um commit das mudanças:
```bash
git commit -m "Adiciona arquivo.txt com mensagem de saudação"
```

# 5. Enviando as Mudanças para o GitHub
```bash
git push origin main
```
> Nota: Substitua main pelo nome da branch, se for diferente.

## Fluxo de Trabalho Básico

# 1. Atualize seu repositório local:
```bash
git pull origin main

```
# 2. Crie uma nova branch para novas features:
```bash
git checkout -b nova-feature
```
# 3. Após fazer mudanças, adicione e commit:
```bash
git add .
git 	commit -m "Implementa nova feature"
```
# 4. Envie a branch para o repositório remoto:
```bash
git push origin nova-feature
```

# 5. Abra um Pull Request no GitHub:
    - Acesse o repositório no GitHub.
    - Clique em Compare & pull request.
    - Preencha os detalhes e envie o Pull Request.

# 6. Merge da Branch:
    - Após revisão, mescle a branch com a main pelo GitHub.

## Colaboração no GitHub
# Forks e Pull Requests

- Fork: Cria uma cópia do repositório no seu perfil, permitindo que você trabalhe nele sem afetar o original.
- Pull Request: Solicitação para que as mudanças da sua branch sejam mescladas em outra branch do repositório original.

# Issues

- Issues: São usadas para rastrear tarefas, melhorias ou bugs.
- Criando uma Issue:
    - Vá até a aba Issues no repositório.
    - Clique em New issue.
    - Descreva o problema ou sugestão.

## Recursos Adicionais

> Documentação Oficial do Git: git-scm.com/doc
> Guias do GitHub: guides.github.com
> Pro Git Book (Gratuito): git-scm.com/book/pt-br/v2

# Dicas Finais

>  Pratique os comandos do Git regularmente.
>  Leia a documentação e tutoriais.
>  Não tenha medo de experimentar em repositórios de teste.

Autor: FA.TEC.br
Data: Novembro de 2024
