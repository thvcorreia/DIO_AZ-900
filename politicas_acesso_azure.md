# Gerenciando Políticas de Acessos no Microsoft Azure

## Descrição
Este projeto explora como configurar e gerenciar **políticas de acesso** no **Microsoft Azure** para garantir que os usuários e grupos tenham o nível adequado de permissão para acessar recursos. O uso de **Role-Based Access Control (RBAC)** e **Azure Policy** garante conformidade e segurança no gerenciamento de acessos.

## Objetivos
- Configurar e gerenciar permissões de acesso com base em funções.
- Implementar políticas de segurança para conformidade e controle.
- Garantir que apenas usuários autorizados possam acessar e gerenciar recursos no Azure.

## Ferramentas e Políticas de Acesso no Azure

1. **Controle de Acesso Baseado em Funções (RBAC)**:
   - O RBAC permite atribuir funções específicas para usuários, grupos e serviços, garantindo que apenas pessoas com permissões necessárias possam acessar e gerenciar recursos.
   - Atribuir funções como **Leitor**, **Colaborador** e **Proprietário** aos recursos.
   
2. **Azure Active Directory (Azure AD)**:
   - Use o **Azure AD** para gerenciar identidades e autenticação. Ele permite configurar Single Sign-On (SSO), autenticação multifator (MFA) e a integração com outras aplicações.

3. **Azure Policy**:
   - Crie e aplique políticas para garantir que os recursos estejam em conformidade com as melhores práticas. 
   - As políticas podem restringir o tipo de recurso que pode ser criado, como configurar limites de localidade ou definir os tipos de VMs permitidos.

4. **Blueprints do Azure**:
   - Facilite a implantação de políticas e papéis de segurança em uma arquitetura, garantindo que toda a infraestrutura siga os padrões corporativos.

## Como Configurar Políticas de Acesso

1. **Acessar o Portal Azure**:
   - Entre no [Azure Portal](https://portal.azure.com) e vá para **Azure Active Directory** ou **Controle de Acesso (IAM)** para configurar permissões.
   
2. **Configurar RBAC**:
   - Em **Controle de Acesso (IAM)** de um recurso, clique em **Adicionar função**.
   - Selecione a função desejada (ex: **Leitor**, **Colaborador**, **Proprietário**) e atribua a um usuário ou grupo.
   
3. **Criar Políticas com Azure Policy**:
   - No portal, vá para **Azure Policy** e crie uma política.
   - Defina a política de conformidade (ex: restrições de tipo de recurso ou localidade) e aplique-a aos grupos de recursos.

4. **Monitoramento de Políticas**:
   - Use o **Azure Policy** e o **Azure Monitor** para verificar se as políticas estão sendo seguidas e se há violações de conformidade.

## Exemplos de Uso
- **Políticas de Segurança**: Implemente uma política para garantir que todas as VMs criadas tenham criptografia habilitada.
- **RBAC para Controle de Acesso**: Configure o RBAC para que apenas administradores de rede possam modificar configurações de rede, enquanto desenvolvedores têm acesso limitado.

## Autor
- [Thiago Valentim](https://github.com/thvcorreia)

## Referências
- [Documentação Oficial sobre RBAC no Azure](https://docs.microsoft.com/pt-br/azure/role-based-access-control/)
- [Documentação sobre Azure Policy](https://docs.microsoft.com/pt-br/azure/governance/policy/)

