# Cadrastro de Carro

**RF**
Deve ser possível cadastrar um novo carro.
Deve ser possível listar todas categorias.

**RN**
Não deve ser possível cadastrar um carro com uma placa já existente.
não deve ser possível alterar a placa de um carro ja cadastrado.
O carro deve ser cadastrado, por padrão, com disponibilidade.
O usuário responsável pelo cadastro, deve ser um usuário administrador.

# Listagem de carros

**RF**
Deve ser possível listar todos carros disponíveis.
Deve ser possível listar todos carros disponíveis pelo nome da categoria.
Deve ser possível listar todos carros disponíveis pelo nome da marca.
Deve ser possível listar todos carros disponíveis pelo nome do carro.

**RN**
O usuário não precisa estar logado no sistema.

# Cadastro de especificação no carro

**RF**
Deve ser possível cadastrar uma especificação para um carro.
Deve ser possível listar todas especificações.
Deve ser possível listar todos carros

**RN**
Não deve ser possível cadastrar uma especificação para um carro não cadastrado.
Não deve ser possível cadastrar uma especificação já existente para o mesmo carro.
O usuário responsável pelo cadastro, deve ser um usuário administrador.

# Cadastro de imagens do carro

**RF**
Deve ser possível cadastrar a imagem do carro.
Deve ser possível listar todos carros

**RNF**
Utilizar o multer para upload dos arquivos.

**RN**
O usuário deve poder cadastrar mais de uma imagem para o mesmo carro.
O usuário responsável pelo cadastro, deve ser um usuário administrador.

# Aluguel de carro

**RF**
Deve ser possível cadastrar um aluguel.

**RN**
O aluguel deve ter duração mínima de 24 horas.
Não deve ser possível cadastrar um nono aluguel caso já exista um aberto para o mesmo usuário.
Não deve ser possível cadastrar um nono aluguel caso já exista um aberto para o mesmo carro.
