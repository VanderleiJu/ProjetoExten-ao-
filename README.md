<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro para Ação Beneficente</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
        }
        form {
            max-width: 400px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        h2 {
            text-align: center;
        }
        input[type="text"], input[type="email"], select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h2>Cadastro para Ação Beneficente</h2>
    <form action="submit_form.php" method="post">
        <label for="nome_crianca">Nome da Criança:</label>
        <input type="text" id="nome_crianca" name="nome_crianca" required>

        <label for="idade_crianca">Idade da Criança:</label>
        <input type="text" id="idade_crianca" name="idade_crianca" required>

        <label for="nome_pai">Nome do Pai/Responsável:</label>
        <input type="text" id="nome_pai" name="nome_pai" required>

        <label for="email">Email do Pai/Responsável:</label>
        <input type="email" id="email" name="email" required>

        <label for="telefone">Telefone do Pai/Responsável:</label>
        <input type="text" id="telefone" name="telefone" required>

        <label for="endereco">Endereço:</label>
        <input type="text" id="endereco" name="endereco" required>

        <label for="cidade">Cidade:</label>
        <input type="text" id="cidade" name="cidade" required>

        <label for="estado">Estado:</label>
        <select id="estado" name="estado" required>
            <option value="">Selecione o estado</option>
            <option value="AC">Acre</option>
            <option value="AL">Alagoas</option>
            <!-- Adicione mais opções conforme necessário -->
        </select>

        <input type="submit" value="Enviar Cadastro">
    </form>
</body>
</html>
