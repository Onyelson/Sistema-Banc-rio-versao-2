## 📌 Função cadastrar_usuario(usuarios)

🔹 O que ela faz?

Ela permite que um usuário seja cadastrado no banco. Cada usuário tem:

    CPF (somente números)

    Nome completo

    Data de nascimento

    Endereço (logradouro, número - bairro - cidade/UF)

## 📌 Função cadastrar_conta(contas, usuarios, numero_conta)
🔹 O que ela faz?

Ela cria uma nova conta bancária vinculada a um usuário já cadastrado.
Cada conta tem:

    Agência (sempre "0001")

    Número da conta (sequencial, começando em 1)

    Usuário vinculado (identificado pelo CPF)
