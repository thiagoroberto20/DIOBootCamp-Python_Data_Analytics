Etapas:

1. Verificação de Cabeçalhos e Tipos de Dados:
 *  tipos de dados das colunas estão corretos

2. Modificação de Valores Monetários:
 * salary foi convertido para  "double preciso" para garantir a precisão dos cálculos.

3.  Análise de Valores Nulos:
  * Foi removido valores nulos da tabela employee

4.  Identificação de Gerentes:
  * Foi identificado funcionario com valor nulo na coluna "Super_ssn". Ele não tinha gerente e o valor nulo foi removido.

5. Separação de Colunas Complexas:
  * Tabela employee foi divido a coluna de endereço(rua, bairro, cidade e UF)	

6. Mescla de Consultas:
 * employee_department

7. Mescla de Nomes:
 * foi mesclado Nome e Sobrenome

8. Mescla de Departamentos e Localização:
 * "Departamento-Localização" 

9. Justificativa para Mescla:
  * A mescla é mais adequada que a atribuição por causa da necessidade de manter a unicidade das combinações departamento-localização.
    A atribuição resultaria em duplicatas caso existissem departamentos com o mesmo nome em diferentes localizações. 

10. Agrupamento por Gerente:
  * Foi Agrupado os daos por  "Manager_id" 

11. Eliminação de Colunas Desnecessárias:
  * Foi eliminado colunas desnecessárias de cada tabela 
