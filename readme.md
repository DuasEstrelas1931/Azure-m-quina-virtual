# Como Criar uma Máquina Virtual no Azure

## Pré-requisitos
1. **Conta no Microsoft Azure** – Certifique-se de ter uma conta ativa no Azure. Se ainda não tiver, você pode se registrar em [azure.microsoft.com](https://azure.microsoft.com/).
2. **Acesso ao Portal do Azure** – Acesse o portal do Azure [aqui](https://portal.azure.com/).

## Passo 1: Acesse o Portal do Azure
- Entre no [Portal do Azure](https://portal.azure.com) usando suas credenciais da conta.

## Passo 2: Criação de uma Máquina Virtual
1. No menu lateral esquerdo, clique em **Máquinas Virtuais**.
2. Clique em **+ Criar** e selecione **Máquina Virtual**.

## Passo 3: Configuração Básica da Máquina Virtual
1. **Assinatura**: Selecione a assinatura desejada.
2. **Grupo de Recursos**: Selecione um grupo de recursos existente ou crie um novo clicando em **Criar novo**.
3. **Nome da Máquina Virtual**: Dê um nome à sua máquina virtual.
4. **Região**: Selecione a região geográfica onde sua VM será implantada (por exemplo, **East US**).
5. **Imagem**: Escolha o sistema operacional da máquina virtual, como **Windows Server 2019** ou **Ubuntu 20.04 LTS**.
6. **Tamanho**: Escolha o tamanho da VM com base nas necessidades de processamento e memória.

## Passo 4: Configuração de Conta de Administrador
1. **Nome de Usuário**: Defina um nome de usuário para acessar a VM.
2. **Autenticação**: Escolha entre senha ou chave SSH para autenticação:
   - Se optar por senha, insira e confirme a senha.
   - Se optar por chave SSH, forneça sua chave pública SSH.

## Passo 5: Configurações de Rede
1. **Rede Virtual**: Selecione uma rede virtual existente ou crie uma nova.
2. **Sub-rede**: Escolha ou crie uma sub-rede.
3. **IP Público**: Deixe configurado para que a VM tenha um endereço IP público.
4. **Portas de Entrada**: Selecione as portas que deseja abrir, como RDP (porta 3389) para Windows ou SSH (porta 22) para Linux.

## Passo 6: Discos
1. Escolha o tipo de disco que deseja usar:
   - **Disco gerenciado padrão** (mais econômico).
   - **Disco SSD premium** (mais rápido).
2. Se necessário, você pode adicionar discos adicionais nas configurações avançadas.

## Passo 7: Revisar e Criar
1. Revise todas as configurações da sua máquina virtual.
2. Clique em **Revisar e Criar**.
3. Após a validação, clique em **Criar** para iniciar a criação da sua VM.

## Passo 8: Acessando a Máquina Virtual
1. Quando a VM estiver pronta, vá para a seção **Máquinas Virtuais** e selecione a máquina recém-criada.
2. Clique em **Conectar** e siga as instruções para se conectar via **RDP** (para Windows) ou **SSH** (para Linux).

## Conclusão
Você criou com sucesso uma máquina virtual no Azure! Agora pode gerenciar e usar a VM conforme suas necessidades.

---

**Referências:**
- [Documentação do Azure sobre Máquinas Virtuais](https://docs.microsoft.com/pt-br/azure/virtual-machines/)
