# Cientista-de-dados-Modelagem-de-bom-ou-mau-pagadores.
Utilizando a linguagem python.
1) Faça uma indicadora de se o cliente está em default em cada uma das marcações (mes_00 a mes_24). Dica: você pode utilizar o método .isin() do Pandas. Consulte a documentação caso necessário.

2) 'bons' e 'maus' ao longo de todos os 24 meses de desempenho
Marque para cada cliente se ele teve pelo menos um episódio de default entre o mês 0 e o mês 24. Dica: o método sum() pode ajudar. Caso precise, consulte a documentação e procure pelo argumento axis, você viu outros métodos que possuem esse argumento também. Tendo o número de meses em default de cada cliente, basta marcar True para todos aqueles que possuem pelo menos 1 mês em default e False para os demais.

3) Marcando proponentes expostos ao risco de crédito
Marcando proponentes que se tornaram tomadores: lembre-se de que clientes que não adquiriram o cartão devem ser desconsiderados. A base de pagamentos possui apenas clientes que adquiriram cartão de crédito, então você pode selecionar somente os clientes da base de propostas que se encontram na base de pagamentos.

4) Consolidando as informações
Faça uma junção das informações da base de propostas com a variável de default que você acabou de construir. Talvez você consiga realizar a tarefa 3 e tarefa 4 em uma única linha de código ;)

5) Verificando
Faça uma contagem dos valores do default que você construiu.
