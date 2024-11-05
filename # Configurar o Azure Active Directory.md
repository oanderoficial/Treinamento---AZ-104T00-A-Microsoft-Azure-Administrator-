# Configurar o Azure Active Directory
## Anderson Bezerra Silva 
Treinamento - AZ-104T00-A Microsoft Azure Administrator (Green Tecnologia)


## 1. Definir os conceitos do Azure AD, incluindo identidades, contas e locatários

- Exemplo de Estudo: Crie um diagrama simples que mostre a estrutura de um locatário do Azure AD, incluindo usuários, grupos e identidades externas.

- Passo a Passo: Leia a documentação sobre [Azure Active Directory Tenants and Users](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/whatis)

- Tarefa Prática: No Portal Azure, acesse Azure Active Directory > Usuários e crie um usuário simulado para entender como funciona o gerenciamento de identidades.

## 2. Descrever os recursos do Azure AD para suportar diferentes configurações


- Exemplo de Estudo: Liste os principais recursos do Azure AD, como MFA (Autenticação Multifator), identidade híbrida e grupos dinâmicos.

- Passo a Passo: Consulte a página de funcionalidades do [Azure Active Directory](https://www.microsoft.com/pt-br/security/business/identity-access/microsoft-entra-id) e identifique pelo menos três recursos que poderiam ser aplicados em uma configuração de identidade.

- Tarefa Prática: Habilite o MFA para uma conta de teste no Azure AD e explore as configurações avançadas de segurança. [Configuração MFA no Azure AD.](https://learn.microsoft.com/pt-br/entra/identity/authentication/tutorial-enable-azure-mfa)

## 3. Entender as diferenças entre o Azure AD e o AD DS (Active Directory Domain Services)

- Exemplo de Estudo: Crie uma tabela comparativa entre Azure AD e AD DS, destacando diferenças em propósito, arquitetura e gerenciamento.

- Passo a Passo: Leia este artigo sobre [Diferenças entre Azure AD e AD DS.](https://learn.microsoft.com/pt-br/azure/active-directory/fundamentals/compare)

- Tarefa Prática: Descreva um cenário em que o Azure AD seria mais adequado que o AD DS e vice-versa.

## 4. Escolher entre as edições com suporte do Azure AD

- Exemplo de Estudo: Identifique as características de cada edição (Free, Premium P1, Premium P2) e crie um quadro com os principais recursos de cada uma.

- Passo a Passo: Acesse a comparação de edições do [Azure AD.](https://azure.microsoft.com/pricing/details/active-directory/)

- Tarefa Prática: Consulte a tabela de comparação e escolha qual edição você recomendaria para uma empresa pequena com necessidade de segurança básica e por quê.

## 5. Implementar o recurso de ingresso do Azure AD

- Exemplo de Estudo: Configure um dispositivo para ingressar no Azure AD usando uma conta corporativa.

- Passo a Passo: Siga o tutorial para configurar o [Azure AD Join para Windows 10.](https://learn.microsoft.com/pt-br/azure/active-directory/devices/howto-vm-joined-device)

- Tarefa Prática: Conecte uma máquina virtual (ou seu próprio dispositivo, se possível) ao Azure AD e explore as configurações de login com a conta corporativa.

## 6. Usar o recurso de redefinição de senha self-service do Azure AD

- Exemplo de Estudo: Ative a redefinição de senha self-service (SSPR) para um usuário de teste e simule o processo de redefinição.

- Passo a Passo: Consulte o guia sobre [Configuração de redefinição de senha self-service.](https://learn.microsoft.com/pt-br/entra/identity/authentication/concept-sspr-howitworks)

- Tarefa Prática: Habilite o SSPR no Azure AD para uma conta de teste e use a funcionalidade para redefinir a senha de forma autônoma.


