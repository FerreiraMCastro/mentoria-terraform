
#  Projeto Terraform - Mentoria Steam for Women

Este repositório faz parte do meu aprendizado na mentoria **Steam for Women**, focada em infraestrutura como código (IaC) usando **Terraform** na AWS.

##  O que foi criado?

- Uma instância EC2 executando **Ubuntu 22.04 LTS**, provisionada via Terraform.
- Um **bucket S3** para armazenamento de objetos.
- Utilização de **IAM** para criação e gerenciamento seguro de credenciais de acesso.

##  Segurança

Para garantir a segurança, utilizei um arquivo `.tfvars` (não versionado) que contém as minhas credenciais de acesso à AWS (chave de acesso e chave secreta). Esse arquivo está protegido via `.gitignore` e não é enviado para o GitHub.

##  Tecnologias e Ferramentas

- **Terraform**
- **AWS** (EC2, S3, IAM)
- **VSCode**
- **Git e GitHub**

## 📂 Estrutura do Projeto
├── main.tf # Código principal de provisionamento
├── terraform.tfstate # Arquivo de estado (não versionado)
├── terraform.tfvars # Variáveis sensíveis (não versionado)
├── .gitignore # Arquivos ignorados no Git
├── README.md # Documentação do projeto




## 🌍 Objetivo

Meu objetivo com este projeto é:

- Praticar a criação de infraestrutura na AWS utilizando o Terraform.
- Entender conceitos de IaC, versionamento de infraestrutura e boas práticas.
- Fortalecer minha jornada de aprendizado rumo à carreira em **DevOps e Cloud**.

## ⚠️ Aviso

> 🔒 Este projeto é apenas para fins de estudo. Nenhuma credencial sensível é armazenada ou compartilhada publicamente.

---

✨ Feito com muita dedicação por [Marcia Ferreira](https://www.linkedin.com) durante a mentoria Steam for Women.
