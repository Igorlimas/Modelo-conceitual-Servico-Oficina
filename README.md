# Modelo-conceitual-para-banco-de-dados-Servico-Oficina
Modelo conceitual para banco de dados de uma Sistema de controle e gerenciamento de execução de Ordens de Serviço (O.S.) de uma oficina automobilística. Utilizando MySQL para realizar a modelagem.

OBJETIVO:
Criação de um o modelo (esquema) conceitual para os serviços de oficina.

- Os Clientes levam os veículos à oficina mecânica para serem consertados ou passarem por revisões periódicas e, cada veículo é designado a uma equipe de mecânicos que avalia os serviços a serem executados;
- Em seguida, preenchem uma O.S. com a data de entrega, conforme tipo de serviço e peça as serem utilizadas;
- A partir da OS, calcula-se o valor de cada serviço, com referência a uma tabela de preço de mão-de-obra; O valor de cada peça também irá compor a O.S.;
- O Cliente autoriza (Libera) a execução dos serviços ou não;
- A mesma equipe avalia, executará os serviços;
- Cada mecânico possue código, nome, endereço e especialidade;
- E, cada OS possui: n° de identificação, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
- OBS.01: O.S. pode ser composta por vários tipos de serviços, assim como um tipo de serviço pode compor mais de uma O.S.
- OBS.02: O.S. pode ter vários tipos de peças, assim como um tipo de peça pode estar contida em mais de um a O.S.
