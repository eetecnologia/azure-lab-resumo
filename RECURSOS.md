## Manual para Criação de Grupos de Recursos no Portal do Azure

### O que são Grupos de Recursos?
Um grupo de recursos é um contêiner lógico que permite organizar seus recursos do Azure. Ao agrupar recursos relacionados, você pode gerenciá-los, implantá-los e monitorá-los como uma única unidade. Isso facilita o controle de custos, o gerenciamento de acesso e a organização de sua infraestrutura na nuvem.

### Por que usar Grupos de Recursos?
* **Organização:** Agrupa recursos por projeto, ambiente ou equipe.
* **Gerenciamento:** Permite implantar, atualizar e excluir recursos em conjunto.
* **Controle de acesso:** Facilita a definição de permissões para diferentes grupos de usuários.
* **Gerenciamento de custos:** Ajuda a rastrear os custos associados a cada grupo.

### Criando um Grupo de Recursos
1. **Acesse o Portal do Azure:**
   * Abra seu navegador e vá para [https://portal.azure.com/](https://portal.azure.com/).
   * Faça login com sua conta do Azure.

2. **Navegue até Grupos de Recursos:**
   * Na barra de pesquisa, digite "Grupos de recursos" e selecione a opção.

3. **Crie um Novo Grupo de Recursos:**
   * Clique em "Criar".
   * Preencha as informações solicitadas:
     * **Assinatura:** Selecione a assinatura do Azure onde você deseja criar o grupo.
     * **Grupo de recursos:** Digite um nome único para o grupo.
     * **Região:** Escolha a região onde seus recursos serão hospedados.
     * **Tags (opcional):** Adicione tags para categorizar e filtrar seus grupos.

4. **Revise e Crie:**
   * Revise as informações e clique em "Criar".

### Abrindo um Grupo de Recursos Existente
* Na página "Grupos de recursos", localize o grupo desejado e clique nele.

### Gerenciando um Grupo de Recursos
Dentro de um grupo de recursos, você pode:
* **Visualizar recursos:** Veja todos os recursos que fazem parte do grupo.
* **Adicionar recursos:** Crie novos recursos e adicione-os ao grupo.
* **Excluir recursos:** Remova recursos do grupo.
* **Mover recursos:** Transfira recursos para outro grupo.
* **Gerenciar tags:** Adicione, edite ou remova tags.
* **Controlar acesso:** Defina permissões para diferentes usuários ou grupos.

### Dicas Adicionais
* **Use nomes descritivos:** Escolha nomes que reflitam o propósito do grupo.
* **Organize por projeto ou ambiente:** Crie grupos separados para diferentes projetos ou ambientes (desenvolvimento, teste, produção).
* **Utilize tags:** As tags permitem filtrar e organizar seus grupos de forma mais granular.
* **Considere a hierarquia:** Para grandes projetos, você pode criar grupos de recursos aninhados.

### Considerações Importantes
* **Excluir um grupo de recursos exclui todos os recursos dentro dele.** Tenha cuidado ao excluir grupos.
* **Os grupos de recursos não podem ser renomeados.** Se precisar mudar o nome, crie um novo grupo e mova os recursos.

### Conclusão
Os grupos de recursos são uma ferramenta poderosa para organizar e gerenciar sua infraestrutura no Azure. Ao seguir estas etapas e dicas, você poderá otimizar a utilização da nuvem e garantir a escalabilidade e a flexibilidade dos seus projetos.
