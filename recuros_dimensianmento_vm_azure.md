# Configurando Recursos e Dimensionamento em Máquinas Virtuais no Microsoft Azure

## Descrição
Este projeto descreve como configurar recursos e ajustar o dimensionamento das **Máquinas Virtuais (VMs)** no **Microsoft Azure**. O Azure permite a criação de VMs com recursos escaláveis, ajustando CPU, memória e armazenamento de acordo com a demanda do cliente.

## Objetivos
- Configurar corretamente os recursos de CPU, memória e armazenamento das VMs.
- Implementar dimensionamento automático (Auto-Scaling) para otimizar custos e desempenho.

## Passos para Configurar e Dimensionar uma Máquina Virtual no Azure

1. **Acessar o Portal Azure**: 
   - Faça login no [Azure Portal](https://portal.azure.com) e vá para a seção **Máquinas Virtuais**.
   
2. **Configuração de Recursos**:
   - Selecione a VM ou crie uma nova.
   - Defina o tamanho da VM (número de vCPUs, memória RAM, disco de armazenamento).
   - Para ajustar o tamanho de uma VM existente, vá até **Configurações > Tamanho** e selecione a nova configuração desejada.

3. **Dimensionamento Automático (Auto-Scaling)**:
   - Habilite o dimensionamento automático em **Configurações > Auto-Scaling**.
   - Defina políticas para escalonamento de acordo com o uso de CPU, memória ou métricas personalizadas.
   - Configure limites mínimo e máximo para o número de instâncias, permitindo que a infraestrutura se ajuste às variações de demanda.

4. **Monitoramento e Ajustes**:
   - Monitore o desempenho da VM através do **Azure Monitor**.
   - Realize ajustes nos recursos conforme necessário para otimizar o desempenho ou reduzir custos.

## Exemplos de Uso
- **Serviços Web de Alta Demanda**: Dimensionamento automático para garantir que o sistema suporte picos de tráfego sem perder desempenho.
- **Ambientes de Desenvolvimento e Teste**: Utilização de VMs de menor porte para desenvolvimento, ajustando o tamanho conforme necessário para testes de desempenho.

## Autor
- [Thiago Valentim](https://github.com/thvcorreia)

## Referências
- [Documentação Oficial do Azure sobre Máquinas Virtuais](https://docs.microsoft.com/pt-br/azure/virtual-machines/)
- [Documentação sobre Dimensionamento Automático no Azure](https://docs.microsoft.com/pt-br/azure/virtual-machine-scale-sets/)

