# Desafios
Desafios concluidos durante o curso
<br><b>Dart: </b>

>Desafio 1
- Listas e tratamento de strings
- Descrição:
    - Lista a ser tratada:
        ```dart
        final pacientes = [
            'Rodrigo Rahman|35|desenvolvedor|SP',
            'Manoel Silva|12|estudante|MG',
            'Joaquim Rahman|18|estudante|SP',
            'Fernando Verne|35|estudante|MG',
            '...']
        ```
    - Apresente os pacientes com mais de 20 anos e print o nome deles
    - Apresente quantos pacientes existem para cada profissão (desenvolvedor, estudante, dentista, jornalista)
    - Apresente a quantidade de pacientes que moram em SP
- Resolução: [Clique aqui](./Desafio_Dart/Desafio_1.dart)
<br>

>Desafio 2
- Listas e tratamento de strings obter dados da lista
- Descrição:
    - Lista a ser tratada:
        ```dart
        final pessoas = [
            'Rodrigo Rahman|35|Masculino',
            'Jose|56|Masculino',
            'Joaquim|84|Masculino',
            'Rodrigo Rahman|35|Masculino',
            '...']
        ```
    - Remova os pacientes duplicados e apresente a nova lista
    - Me mostre a quantidade de pessoas por sexo (Masculino e Feminino) e depois me apresente o nome dela
    - Filtrar e deixar a lista somente com pessoas maiores de 18 anos e apresente essas pessoas pelo nome
    - Encontre a pessoa mais velha e apresente o nome dela
- Resolução: [Clique aqui](./Desafio_Dart/Desafio_2.dart)
<br>

>Desafio 3
- Trabalhando com banco de dados SQL
    - Preencher no MySQL duas tabelas
    - Estado salvar nesta tabela todos os estados do Brasil
    - Exemplo:
        |Estado   |Sigla|
        |-------  |-----|
        |Bahia    |BA   |
        |São Paulo|SP   |
    - Cidades, salvar nesta tabela todos as cidades do Brasil com a sigla correspondente a seu estado.
    - Exemplo:
        |Cidade   |Estado|
        |-------  |----- |
        |Salvador |BA    |
        |Ilheus   |BA    |
        |Santos   |SP    |
    - Fonte Estados: [IBGE](https://servicodados.ibge.gov.br/api/v1/localidades/estados)
    - Fonte Cidades: [IBGE](https://servicodados.ibge.gov.br/api/v1/localidades/estados/<idEstado>/distritos)
- Resolução: [Clique aqui](../Desafios/Desafio_Dart/desafio_3)

<br><b>Flutter:</b>
>Desafio 1: 
- Instagram clone (página estática)
- Descrição:
    - Modelo a seguir [pag instagram](../Dart/Img/instaClone.png)
- Resolução: [Clique aqui](./Desafio_Flutter/1.flutter_clone_instagram)