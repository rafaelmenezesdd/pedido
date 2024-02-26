<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pedido de Comida</title>
    <link rel="stylesheet" href="ttt.css">
</head>

<body>
    <header>
        <h1>Nome do Restaurante</h1>
    </header>
    <main>
        <section id="menu">
            <h2>Menu</h2>
            <!-- Aqui você pode listar os itens do menu -->
            <div class="item">
                <h3>Nome do Prato</h3>
                <p>Descrição do Prato.</p>
                <p>Preço: $XX.XX</p>
                <button class="add-to-cart" data-item-id="1">Adicionar ao Carrinho</button>
            </div>
            <!-- Repita o código acima para outros itens do menu -->
        </section>
        <section id="cart">
            <h2>Carrinho de Compras</h2>
            <ul id="cart-items">
                <!-- Os itens selecionados serão exibidos aqui -->
            </ul>
            <button id="checkout">Finalizar Pedido</button>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Nome do Restaurante. Todos os direitos reservados.</p>
    </footer>
    <button id="openChat">Abrir Chat</button>

    <script>
        document.getElementById('openChat').addEventListener('click', function() {
            // Substitua 'NUMERO_DO_WHATSAPP' pelo número de telefone do WhatsApp que você deseja usar
            window.open('https://wa.me/94996621746', '_blank');
        });
    </script>

</html>
