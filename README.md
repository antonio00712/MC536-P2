# Projeto MC536
> Projeto 2 da disciplina de Banco de Dados MC536 da Unicamp

> No código tables.py favor ajustar os caminhos para o csv escolas.csv (linha 218) e para banco de dados database.duckdb (linha 8) em sua máquina.

## 🌎 Objetivo de Desenvolvimento Sustentável
Este projeto se relaciona com a ODS 4 – Educação de qualidade, especialmente com as metas 4.4 e 4.c. Ao cruzar dados sobre a infraestrutura das escolas com o desempenho dos alunos no ENEM, buscamos entender como fatores como acesso à internet, biblioteca, saneamento e laboratórios impactam a formação de habilidades importantes para o mercado de trabalho. Isso contribui para pensar políticas que melhorem o ambiente escolar e ajudem no desenvolvimento de competências técnicas e profissionais (meta 4.4), além de apoiar decisões sobre a formação e distribuição de professores qualificados (meta 4.c).

## 🔷 Cenário: A

Você foi contratado para reformular um sistema de consulta a dados altamente estruturados. As principais operações consistem em realizar análises estatísticas sobre grandes volumes de dados históricos e imutáveis. As consultas acessam frequentemente um número pequeno de atributos, mas um número grande de registros. O sistema é utilizado por analistas de dados que preferem uma integração direta com linguagens como Python ou R.

## 🦆 Por que utilizar o DuckDB?
O DuckDB é a melhor escolha para o cenário A porque usa um modelo de armazenamento colunar, que garante leitura rápida e boa compressão, ideal para trabalhar com muitos dados históricos e poucas atualizações. Ele é compatível com SQL, o que facilita o reaproveitamento das consultas do Projeto 1, e se integra muito bem com Python e R. Como o foco é leitura, o modelo pode ser desnormalizado sem prejuízo, ganhando desempenho. O banco funciona de forma leve, sem precisar de servidor, e oferece o básico em termos de transações e segurança, com dados salvos em um único arquivo .duckdb, o que também facilita backup e recuperação.

## 🤝 Grupo
- Pedro Henrique dos Reis Arcoverde `RA: 254719`
- Leonardo da Silva Giovanelli de Santana `RA: 256472`
- Antonio Carlos Carvalho Macedo `RA: 199152`
