## Passo a Passo para Criar uma Máquina Virtual no Portal Azure

**O que é uma Máquina Virtual (VM)?**
Uma máquina virtual é um computador virtual que roda dentro de um ambiente de computação em nuvem. Ela oferece a flexibilidade de um servidor físico, mas com a agilidade e escalabilidade da nuvem.

**Criando sua Primeira VM:**

1. **Acesse o Portal do Azure:**
   * Abra seu navegador e vá para [https://portal.azure.com/](https://portal.azure.com/).
   * Faça login com sua conta do Azure.

2. **Crie um Novo Recurso:**
   * Na barra de pesquisa, digite "Máquinas virtuais" e selecione a opção.
   * Clique em "Criar".

3. **Selecione um Plano:**
   * **Básico:** Ideal para desenvolvimento e testes.
   * **Padrão:** Oferece mais opções de personalização e desempenho.
   * **Outros:** Explore outras opções, como máquinas virtuais especializadas para workloads específicas.

4. **Configure a Máquina Virtual:**
   * **Nome:** Defina um nome para sua máquina virtual.
   * **Região:** Escolha a região onde sua VM será hospedada.
   * **Imagem:** Selecione a imagem do sistema operacional desejado (Windows, Linux, etc.).
   * **Tamanho:** Escolha o tamanho da máquina virtual (número de núcleos, memória RAM, etc.).
   * **Usuário e senha:** Crie um usuário e senha para acessar a VM.

5. **Discos:**
   * **Disco do sistema operacional:** Escolha o tamanho do disco para o sistema operacional.
   * **Discos de dados:** Adicione discos adicionais para armazenamento se necessário.

6. **Redes:**
   * **Rede virtual:** Selecione uma rede virtual existente ou crie uma nova.
   * **Sub-rede:** Escolha ou crie uma sub-rede dentro da rede virtual.
   * **Endereço IP público:** Decida se sua VM terá um endereço IP público para acesso externo.

7. **Gerenciamento:**
   * **Monitoramento:** Configure alertas e diagnóstico para monitorar a saúde da sua VM.
   * **Disponibilidade:** Configure a disponibilidade da sua VM (zonas de falha, conjuntos de disponibilidade).
   * **Autenticação:** Configure opções de autenticação adicionais, como chaves SSH.

8. **Tags:**
   * Adicione tags para organizar e filtrar suas máquinas virtuais.

9. **Revisão e criação:**
   * Revise as configurações e clique em "Criar".

**Após a criação:**

* **Acesso à VM:**
   * **RDP (Windows):** Use o protocolo RDP para se conectar à sua máquina virtual Windows.
   * **SSH (Linux):** Use o protocolo SSH para se conectar à sua máquina virtual Linux.
   * **Bastion:** Utilize o serviço Bastion do Azure para se conectar à sua VM sem precisar de uma regra de entrada na rede virtual.

**Dicas Adicionais:**

* **Grupos de recursos:** Organize suas máquinas virtuais em grupos de recursos para melhor gerenciamento.
* **Discos gerenciados:** Utilize discos gerenciados para maior flexibilidade e escalabilidade.
* **Network Security Groups (NSGs):** Configure NSGs para controlar o tráfego de rede para sua VM.
* **Azure Marketplace:** Explore o Azure Marketplace para encontrar imagens de sistema operacional personalizadas e aplicativos pré-configurados.

**Observações:**
* Os custos variam de acordo com a região, o tamanho da máquina virtual e os serviços adicionais utilizados.
* Consulte a documentação oficial da Microsoft para obter informações mais detalhadas e exemplos específicos: [https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal](https://learn.microsoft.com.br/pt-br/azure/virtual-machines/windows/quick-create-portal)
