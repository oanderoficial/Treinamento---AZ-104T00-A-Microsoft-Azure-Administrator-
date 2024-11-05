# Configurar o controle de acesso baseado em função

## Anderson Bezerra Silva 
Treinamento - AZ-104T00-A Microsoft Azure Administrator (Green Tecnologia)


## 1. Identifique os recursos e casos de uso do controle de acesso baseado em função (RBAC)

- Exemplo de Estudo: Liste os principais benefícios do RBAC, como segregação de funções, controle de acesso granular e restrição de permissões.

- Passo a Passo: Leia sobre o [RBAC no Azure](https://learn.microsoft.com/pt-br/azure/role-based-access-control/overview) e entenda como ele pode ser usado em diferentes cenários.

- Tarefa Prática: Crie uma tabela com cenários fictícios onde RBAC seria útil, como acesso restrito a recursos específicos por desenvolvedores e administradores.

## 2. Liste e crie definições de função

 - Exemplo de Estudo: Descreva as permissões necessárias para um "Leitor de Recursos" personalizado que pode visualizar recursos, mas não pode fazer alterações.

-  Passo a Passo: Consulte a [documentação sobre definições de função no Azure](https://learn.microsoft.com/pt-br/azure/role-based-access-control/custom-roles) e como criar papéis personalizados.

- Tarefa Prática: No portal do Azure, navegue até o RBAC e experimente criar uma função personalizada que tenha permissões específicas. Salve e documente a função para referência futura.

## 3. Crie atribuições de função

- Exemplo de Estudo: Atribua uma função de "Leitor" a um grupo de recursos, permitindo que um usuário fictício visualize, mas não edite, recursos dentro desse grupo.

- Passo a Passo: Veja o guia de [atribuição de funções no Azure.](https://learn.microsoft.com/pt-br/azure/role-based-access-control/role-assignments-portal)

- Tarefa Prática: No portal do Azure, vá até um recurso ou grupo de recursos, escolha um usuário de teste e atribua uma função específica, como "Contribuidor" ou "Leitor". Verifique se o usuário só consegue realizar as ações permitidas.

## 4. Identifique as diferenças entre as funções RBAC do Azure e as funções do Azure Active Directory

 - Exemplo de Estudo: Crie um quadro comparativo entre as funções do Azure AD (como "Administrador Global" e "Administrador de Aplicativos") e as funções RBAC do Azure (como "Contribuidor" e "Proprietário").

- Passo a Passo: Consulte este artigo sobre as [Diferenças entre Azure RBAC e Funções do Azure AD.](https://learn.microsoft.com/pt-br/azure/role-based-access-control/role-definitions-list)

- Tarefa Prática: Liste alguns cenários onde uma função do Azure AD seria mais apropriada que uma função RBAC, e vice-versa.

## 5. Gerencie o acesso a assinaturas com o RBAC

 - Exemplo de Estudo: Defina o escopo do RBAC em uma assinatura e atribua a função de "Proprietário" a um usuário que precisa gerenciar todos os recursos.

- Passo a Passo: Acesse a [documentação para gerenciar assinaturas com o RBAC](https://learn.microsoft.com/pt-br/azure/role-based-access-control/role-assignments-portal) e entenda os limites de cada nível de escopo.

- Tarefa Prática: No Portal do Azure, atribua a função de "Proprietário" para um usuário de teste em uma assinatura. Explore como o acesso muda dependendo do escopo atribuído.

## 6. Examine as funções RBAC internas do Azure

- Exemplo de Estudo: Identifique algumas das principais funções internas do Azure RBAC, como "Contribuidor de Rede" e "Leitor de Monitoramento", e liste as permissões principais de cada uma.

- Passo a Passo: Explore a [lista de funções internas no Azure.](https://learn.microsoft.com/pt-br/azure/role-based-access-control/built-in-roles)

- Tarefa Prática: No portal, selecione um recurso específico (como uma VM ou uma rede virtual) e atribua uma das funções internas a um usuário de teste. Experimente verificar quais ações o usuário consegue realizar com essa função.



