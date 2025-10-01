C- Protege os recursos do Azure de exclusão ou modificação acidental
- Gerenciar bloqueios na assinatura, grupo de recursos ou níveis de recursos individuais dentro do Portal do Azure 

Você pode definir bloqueios que impedem exclusões ou modificações. No portal, os bloqueios são chamados de **Excluir** e **Somente leitura**. Na linha de comando, esses bloqueios são chamados de **CanNotDelete** e **ReadOnly**.

- **CanNotDelete** significa que os usuários autorizados ainda poderão ler e modificar um recurso, mas não poderão excluí-lo.
- **ReadOnly** significa que os usuários autorizados poderão ler um recurso, mas não poderão excluir ou atualizá-lo. Aplicar esse bloqueio é semelhante a restringir todos os usuários autorizados para as permissões concedidas pela função **Leitor**.