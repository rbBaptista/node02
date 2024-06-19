# App

## RFs (Requisitos funcionais)

    - [ ] O usuario deve poder se cadastrar na aplicacao
    - [ ] O usuario deve poder se autenticar na aplicacao
    - [ ] O usuario deve poder obter o seu perfil
    - [ ] O usuario deve poder obter o total de checkins realizados
    - [ ] O usuario deve poder obter o historico de checkins
    - [ ] O usuario deve poder buscar academias proximas
    - [ ] O usuario deve poder buscar academias pelo nome
    - [ ] O usuario deve poder realizar checkin em uma academia
    - [ ] O usuario deve poder validar o checkin
    - [ ] O usuario deve poder cadastrar uma nova academia

## RNs (Requisitos de negocio)

    - [ ] O usuario nao pode se cadastrar com email duplicado
    - [ ] O usuario nao pode fazer dois checkins no mesmo dia
    - [ ] O usuario nao pode fazer checkin a uma distancia maior que 100 metros da academia
    - [ ] O checkin so 'e valido por 20 minutos
    - [ ] O checkin so pode ser validado por um amdministrador
    - [ ] A academia so pode ser cadastrada por um administrador

## RNFs (Requisitos nao funcionais)

    - [ ] A senha do usuario precisa estar criptografada
    - [ ] O usuario deve ser autenticado por JWT
    - [ ] Os dados da aplicacao devem ser armazenados em um banco de dados
    - [ ] Todas as listagens devem ser paginadas (20 itens por pagina)