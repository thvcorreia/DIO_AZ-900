# Criando Máquinas Virtuais no Microsoft Azure

## Descrição
Este projeto demonstra como criar e configurar **Máquinas Virtuais (VMs)** no **Microsoft Azure**. As VMs são essenciais para hospedar aplicativos, testar ambientes e executar diversas cargas de trabalho em uma infraestrutura escalável e segura.

## Objetivos
- Criar uma Máquina Virtual no Azure.
- Configurar recursos de armazenamento, rede e segurança.
- Acessar e gerenciar a VM após a criação.

## Passos para Criar uma Máquina Virtual no Azure
1. **Acessar o Portal Azure**: Faça login no [Azure Portal](https://portal.azure.com).
2. **Ir até a seção "Máquinas Virtuais"**:
   - No menu lateral, selecione **Máquinas Virtuais** e, em seguida, clique em **Adicionar** para criar uma nova.
3. **Configurar a Máquina Virtual**:
   - **Nome**: Defina o nome da VM.
   - **Região**: Escolha a região em que deseja hospedar a VM.
   - **Imagem**: Selecione o sistema operacional da máquina (ex: Windows, Linux).
   - **Tamanho**: Selecione o tamanho da VM (número de CPUs, memória).
4. **Configurar as Opções de Rede e Segurança**:
   - **Rede**: Configure a Virtual Network (VNet) e os grupos de segurança.
   - **Autenticação**: Escolha entre senha ou chave SSH.
5. **Revisar e Criar**: Revise todas as configurações e clique em **Criar**. A VM será provisionada e estará pronta para uso em poucos minutos.

## Acessando a Máquina Virtual
- Após a criação, você pode acessar a VM via **RDP** (para Windows) ou **SSH** (para Linux).
- Use o endereço IP público da VM e as credenciais criadas durante a configuração.

## Exemplos de Uso
- **Ambientes de Desenvolvimento**: Criação de ambientes para desenvolvimento e teste.
- **Hospedagem de Aplicações**: Usar a VM para hospedar aplicativos ou websites.
- **Treinamento e Laboratórios**: Criar ambientes isolados para treinamento e laboratórios.

## Autor
- [Thiago Valentim](https://github.com/thvcorreia)

## Referências
- [Documentação Oficial do Azure sobre Máquinas Virtuais](https://docs.microsoft.com/pt-br/azure/virtual-machines/)
