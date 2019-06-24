# Stag

**STAG** é uma atividade proposta pela **Equipe de Tecnologia da LinCare** às pessoas interessadas a vaga de estágio na equipe.
A ideia principal da atividade é analisar os conhecimentos em relação à:

- Modelagem de soluções;
- Entendimento e interpretação de problemas;
- Modelagem de soluções;
- Raciocínio lógico;
- Ferramentas de controle de versão;
- Clareza de código;
- Capacidade de resolução de problemas;
- Análise e modelagem de soluções;

**Proposta STAG:**

Nossa equipe cansou da nossa API atual e quer fazer uma nova. Você pode nos ajudar?

Bom, estamos sem preferência de uma tecnologia específica, ou seja, você pode usar a linguagem e/ou tecnologia que você tem mais familiaridade.
Mas calma! Não queremos toda a API! Apenas a representação dos nossos usuários e usuárias da Plataforma LinCare.

Ah,mas tem alguns pontos que não abrimos mão:

- A API tem que ser na arquitetura REST ;)
- Estamos sem banco de dados também. Precisamos de uma estrutura e modelagem dados para que a API funcione
- Queremos receber sua atividade nesse repositório do GitHub. Que tal criar uma nova _branch_ e nos mandar? E lembre-se: nada de _commit_ na _master_ ou  _commit -force_ hein!
- A API será um CRUD da nossa entidade Usuário! (Afinal, precisamos cadastrar, atualizar, ler e deletar nossos usuários)

**E que informações um usuário da Plataforma LinCare tem?**

Para cadastrar nossos usuários e usuárias precisamos das seguintes informações:

- Nome
- Data de nascimento
- Endereço com CEP
- Gênero
- Altura
- Peso
- Telefone
- WhatsApp
- E-mail
- CPF
- Login/Senha
- Qual plano foi contrato: 3 meses | 6 meses | 12 meses
- Se tem algum problema de saúde (se sim, qual(is)?)
- Se toma algum medicamento (se sim, qual(is)?)
- Lista de cuidadores (nome, parentesco, contato)

**Observações:**

- Ao cadastrar um novo usuário, será criada uma data de controle de criação do cadastro
- Também é necessário ter uma forma de registrar a data de alguma mudança do cadastro do usuário, que será atualizada a cada e qualquer atualização
- Todo usuário criado, tem um status &#39;ativo&#39;
- Quando o usuário for deletado, ele não será apagado da base de dados. Apenas o seu status passará para &#39;desativado&#39;
- Queremos listar todos e um usuário específico
- Queremos atualizar apenas um usuário por vez
- Queremos deletar apenas um usuário por vez
- Não poderá ser cadastrado um usuário com mesmo CPF e/ou e-mail
- Para a altura, preferimos em metros
- Para o peso, preferimos em kg

**Dicas:**

- Para datas, gostamos de usar **Timestamp**
- Não se esqueça das validações
- Não se esqueça das observações
- Senhas devem ser criptografadas

Bom, é isso! Faça a seu tempo e da melhor maneira que você puder! Vamos olhar todos os pontos.

Caso tenha alguma dúvida, mande uma mensagem para gente: [tech@lincare.com.br](mailto:tech@lincare.com.br)

Até logo ;)

Equipe LinCare
