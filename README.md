# Perguntas
## 1) Você acha que este código está estruturado, legível e escalável?
## Resposta: não
## 2) O que você mudaria nos arquivos e na estrutura de pastas para melhorá-lo nesse sentido?
## Resposta: Trabalharia com Camadas, criando uma pasta para cada camada e as classes para cada Entidade, dessa forma cada classe teria sua responsabilidade.
## 3) Quanto a arquitetura API e sua conteinerização, liste as brechas de segurança que você identificou neste código? Como você as resolveria?
## Resposta: no codigo nao ha nenhum controle ou registro de acesso a base de dados, qualquer usuario tem acesso a qualquer dados nesta base a qualquer momento. implementaria uma política de segurança onde requisitsse que a pessoa teria que estar com um token válido, podendo ser temporário, para que a Api faça as buscas. Caso contrário, ele não realizaria as consultas ao banco.   

