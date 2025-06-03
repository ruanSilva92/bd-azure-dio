# 🧾 Resumo: Criando uma Instância Gerenciada de SQL no Azure

### 1. Acessando o Portal do Azure

* Acesse o [portal do Azure](https://portal.azure.com).
* No menu à esquerda, selecione **"SQL do Azure"**.
* Clique em **"+ Criar"** para iniciar o processo de criação.

### 2. Selecionando a Opção de Implantação

* Na página de opções de implantação, escolha **"Instância Gerenciada SQL"**.
* Clique em **"Criar"** para prosseguir.

### 3. Configurando a Instância

* **Assinatura**: Selecione sua assinatura do Azure.
* **Grupo de Recursos**: Escolha um existente ou crie um novo.
* **Nome da Instância**: Defina um nome exclusivo para a instância.
* **Região**: Escolha a localização geográfica adequada.
* **Camada de Preço**: Selecione entre as opções disponíveis, como "Uso Geral" ou "Crítico para a Empresa".
* **Configurações de Rede**: Configure a rede virtual (VNet) e a sub-rede onde a instância será implantada.
* **Configurações de Segurança**: Defina as regras de firewall e outras configurações de segurança conforme necessário.

### 4. Revisão e Criação

* Revise todas as configurações na guia **"Examinar + criar"**.
* Após a validação, clique em **"Criar"** para iniciar a implantação da instância.

### 5. Monitorando a Implantação

* Acompanhe o progresso da implantação através do ícone de **Notificações** no portal.
* Após a conclusão, acesse o grupo de recursos para visualizar e gerenciar a instância criada.

---

## 📝 Anotações e Dicas

* **Planejamento de Rede**: Antes de criar a instância, planeje adequadamente a rede virtual e as sub-redes para garantir conectividade e segurança ideais.
* **Segurança**: Configure regras de firewall para restringir o acesso à instância apenas a endereços IP confiáveis.
* **Monitoramento**: Utilize ferramentas como o **Azure Monitor** para acompanhar o desempenho e a integridade da instância.
* **Backup e Restauração**: Aproveite os recursos integrados de backup automático e, se necessário, configure políticas de retenção adicionais.
* **Escalabilidade**: Considere as necessidades futuras de escalabilidade ao escolher a camada de preço e as configurações de desempenho.
