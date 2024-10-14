# Ferramentas de Implantação no Microsoft Azure

## Descrição
Este projeto apresenta as principais **ferramentas de implantação** no **Microsoft Azure** que facilitam a automação e gerenciamento de infraestrutura e aplicações na nuvem. Elas permitem maior agilidade na entrega de serviços e infraestrutura, mantendo controle e segurança.

## Objetivos
- Entender as principais ferramentas de implantação no Azure.
- Automatizar a criação e gerenciamento de recursos com eficiência.
- Usar pipelines de CI/CD para agilizar o desenvolvimento e implantação de software.

## Principais Ferramentas de Implantação

1. **Azure Resource Manager (ARM)**:
   - O **ARM** é um serviço que permite criar, atualizar e deletar recursos no Azure. Ele usa templates JSON para definir a infraestrutura como código, facilitando o gerenciamento de recursos.
   - Exemplo: Implantar um conjunto de VMs, redes e armazenamento usando um template ARM.

2. **Azure DevOps**:
   - Ferramenta de CI/CD (integração contínua/entrega contínua) que permite a automação de pipelines de build e deploy.
   - Exemplo: Automatizar a implantação de uma aplicação web com Azure DevOps Pipelines.

3. **Terraform**:
   - Ferramenta de código aberto que permite gerenciar a infraestrutura através de um código declarativo. O **Terraform** funciona tanto em ambientes on-premise quanto em nuvens públicas como o Azure.
   - Exemplo: Usar o Terraform para definir e provisionar uma infraestrutura completa no Azure.

4. **Azure CLI**:
   - A **Azure Command-Line Interface (CLI)** permite a interação direta com os serviços do Azure por meio do terminal. Você pode gerenciar recursos, configurar ambientes e implantar aplicativos de maneira rápida e eficiente.
   - Exemplo: Criar uma VM e configurá-la diretamente pelo terminal.

5. **GitHub Actions para Azure**:
   - Automatize fluxos de trabalho diretamente do **GitHub**. Usando **GitHub Actions**, é possível criar pipelines para CI/CD que integram-se facilmente com os serviços do Azure.
   - Exemplo: Automatizar o deploy de uma aplicação web para o Azure diretamente do repositório GitHub.

## Como Configurar e Utilizar

### Azure DevOps Pipeline
1. **Criar um projeto no Azure DevOps**.
2. **Configurar um pipeline de build** para compilar e testar seu código.
3. **Adicionar um pipeline de release** para automatizar o deploy para os serviços do Azure.

### Terraform
1. **Instalar o Terraform** em sua máquina.
2. Criar um arquivo `.tf` com a definição da infraestrutura desejada.
3. **Executar os comandos** `terraform init`, `terraform plan` e `terraform apply` para provisionar os recursos.

## Exemplos de Uso
- **Implantação de Infraestrutura Automatizada**: Usar ARM templates ou Terraform para provisionar redes virtuais, VMs, e bancos de dados automaticamente.
- **CI/CD Automatizado**: Usar Azure DevOps ou GitHub Actions para criar pipelines de desenvolvimento que automaticamente deployam novas versões de software no Azure.

## Autor
- [Thiago Valentim](https://github.com/thvcorreia)

## Referências
- [Documentação Oficial do Azure Resource Manager](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/)
- [Documentação do Azure DevOps](https://docs.microsoft.com/pt-br/azure/devops/)
- [Terraform no Azure](https://learn.hashicorp.com/terraform/azure/intro)
