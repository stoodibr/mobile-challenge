# Desafio mobile

A ideia deste desafio é nos permitir avaliar melhor as habilidades de candidatos à vagas de desenvolvedor, de vários níveis.
O tempo limite é de sete dias.

## Instruções de entrega do desafio

1. Primeiro, faça um *fork* deste projeto para sua conta no Bitbucket (crie uma se você não possuir).
1. Em seguida, implemente o projeto tal qual descrito abaixo, em seu próprio *fork*.
1. Por fim, faça *commit* e *push* com todas as suas alterações para o seu *fork* no Bitbucket e envie um pull request para este repositório original. 

## Descrição do projeto

Você deve criar um aplicativo que irá listar os repositórios públicos mais populares relacionados à Swift no GitHub, usando a [API GraphQL do GitHub](https://api.github.com/graphql) ou [API REST do GitHub](https://developer.github.com/v3/) para buscar os dados necessários.

O aplicativo deve exibir inicialmente uma lista paginada dos repositórios, ordenados por popularidade decrescente.

Cada repositório deve exibir `Nome do repositório`, `Descrição do Repositório`, `Nome` / `Foto do autor`, `Número de Stars`, `Número de Forks`.

Ao tocar em um item, deve levar a lista de Pull Requests do repositório. Cada item da lista deve exibir `Nome` / `Foto do autor do PR`, `Título do PR`, `Data do PR` e `Body do PR`.

Também é esperado que você crie uma tela adicional que partirá de qualquer outra, alguma ação qualquer, seja clique, ou qualquer outra ação. Esta parte é para você mostrar mais qualquer conhecimento que você achar necessário sabermos.

Você pode se basear neste mockup para criar as telas mencionadas acima:

![mockup](mockup.png)

Sua aplicação deve ter os seguintes critérios:

- Android (Kotlin), iOS (Swift 5.0) ou Flutter (Dart 2.5)
- Suporte as versões Android (API 19) e/ou iOS 10.*
- usar arquivos .gitignore no repositório
- Layouts responsivos e otimizados
- usar gestão de dependências no projeto. Ex: *Cocoapods*, *Pub*, *Gradle*
- usar uma *lib* para Comunicação com API. Ex: *Apollo GraphQL*, *Retrofit*, *Alamofire*, *Flutter GraphQL*, *Artemis*
- ser implementada utilizando algum padrão de arquitetura
- possuir boa cobertura de testes unitários no projeto. Ex: *JUnit*, *Robolectric*, *XCTests* / *Quick* + *Nimble*

Você ganha mais pontos se:

- utilizar libs que usam paradigma reativo/funcional como *RxSwift*, *RxDart*, *RxKotlin* 
- persistir os dados localmente usando *Core Data* / *Realm* / *Room*, etc
- fazer um app Universal, Tablets | Ipad | Iphone | Landscape | Portrait (Size Classes)
- fazer cache de imagens. Ex: Picasso/Glide/SDWebImage/Kingfisher/AlamofireImage
- utilizar alguma biblioteca de injeção de dependência. Ex: *Swinject*, *Dagger*, *GetIt*
- utilizar *clean architecture*
- utilizar *MVVM* ou *BLoC* 
- Testes de *UI*

As sugestões de bibliotecas fornecidas são só um guideline, sinta-se a vontade para usar soluções diferentes e nos surpreender. O importante de fato é que os objetivos macros sejam atingidos.

## Avaliação

Seu projeto será avaliado de acordo com os seguintes critérios.

1. Sua aplicação preenche os requerimentos básicos?
1. Você documentou a maneira de configurar o ambiente e rodar sua aplicação?
1. Você seguiu as instruções de envio do desafio?
1. Você enviaria para produção seu código da maneira como está?

Adicionalmente, tentaremos verificar a sua familiarização com as bibliotecas padrões (standard libs), bem como sua experiência com programação orientada a objetos a partir da estrutura de seu projeto,
além de que o projeto será avaliado o mais próximo possível de uma solução para produção.
