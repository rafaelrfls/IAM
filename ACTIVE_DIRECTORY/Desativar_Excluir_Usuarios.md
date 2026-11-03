1. Desative a conta (Disable Account):
	• Impede que o usuário faça novos logins no domínio.
	• Atenção: Desativar a conta não encerra sessões que já estavam abertas. É preciso derrubar as sessões ativas manualmente (via comando logoff ou no Gerenciador 
  de Tarefas do servidor/máquina).

2. Remova dos grupos de privilégio:
	• Retire o usuário de todos os grupos de segurança, especialmente de administradores ou grupos com acessos sensíveis.

3. Mova para uma OU específica ("OU de Desativados"):
	• Em vez de um grupo, a prática de mercado mais aceita é mover o objeto da conta para uma Unidade Organizacional (OU) chamada Desativados ou Inativos.
	• Isso facilita a aplicação de bloqueios em GPOs (Group Policy Objects) específicas (como bloquear logon interativo ou restrições adicionais) e mantém a 
  organização limpa nas OUs de trabalho.

4. Quando excluir permanentemente?
	• A exclusão definitiva só deve ocorrer após um período de retenção definido pela política da empresa (por exemplo, após 30, 60 ou 90 dias desativado).
	• Esse prazo garante que, se algum arquivo esquecido, e-mail arquivado ou processo pendente do ex-colaborador precisar ser recuperado, os dados ainda estarão acessíveis.
