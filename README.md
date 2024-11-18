
![aws](https://github.com/user-attachments/assets/50ce07e2-40df-4a74-9a98-335d5a65fc3d)

# Estudo de AWS

Este repositório é dedicado ao estudo dos serviços da Amazon Web Services (AWS).

## Introdução

A AWS oferece uma ampla gama de serviços de computação em nuvem que permitem que você crie e gerencie aplicações de forma eficiente e escalável. Este repositório tem como objetivo fornecer uma base sólida para quem deseja aprender sobre esses serviços.

## Serviços Principais

- **EC2**: Instâncias de computação escaláveis na nuvem.
- **S3**: Armazenamento de objetos seguro e escalável.
- **RDS**: Banco de dados relacional gerenciado.
- **Lambda**: Execução de código sem provisionar ou gerenciar servidores.
- **CloudFormation**: Gerenciamento de infraestrutura como código.

***

O primeiro passo para começar a usar os serviços da [AWS](https://aws.amazon.com/free/) é criar uma conta. Recomendo iniciar pelo Free Tier, que oferece uma variedade de serviços gratuitos por 12 meses, permitindo que você explore e aprenda sem custos iniciais.

![aws1](https://github.com/user-attachments/assets/5677ea39-e0ad-48e6-a656-f72fc8fc3733)

Após acessar sua conta, por padrão, a região configurada será **North Virginia (us-east-1)**. Você verá uma tela semelhante à imagem acima.

> **Dica:** Se desejar alterar a região, você pode fazer isso clicando no nome da região no canto superior direito do console da AWS e selecionando a região desejada no menu suspenso.

## Começando com o EC2 (Elastic Compute Cloud)

![aws2](https://github.com/user-attachments/assets/4ece4420-c115-4089-bcd5-500dac44c6f2)

![aws3](https://github.com/user-attachments/assets/9f619e54-7f7d-47cc-8c05-27d9bbda7e86)

![aws4](https://github.com/user-attachments/assets/999fec34-0c49-4730-81e5-7f68bff697c7)

![aws](https://github.com/user-attachments/assets/398bece2-0223-4b4d-9381-17df187d1bba)

Uma parte importante da configuração é criar um par de chaves, composto por uma chave pública e uma chave privada, para garantir acesso seguro ao servidor. A chave pública ficará no servidor, enquanto a chave privada ficará na nossa máquina.

![aws1](https://github.com/user-attachments/assets/e07c067a-be39-4272-9e0c-a039349f25ad)

Com o Windows instalado em minha máquina, a utilização do Windows Subsystem for Linux (WSL) se torna essencial para a realização de diversas operações que são mais eficientes ou exclusivas do ambiente Linux. 
Após gerar o par de chaves em formato .pem, salvei ele lá dentro do meu Linux, na pasta temporária (tmp).

![aws](https://github.com/user-attachments/assets/2b8c20a7-56b3-4692-b24a-ee74ccab7547)

![aws1](https://github.com/user-attachments/assets/d5ad78aa-e101-49f2-a121-bb3312b36606)

Adicionando um pouco de segurança a chave.

![aws2](https://github.com/user-attachments/assets/32f71eed-c477-4c20-a159-d5881998315c)

![aws3](https://github.com/user-attachments/assets/6c9fffe5-6389-4ef0-bf6d-207c182d4331)

![aws4](https://github.com/user-attachments/assets/91bfb9e1-019c-487c-b0d1-fdb9746574b7)

![aws5](https://github.com/user-attachments/assets/c8ae102c-5f19-4bd9-ad0b-1e7308591a21)

![aws6](https://github.com/user-attachments/assets/1bd2a6a4-fdfc-462d-b385-bcecf36f2e87)

Clicando em cima do ID da Instância.

![aws7](https://github.com/user-attachments/assets/682c00f2-890f-4565-aa5c-378f6747b467)

![aws8](https://github.com/user-attachments/assets/a4afb48d-a806-4a04-9421-6069dc551ae7)

![aws9](https://github.com/user-attachments/assets/aeaef773-aa2b-4064-9bff-359f544e4a47)

Instância EC2 conectada!

***

Configurando Grupos de Segurança

![aws10](https://github.com/user-attachments/assets/3c392426-1b7a-4ac2-9c24-fa6b233f5327)

![aws11](https://github.com/user-attachments/assets/d1963c03-37f3-4899-99af-237ecc0c6eda)

Ideal é alocar um IP para a instância, sempre que reiniciamos a instância o IP e o DNS mudam.

![aws](https://github.com/user-attachments/assets/1a03f2df-3766-4d71-933b-720d59da7a17)

![aws2](https://github.com/user-attachments/assets/fabb4bef-a33e-471f-8b2e-ee9bf608d0d0)

Não mudar nenhuma configuração, apenas alocar.

![aws3](https://github.com/user-attachments/assets/27cc0e3a-e739-406b-b7a8-677f13a0b2c2)

![aws4](https://github.com/user-attachments/assets/196680d2-5ee7-4699-9044-9dcc0fd4f630)

![aws6](https://github.com/user-attachments/assets/130e6850-3dd0-480f-8588-130e7635978f)

***

## Começando com o S3 (Simple Storage Service)

Buckets funcionam como repositório na AWS.

[Documentação](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)
