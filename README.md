
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




