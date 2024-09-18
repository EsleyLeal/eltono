<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Logo do Laravel"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Status do Build"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Downloads Totais"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Última Versão Estável"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="Licença"></a>
</p>

# Vocalista Manager 🎤

Este projeto tem como objetivo facilitar o gerenciamento de vocalistas, músicas, tonalidades e links de vídeos, com foco em melhorar a organização de ensaios e planejamentos musicais. A ideia surgiu da necessidade de simplificar a escolha de tonalidades adequadas para os vocalistas, especialmente em contextos como ensaios de igreja, onde as variações podem impactar diretamente o desempenho coletivo.

## Tecnologias Utilizadas 🛠️

- **Laravel 9**: Framework PHP utilizado para o desenvolvimento deste projeto. Escolhi o Laravel por sua robustez e facilidade de uso ao construir aplicações web modernas.
- **MySQL**: Banco de dados relacional utilizado para armazenar as informações de vocalistas, músicas e tonalidades.
- **Bootstrap**: Framework CSS que proporcionou uma interface responsiva e moderna.

## Funcionalidades 🚀

- Cadastro de vocalistas com seus respectivos nomes e tonalidades preferidas.
- Registro das músicas com a possibilidade de associar cada música a um vocalista e à sua tonalidade.
- Links de vídeos de referência para cada música, facilitando a preparação e o ensaio dos músicos.

## Motivação 🎯

Este projeto foi criado para resolver um problema recorrente em ensaios musicais, onde a tonalidade das músicas nem sempre correspondia à capacidade vocal dos participantes. A solução visa otimizar o processo de preparação de ensaios, ajudando a equipe a escolher as tonalidades adequadas para cada vocalista de forma ágil e eficiente.

## Aprendizado e Desenvolvimento 📚

Este projeto foi uma excelente oportunidade para consolidar meus conhecimentos em **Laravel**, especialmente no que diz respeito ao desenvolvimento de APIs e à manipulação de dados relacionais com **Eloquent ORM**. Também pude aprimorar habilidades de front-end com **Bootstrap**, garantindo uma interface intuitiva e responsiva. Além disso, o projeto me permitiu aprofundar nas melhores práticas de organização de código e arquitetura de aplicações web.

## Como Executar o Projeto 🚀

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/vocalista-manager.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd vocalista-manager
    ```
3. Instale as dependências:
    ```bash
    composer install
    ```
4. Configure o arquivo `.env` para seu ambiente local.
5. Rode as migrações:
    ```bash
    php artisan migrate
    ```
6. Inicie o servidor local:
    ```bash
    php artisan serve
    ```

---

💡 **Dica:** Para rodar o projeto em um ambiente de desenvolvimento Docker, você pode usar o [Laravel Sail](https://laravel.com/docs/9.x/sail), o ambiente de desenvolvimento oficial do Laravel.

## Contribuições 🤝

Sinta-se à vontade para enviar issues, sugestões ou abrir pull requests! Toda contribuição é bem-vinda.





