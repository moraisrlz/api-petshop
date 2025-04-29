<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>API Pet Shop</title>
    <style>
        body { background-color: #f0f8ff; font-family: Arial, sans-serif; color: #003366; margin: 0; padding: 0; }
        header { background-color: #0077cc; color: white; padding: 20px; text-align: center; }
        .container { padding: 20px; max-width: 900px; margin: auto; background-color: white; }
        h2 { color: #0059b3; }
        table { border-collapse: collapse; width: 100%; margin-top: 20px; }
        th, td { border: 1px solid #ccc; padding: 8px; font-size: 14px; }
        th { background-color: #cce6ff; }
        footer { text-align: center; font-size: 13px; color: #666; padding: 15px; }
    </style>
</head>
<body>
    <header><h1>API Pet Shop</h1></header>
    <div class="container">
        <h2>Lista de Produtos</h2>
        <table>
            <thead>
                <tr><th>ID</th><th>Nome</th><th>Descrição</th><th>Preço (R$)</th><th>Estoque</th></tr>
            </thead>
            <tbody>
                <tr><td>1</td><td>Coleira</td><td>Coleira para cachorro de pequeno porte</td><td>23.90</td><td>26</td></tr>
                <tr><td>2</td><td>Ração para cães adultos</td><td>Ração premium para cães adultos de médio porte</td><td>119.90</td><td>40</td></tr>
                <tr><td>3</td><td>Areia para gatos</td><td>Areia higiênica com controle de odor para gatos</td><td>35.00</td><td>60</td></tr>
                <tr><td>4</td><td>Brinquedo de borracha</td><td>Brinquedo mordedor em formato de osso</td><td>15.00</td><td>75</td></tr>
                <tr><td>5</td><td>Comedouro duplo</td><td>Comedouro e bebedouro acoplado para cães e gatos</td><td>29.90</td><td>30</td></tr>
                <tr><td>6</td><td>Tapete higiênico</td><td>Tapete absorvente para cães</td><td>39.90</td><td>45</td></tr>
                <tr><td>7</td><td>Shampoo para cães</td><td>Shampoo neutro para cães com pele sensível</td><td>22.50</td><td>50</td></tr>
                <tr><td>8</td><td>Antipulgas</td><td>Medicamento antipulgas em comprimido para cães</td><td>89.00</td><td>20</td></tr>
                <tr><td>9</td><td>Caixa de transporte</td><td>Caixa de transporte tamanho médio</td><td>150.00</td><td>12</td></tr>
                <tr><td>10</td><td>Osso de couro</td><td>Osso natural para mastigação</td><td>9.90</td><td>80</td></tr>
            </tbody>
        </table>
    </div>
    <footer>&copy; 2025 moraisrlz - Projeto acadêmico de API Flask</footer>
</body>
</html>
