# Dominando o Armazenamento no Microsoft Azure

## Descrição
Este projeto aborda como utilizar e gerenciar eficientemente os diferentes serviços de armazenamento no **Microsoft Azure**. O Azure oferece uma variedade de opções de armazenamento para diferentes necessidades, como **Blobs**, **Discos Gerenciados**, **Armazenamento de Arquivos**, e muito mais.

## Objetivos
- Compreender e configurar os principais tipos de armazenamento no Azure.
- Implementar políticas de retenção de dados e gerenciamento de custos.
- Utilizar diferentes tipos de armazenamento para cenários de backup e recuperação.

## Tipos de Armazenamento no Azure

1. **Blob Storage**:
   - Ideal para armazenamento de objetos em grande escala, como arquivos de mídia ou backups.
   - Configure acessos, níveis de redundância (LRS, GRS) e políticas de lifecycle para gerenciar o ciclo de vida dos dados.

2. **Discos Gerenciados**:
   - Usados para fornecer armazenamento persistente para **Máquinas Virtuais**.
   - Escolha entre tipos de discos como **SSD** e **HDD**, ajustando o desempenho conforme necessário.

3. **File Storage**:
   - Oferece um sistema de arquivos compartilhado acessível por meio do protocolo **SMB**.
   - Ideal para cenários em que múltiplas VMs precisam compartilhar arquivos.

4. **Queue Storage**:
   - Usado para armazenar mensagens para comunicação entre componentes distribuídos de aplicações.

## Como Configurar Armazenamento no Azure

1. **Acessar o Azure Portal**: Entre no [Azure Portal](https://portal.azure.com) e selecione **Storage Accounts**.
2. **Criar uma Conta de Armazenamento**:
   - Defina o nome, região e nível de redundância.
   - Escolha o tipo de armazenamento desejado (Blob, File, Queue).
3. **Gerenciar Dados**:
   - Use ferramentas como **Azure Storage Explorer** ou APIs para gerenciar e acessar os dados armazenados.
4. **Política de Retenção**:
   - Configure políticas de retenção e gerenciamento de custos para otimizar o uso do armazenamento.

## Exemplos de Uso
- **Armazenamento de Backups**: Utilize **Blob Storage** para armazenar backups de grandes volumes de dados.
- **Sistemas Distribuídos**: Use **Queue Storage** para comunicação entre componentes de sistemas distribuídos.

## Autor
- [Thiago Valentim](https://github.com/thvcorreia)

## Referências
- [Documentação Oficial do Azure sobre Armazenamento](https://docs.microsoft.com/pt-br/azure/storage/)
- [Azure Storage Explorer](https://azure.microsoft.com/pt-br/features/storage-explorer/)

