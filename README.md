# Global-OS

## Descrição
Projeto de simulação de ambiente corporativo com autenticação via Active Directory, infraestrutura provisionada com Terraform no Azure, aplicação Flask integrada ao IIS via FastCGI e monitoramento com backups e recuperação automatizada.

## Integrantes
- Enzo Cunha - RM550985  
- Eduardo Gomes - RM97919  
- Gustavo Lopes - RM98887  

## Tecnologias Utilizadas
- **Terraform** (infraestrutura como código)
- **Microsoft Azure** (ambiente em nuvem)
- **Windows Server** (AD DS, IIS)
- **Active Directory**
- **Flask com LDAP3**
- **FastCGI + wfastcgi**
- **Backup Vault com Azure Recovery Services**
- **PowerShell + AppCmd**

## Infraestrutura
| Máquina | IP Público     | IP Privado  |
|--------|----------------|-------------|
| vm-ad  | 4.201.194.69   | 10.0.1.4    |
| vm-web | 4.201.185.74   | 10.0.2.4    |

**Usuário Padrão:** `azureuser`  
**Senha:** `SenhaForte@123!`

## Demonstrações em vídeo
- 🎥 **1ª Parte - Explicação:**  
  https://www.loom.com/share/8cb1c44b4bf94b3481f9fa4d61c7af54?sid=f674fd9d-dc4f-465b-8af5-364ab6fa4ff5
- 🎥 **2ª Parte - Explicação:**  
  https://www.loom.com/share/799b28a03339436e802c041f2fb07d81?sid=f7845cae-559f-45d9-bb8b-d9b5c80ef48a

## Observações
Este projeto foi construído como parte da disciplina de Global Solution com foco em alta disponibilidade, automação e segurança de acesso em rede corporativa.
