# Q PROCURA - WEBSITE & APP

## DOCUMENTAÇÃO WEBSITE

### INSTALAÇÃO:

- Antes da instalação, verifique se os componentes abaixo estão ativados no seu servidor:

    - PHP 7.1.3 ou superior (com todas as funções padrão do PHP ativadas, incluindo exec(), etc.)
    - MySQL 5.6 ou superior (o usuário MySQL precisa ter um privilégio total para gerenciar o banco de dados)
    - Extensão PHP OpenSSL
    - Extensão PHP DOP
    - Extensão PHP Mbstring
    - Extensão PHP do tokenizador
    - Extensão XML PHP
    - Extensão PHP de tipo
    - Extensão PHP JSON
    - Extensão PHP BCMath
    - Extensão PHP GD (ou Extensão PHP Imagick)
    - Extensão PHP Fileinfo
    - PHP Zip Archive
    - Módulo de reescrita /*Rewrite Module*/ (Apache ou Nginx)

- Requisitos do PHP.INI:

    - open_basedir deve estar desativado

- Permissões de arquivos e pastas:

    - /bootstrap 775
    - /storage 775 (pastas e subspastas)

> Nota: O script não possui uma pasta "install".  A instalação é realizada por um controlador do sistema.
