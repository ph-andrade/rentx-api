# Cadastro de carro

**RF**
Deve ser possível cadastrar um novo carro.

**RN**
Não deve ser possível cadastrar um carro com uma placa já existente.
O carro deve ser cadastrado, por padrão, com disponibilidade.
O usuário responsável pelo cadastro deve ser administrador.

# Listagem de carros

**RF**
Deve ser possível listar todos os carros disponíveis.
Deve ser possível listar todos os carros disponíveis pelo nome da categoria.
Deve ser possível listar todos os carros disponíveis pelo nome da marca.
Deve ser possível listar todos os carros disponíveis pelo nome do carro.

**RN**
O usuário não precisar estar logado no sistema.

# Cadastro de especificação no carro

**RF**
Deve ser possível cadastrar uma especificação para um carro.

**RN**
Não deve ser possível cadastrar uma especificação para um carro não cadastrado.
Não deve ser possível cadastrar uma especificação já existente para o mesmo carro.
O usuário responsável pelo cadastro deve ser administrador.

# Cadastro de imagens do carro

**RF**
Deve ser possível cadastrar a imagem do carro.

**RN**
Utilizar o multer para upload dos arquivos.

**RN**
O usuário deve poder cadastrar mais de uma imagem para o mesmo carro.
O usuário responsável pelo cadastro deve ser administrador.

# Aluguel de carro

**RF**
Deve ser possível cadastrar um aluguel.

**RN**
O Aluguel deve ter duração mínima de 24 horas.
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo usuário.
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo carro.
Ao realizar um aluguel, o status do carro deverá ser alterado para indisponível.

# Devolução do carro

**RF**
Deve ser possível realizar a devolução de um carro.

**RN**
Se o carro for devolvido em menos de 24h, deverá ser cobrado a diária completa.
Ao realizar a devolução, o carro deverá ficar disponível para outro aluguel.
Ao realizar a devolução, o usuário deverá ficar disponível para outro aluguel.
Caso o horário de devolução for superar ao horário previsto de entrega deverá ser cobrado multa proporcional aos dias de atraso.
Caso tiver multa, deverá ser somada ao montante do aluguel.