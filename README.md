# Criando Máquinas Virtuais no Microsoft Azure

Este guia descreve o processo de criação de máquinas virtuais (VMs) no Microsoft Azure, desde a configuração inicial até a conclusão da implantação.

## Índice

1. [Introdução](#introdução)
2. [Acessando o Portal do Azure](#acessando-o-portal-do-azure)
3. [Criando uma Máquina Virtual](#criando-uma-máquina-virtual)
   - [Passo 1: Acessar a Seção de Máquinas Virtuais](#passo-1-acessar-a-seção-de-máquinas-virtuais)
   - [Passo 2: Configurações Básicas](#passo-2-configurações-básicas)
   - [Passo 3: Tamanho da Máquina Virtual](#passo-3-tamanho-da-máquina-virtual)
   - [Passo 4: Configurações de Disco](#passo-4-configurações-de-disco)
   - [Passo 5: Configurações de Rede](#passo-5-configurações-de-rede)
   - [Passo 6: Revisão e Criação](#passo-6-revisão-e-criação)
4. [Gerenciando a Máquina Virtual](#gerenciando-a-máquina-virtual)
5. [Conclusão](#conclusão)

## Introdução

As Máquinas Virtuais no Azure permitem que você execute aplicações em ambientes isolados, simulando servidores físicos. Este guia explica como criar uma VM a partir do zero.

## Acessando o Portal do Azure

1. **Acesse o portal do Azure**:
   - Visite o site [https://portal.azure.com](https://portal.azure.com).
   - Insira suas credenciais (email e senha) para fazer login.

## Criando uma Máquina Virtual

### Passo 1: Acessar a Seção de Máquinas Virtuais

1. No painel de navegação à esquerda, clique em "Todos os Serviços".
2. No campo de busca, digite "Máquinas Virtuais" e selecione a opção "Máquinas Virtuais" em "Computação".
3. Clique em "Adicionar" ou "Criar" para iniciar o processo de criação de uma nova máquina virtual.

### Passo 2: Configurações Básicas

1. **Assinatura e Grupo de Recursos**:
   - Selecione a assinatura correta e um grupo de recursos existente ou crie um novo.

2. **Detalhes da Instância**:
   - Insira o nome da máquina virtual.
   - Escolha a região onde a VM será hospedada.
   - Selecione a disponibilidade, se necessário (opcional).

3. **Imagens e Sistema Operacional**:
   - Selecione a imagem do sistema operacional que deseja usar (por exemplo, Windows Server, Ubuntu, etc.).

4. **Tipo de Autenticação**:
   - Escolha entre senha ou chave SSH para autenticação.

### Passo 3: Tamanho da Máquina Virtual

1. Escolha o tamanho da máquina virtual com base nos requisitos de CPU, memória e armazenamento. Azure oferece várias opções, desde VMs pequenas e econômicas até instâncias maiores e mais potentes.

### Passo 4: Configurações de Disco

1. Selecione o tipo de disco de SO (SSD, HDD).
2. Adicione discos adicionais, se necessário, para armazenamento de dados.

### Passo 5: Configurações de Rede

1. **Rede Virtual e Sub-rede**:
   - Escolha uma rede virtual existente ou crie uma nova.
   - Selecione a sub-rede desejada.

2. **Endereço IP Público**:
   - Escolha se a VM terá um endereço IP público.

3. **Grupo de Segurança de Rede (Firewall)**:
   - Configure regras de entrada e saída, como permitir acesso via RDP (para Windows) ou SSH (para Linux).

### Passo 6: Revisão e Criação

1. **Revisar Configurações**:
   - Verifique todas as configurações feitas e clique em "Revisar + criar".
   
2. **Implantação**:
   - Após a revisão, clique em "Criar" para iniciar o processo de implantação da máquina virtual. A criação pode levar alguns minutos.

## Gerenciando a Máquina Virtual

1. **Acessar a VM**:
   - Após a criação, você pode acessar a VM utilizando RDP, SSH ou outras ferramentas de gerenciamento remoto.

2. **Configurações Adicionais**:
   - Acesse o painel da VM para ajustar configurações, monitorar desempenho e gerenciar recursos associados.

## Conclusão

Seguindo este guia, você será capaz de criar e configurar uma máquina virtual no Microsoft Azure, ajustando as opções para atender às suas necessidades específicas. Explore as opções avançadas de gerenciamento para maximizar o desempenho e a segurança da sua VM.
