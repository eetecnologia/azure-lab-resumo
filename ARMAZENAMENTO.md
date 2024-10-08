## Passo a Passo para Criar uma Conta de Armazenamento no Portal Azure

### O que é uma Conta de Armazenamento?
Uma conta de armazenamento do Azure é um serviço que oferece armazenamento durável, altamente disponível e seguro para grandes volumes de dados não estruturados. Você pode usar o armazenamento para armazenar arquivos, blobs, filas e tabelas.

### Criando sua Primeira Conta de Armazenamento:

1. **Acesse o Portal do Azure:**
   * Abra seu navegador e vá para [https://portal.azure.com/](https://portal.azure.com/).
   * Faça login com sua conta do Azure.

2. **Crie um Novo Recurso:**
   * Na barra de pesquisa, digite "Conta de armazenamento" e selecione a opção.
   * Clique em "Criar".

3. **Configurar a Conta de Armazenamento:**
   * **Nome:** Defina um nome único para sua conta de armazenamento. O nome deve ser alfanumérico e conter entre 3 e 24 caracteres.
   * **Tipo de conta:** Escolha o tipo de conta de armazenamento que melhor se adapta às suas necessidades:
     * **Armazenamento geral (v2):** Oferece acesso a todos os serviços de armazenamento (blobs, filas, tabelas e arquivos).
     * **Blob:** Otimizado para armazenar grandes volumes de dados não estruturados.
     * **Arquivo:** Otimizado para compartilhar arquivos entre aplicativos em nuvem e locais.
     * **Tabela:** Otimizado para armazenar grandes quantidades de dados não estruturados no formato de tabelas.
     * **Fila:** Otimizado para armazenar mensagens que podem ser processadas assincronamente.
   * **Desempenho:** Selecione o nível de desempenho desejado para sua conta de armazenamento.
   * **Redundância:** Escolha o tipo de redundância para garantir a durabilidade dos seus dados.
   * **Rede:** Selecione a rede virtual e sub-rede onde sua conta de armazenamento será hospedada.
   * **Chave de acesso:** Gere chaves de acesso para sua conta de armazenamento.

4. **Tags:**
   * Adicione tags para organizar e filtrar suas contas de armazenamento.

5. **Revisão e criação:**
   * Revise as configurações e clique em "Criar".

**Após a criação:**

* **Acesso à conta de armazenamento:**
   * Utilize o portal do Azure para gerenciar seus recursos de armazenamento.
   * Utilize o Azure Storage Explorer para gerenciar seus recursos localmente.
   * Utilize as APIs REST para acessar seus recursos de armazenamento de forma programática.

**Dicas Adicionais:**

* **Grupos de recursos:** Organize suas contas de armazenamento em grupos de recursos para melhor gerenciamento.
* **Hierarquia de contêineres:** Organize seus dados em contêineres dentro da sua conta de armazenamento.
* **Política de vida útil:** Configure políticas de vida útil para gerenciar o ciclo de vida dos seus dados.
* **Azure Storage Explorer:** Utilize o Azure Storage Explorer para explorar e gerenciar seus recursos de armazenamento de forma visual.

**Observações:**
* Os custos variam de acordo com o tipo de conta de armazenamento, o nível de desempenho e a quantidade de dados armazenados.
* Consulte a documentação oficial da Microsoft para obter informações mais detalhadas e exemplos específicos: [[https://learn.microsoft.com/pt-br/azure/storage/common/storage-account-create](https://learn.microsoft.com/pt-br/azure/storage/common/storage-account-create)]
