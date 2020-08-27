# Trainees

Olá, seja bem-vindo ao nosso repositório do projeto de avaliação de trainees.

Aqui será passadas as instruções para você realizar o seu teste, e quem sabe vir trabalho conosco.

Desde já, te desejo Boa Sorte!!!

# As Instruções Iniciais

Para realizar o teste você deverá criar um repositório privado no seu github.

Neste repositório que você criou, você deverá adicionar a chave desta conta da CuboConnect (ID: cubo-connect) como Contribuidor do seu repositório.

Não é necessário que o cubo-connect possua acesso de escrita, apenas de leitura.

O acesso pode ser concedido em qualquer momento, no início ou no término do desenvolvimento da solução. Fica a seu critério.

# O Teste

Uma empresa de gestão de saúde, quer fazer um software de administração de vacinas de seus clientes.

Esta empresa já tem um bom volume de clientes, e basicamente oferece serviços de marcação de consultas, acompanhamento médico e auxílios de saúde em situações de emergência.

Esta empresa também já possui um boa variedade e sistemas já construídos.

Mas a empresa precisa de um módulo novo de Administração de Vacinas.

Você deverá construir algumas funcionalidades para este módulo.

Será necessário neste módulo, ter um cadastro de Vacinas.

Para cadastrar uma vacina, algumas informações são necessárias:
- Nome da vacina (Com no máximo 80 caracteres)
- Recomendações gerais da vacina. (Texto com até 1.000 caracteres)
- Faixa de idades em que a vacina é recomendada.
- Um indicador se existe campanha ativa para vacinação (sim ou não)
- E caso exista campanha, qual a data de término da campanha.

Algumas regras complementares:
- Para a faixa de idades, considere que uma vacina pode ser somente recomendada a partir de uma certa idade, por exemplo 60 anos.
- Algumas vacinas, ao contrário da anterior, somente são recomendadas até uma certa idade, por exemplo, 15 anos.
- E ainda algumas vacinas são válidas para um certo período da vida, como por exemplo, entre 20 e 60 anos.
- O que não é válido: um vacina que não possua nem início e nem fim de recomendação informada, e tão pouco um vacina que a recomendação é de uma faixa de idades inválida, como por exemplo, entre 30 e 20 anos!!! Não faz sentido.

Você deverá construir uma API Rest que basicamente possua duas operações:
- Liste todas as vacinas já cadastradas.
- Inclua uma nova vacina.

Ao incluir uma nova vacina, todas as regras de negócio devem ser observadas e criticadas, não permitindo a inclusão de vacina com dados inválidos.

Você pode construir esta API Rest em NodeJS, Spring Boot ou AspNet Core. Fica a seu critério.

Você pode armazenar os dados em um banco de dados relacional, ou um banco de dados noSQL. Fica a seu critério.

Não é necessário criar testes automatizados.

# Submeter para Avaliação

Como já citado anteriormente, você deverá criar um repositório em seu github para versionar o código-fonte da solução.

Considere adicionar o README.md do seu repositório, relatando instruções de como devemos usar a sua API e explicando detalhes de implementação/solução técnica.

Ao término do desenvolvimento da solução, você deverá enviar email para rh@cuboconnect.com.br com seu Nome e Link do seu repositório para nossa avaliação.

Assim que finalizarmos nossa avaliação do seu teste, você receberá um feedback, e em caso positivo avançaremos no processo seletivo.

Boa sorte e bom teste!!!

