# Configurar o Azure Policy

## Anderson Bezerra Silva 
Treinamento - AZ-104T00-A Microsoft Azure Administrator (Green Tecnologia)


## 1. Crie grupos de gerenciamento para direcionar políticas e orçamentos de gastos

- Exemplo de Estudo: Crie uma estrutura de grupos de gerenciamento para uma organização fictícia, com divisões como "Desenvolvimento", "Produção" e "Teste". Associe políticas e orçamentos específicos para cada grupo.

- Passo a Passo: Consulte a documentação sobre [Gerenciamento de Grupos no Azure.](https://learn.microsoft.com/pt-br/azure/governance/management-groups/overview)

- Tarefa Prática: No portal do Azure, crie um grupo de gerenciamento e associe-o a uma assinatura. Em seguida, aplique uma política de restrição de custos e observe como a estrutura de hierarquia é criada para gerenciamento de políticas e orçamento.

## 2. Implementar o Azure Policy com definições de política e iniciativa

- Exemplo de Estudo: Defina uma política que restrinja o tipo de recurso que pode ser criado (por exemplo, permitir apenas VMs de tamanho pequeno) e agrupe essa política em uma iniciativa para governança de recursos.

- Passo a Passo: Acesse a página de [Azure Policy](https://learn.microsoft.com/pt-br/azure/governance/policy/overview) para entender a criação de políticas e como usar iniciativas.

- Tarefa Prática: Crie uma definição de política para limitar a criação de recursos específicos e, em seguida, crie uma iniciativa que contenha essa política. No portal do Azure, aplique a iniciativa a um grupo de recursos para verificar como as restrições funcionam na prática.


## 3. Definir o escopo das políticas do Azure e determinar a conformidade

- Exemplo de Estudo: Escolha um grupo de recursos e defina uma política para verificar a conformidade de requisitos, como criptografia de discos em máquinas virtuais.

- Passo a Passo: Consulte a [documentação de Escopos e Conformidade no Azure Policy](https://learn.microsoft.com/pt-br/azure/governance/policy/concepts/effect-basics) para entender como definir o escopo de políticas e verificar a conformidade.

- Tarefa Prática: No Portal do Azure, defina uma política para um escopo específico, como uma assinatura ou um grupo de recursos, e visualize o relatório de conformidade. Experimente aplicar uma política de auditoria e observe os recursos que não estão em conformidade.


