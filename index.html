# <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Coxinhas Gourmet com Localização</title>
    <style>
        /* Estilos básicos */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            max-width: 900px;
            padding: 20px;
            background: #fff;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: center;
        }

        .titulo {
            font-size: 2em;
            margin-bottom: 20px;
        }

        .produtos {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-between;
        }

        .produto {
            flex: 1 1 calc(45% - 10px);
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
            text-align: center;
        }

        .produto img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 15px;
        }

        .btn, .btn-finalizar {
            padding: 10px 20px;
            background-color: #3498db;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }

        .btn:hover, .btn-finalizar:hover {
            background-color: #2980b9;
        }

        .total-container {
            margin-top: 20px;
            font-size: 1.2em;
        }

        .total-container span {
            font-weight: bold;
            color: #e67e22;
        }
    </style>
</head>
<body>

<div class="container">
    <h1 class="titulo">Loja de Coxinhas Gourmet</h1>
    <div class="produtos">
        <div class="produto">
            <img src="https://via.placeholder.com/100?text=Coxinha+Clássica" alt="Coxinha Clássica">
            <h3>Coxinha Clássica</h3>
            <p>R$ 5,00</p>
            <input type="number" class="quantidade" value="1" min="1">
            <button class="btn" onclick="adicionarAoCarrinho(5, this.previousElementSibling.value)">Adicionar</button>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/100?text=Coxinha+Vegana" alt="Coxinha Vegana">
            <h3>Coxinha Vegana</h3>
            <p>R$ 6,00</p>
            <input type="number" class="quantidade" value="1" min="1">
            <button class="btn" onclick="adicionarAoCarrinho(6, this.previousElementSibling.value)">Adicionar</button>
        </div>
    </div>
    
    <div class="total-container">
        Total: R$ <span id="total">0.00</span>
    </div>
    <button class="btn-finalizar" onclick="finalizarCompra()">Finalizar Compra</button>
</div>

<script>
    let total = 0;
    let coxinhasTotal = 0;

    function adicionarAoCarrinho(preco, quantidade) {
        total += preco * quantidade;
        coxinhasTotal += parseInt(quantidade);
        document.getElementById("total").textContent = total.toFixed(2);
    }

    function finalizarCompra() {
        if (total > 0) {
            if (navigator.geolocation) {
                navigator.geolocation.getCurrentPosition(
                    (posicao) => {
                        const latitude = posicao.coords.latitude;
                        const longitude = posicao.coords.longitude;
                        
                        const numeroDono = "559181375639"; // Número do dono com código do país
                        const mensagem = `Olá José, eu quero ${coxinhasTotal} coxinhas, total a pagar: R$ ${total.toFixed(2)}. Minha localização: https://www.google.com/maps?q=${latitude},${longitude}`;
                        
                        const urlWhatsApp = `https://wa.me/${numeroDono}?text=${encodeURIComponent(mensagem)}`;
                        window.open(urlWhatsApp, '_blank');
                        
                        total = 0;
                        coxinhasTotal = 0;
                        document.getElementById("total").textContent = total.toFixed(2);
                    },
                    (erro) => {
                        alert("Não foi possível obter a localização.");
                    }
                );
            } else {
                alert("Geolocalização não é suportada pelo seu navegador.");
            }
        } else {
            alert("Seu carrinho está vazio! Adicione coxinhas antes de finalizar a compra.");
        }
    }
</script>

</body>
</html>
