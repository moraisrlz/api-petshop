# api-petshop
Projeto de uma pagina Pessoal
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>API Pet Shop</title>
    <style>
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            color: #003366;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0077cc;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            padding: 20px;
            max-width: 900px;
            margin: auto;
            background-color: white;
        }
        h2 {
            color: #0059b3;
        }
        table {
            border-collapse: collapse;
            width: 100%;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 8px;
            font-size: 14px;
        }
        th {
            background-color: #cce6ff;
        }
        footer {
            text-align: center;
            font-size: 13px;
            color: #666;
            padding: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>API Pet Shop</h1>
    </header>

    <div class="container">
        <h2>Lista de Produtos</h2>
        <table>
            <thead>
                <tr>
                    <th>ID</th>
                    <th>Nome</th>
                    <th>Descrição</th>
                    <th>Preço (R$)</th>
                    <th>Estoque</th>
                </tr>
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
                <tr><td>11</td><td>Cama para cachorro</td><td>Cama acolchoada tamanho G</td><td>120.00</td><td>18</td></tr>
                <tr><td>12</td><td>Ração para gatos filhotes</td><td>Ração específica para crescimento saudável</td><td>92.00</td><td>34</td></tr>
                <tr><td>13</td><td>Bebedouro automático</td><td>Fonte com filtro para cães e gatos</td><td>99.90</td><td>22</td></tr>
                <tr><td>14</td><td>Escova de pelos</td><td>Escova com cerdas macias para remoção de pelos mortos</td><td>18.90</td><td>55</td></tr>
                <tr><td>15</td><td>Brinquedo de pelúcia</td><td>Brinquedo com apito para cães</td><td>25.00</td><td>48</td></tr>
                <tr><td>16</td><td>Coleira peitoral</td><td>Coleira tipo peitoral para cães médios</td><td>35.00</td><td>27</td></tr>
                <tr><td>17</td><td>Ração para roedores</td><td>Alimento completo para hamster e porquinho da índia</td><td>19.90</td><td>38</td></tr>
                <tr><td>18</td><td>Areia sílica para gatos</td><td>Areia higiênica de sílica com alta absorção</td><td>42.00</td><td>32</td></tr>
                <tr><td>19</td><td>Pente para pulgas</td><td>Pente de aço para remoção de pulgas e ovos</td><td>14.90</td><td>44</td></tr>
                <tr><td>20</td><td>Bolinha de tênis</td><td>Brinquedo resistente para cães</td><td>12.00</td><td>70</td></tr>
                <tr><td>21</td><td>Ração para cães filhotes</td><td>Ração específica para cães em fase de crescimento</td><td>110.00</td><td>37</td></tr>
                <tr><td>22</td><td>Coleira com plaquinha</td><td>Coleira com plaquinha de identificação gravável</td><td>28.50</td><td>29</td></tr>
                <tr><td>23</td><td>Petisco dental</td><td>Snack para limpeza dos dentes</td><td>20.00</td><td>65</td></tr>
                <tr><td>24</td><td>Toca para gatos</td><td>Toca de tecido para gatos dormirem confortavelmente</td><td>95.00</td><td>16</td></tr>
                <tr><td>25</td><td>Roupinha para cachorro</td><td>Roupa de frio tamanho P</td><td>45.00</td><td>35</td></tr>
                <tr><td>26</td><td>Limpador de patas</td><td>Copo com cerdas para lavar as patas dos cães</td><td>30.00</td><td>28</td></tr>
                <tr><td>27</td><td>Tesoura para unhas</td><td>Tesoura especial para cortar unhas de pets</td><td>17.90</td><td>50</td></tr>
                <tr><td>28</td><td>Coleira refletiva</td><td>Coleira com fita refletiva para segurança noturna</td><td>32.00</td><td>23</td></tr>
                <tr><td>29</td><td>Ração úmida para gatos</td><td>Sachê com pedaços de carne em molho</td><td>4.90</td><td>100</td></tr>
                <tr><td>30</td><td>Desinfetante pet</td><td>Desinfetante seguro para uso em ambientes com animais</td><td>24.90</td><td>40</td></tr>
                <tr><td>31</td><td>Shampoo para gatos</td><td>Shampoo seco para higiene de gatos</td><td>27.00</td><td>33</td></tr>
                <tr><td>32</td><td>Arranhador pequeno</td><td>Arranhador de papelão reciclável</td><td>59.00</td><td>21</td></tr>
                <tr><td>33</td><td>Escova dental</td><td>Escova dupla para higiene bucal de cães e gatos</td><td>13.50</td><td>46</td></tr>
                <tr><td>34</td><td>Mordedor com corda</td><td>Brinquedo resistente com corda para puxar</td><td>19.00</td><td>36</td></tr>
                <tr><td>35</td><td>Porta petiscos</td><td>Brinquedo dispenser de petiscos</td><td>49.90</td><td>27</td></tr>
                <tr><td>36</td><td>Fonte para gatos</td><td>Fonte elétrica com filtro para gatos beberem mais água</td><td>135.00</td><td>14</td></tr>
                <tr><td>37</td><td>Casinha plástica</td><td>Casinha para cães pequenos</td><td>180.00</td><td>10</td></tr>
                <tr><td>38</td><td>Spray educador</td><td>Spray para evitar xixi fora do lugar</td><td>34.90</td><td>24</td></tr>
                <tr><td>39</td><td>Tapete gelado</td><td>Tapete refrescante para dias quentes</td><td>79.90</td><td>19</td></tr>
                <tr><td>40</td><td>Luva removedora de pelos</td><td>Luva que remove pelos soltos durante o carinho</td><td>21.90</td><td>42</td></tr>
                <tr><td>41</td><td>Bolsa para transporte</td><td>Bolsa acolchoada para gatos e cães de pequeno porte</td><td>99.00</td><td>13</td></tr>
                <tr><td>42</td><td>Cinto de segurança</td><td>Cinto que prende o pet no carro com segurança</td><td>36.00</td><td>25</td></tr>
                <tr><td>43</td><td>Colônia pet</td><td>Colônia com fragrância suave para pets</td><td>26.00</td><td>30</td></tr>
                <tr><td>44</td><td>Cortador elétrico de pelos</td><td>Máquina para tosa caseira de cães e gatos</td><td>199.00</td><td>9</td></tr>
                <tr><td>45</td><td>Brinquedo interativo</td><td>Jogo de inteligência para cães e gatos</td><td>89.00</td><td>18</td></tr>
                <tr><td>46</td><td>Guia retrátil</td><td>Guia extensível para passeios</td><td>59.90</td><td>31</td></tr>
                <tr><td>47</td><td>Ração para peixe beta</td><td>Ração específica para peixes ornamentais</td><td>8.90</td><td>50</td></tr>
                <tr><td>48</td><td>Termômetro aquático</td><td>Termômetro para controle da temperatura em aquários</td><td>12.00</td><td>20</td></tr>
                <tr><td>49</td><td>Filtro para aquário</td><td>Filtro de carvão ativado para aquários</td><td>45.00</td><td>15</td></tr>
                <tr><td>50</td><td>Luz UV para aquário</td><td>Iluminação e esterilização para aquários</td><td>72.00</td><td>11</td></tr>
            </tbody>
        </table>
    </div>

    <footer>
        &copy; 2025 moraisrlz - Projeto acadêmico de API Flask
    </footer>
</body>
</html>
