<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Produto Premium - Apresentação Completa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .product-video {
            text-align: center;
            margin: 20px 0;
        }
        .product-images {
            display: flex;
            gap: 20px;
            margin-bottom: 20px;
        }
        .product-images img {
            width: 100%;
            max-width: 300px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }
        .product-description {
            margin-bottom: 20px;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #45a049;
        }
        .reviews {
            margin-top: 30px;
        }
        .review-item {
            border-bottom: 1px solid #eee;
            padding: 15px 0;
        }
        .review-item:last-child {
            border-bottom: none;
        }
        .review-author {
            font-weight: bold;
        }
        .review-content {
            color: #666;
        }
        .rating {
            color: gold;
            font-size: 1.2em;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #4CAF50;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Produto Premium</h1>
        <p>Inovação, qualidade e performance.</p>
    </header>

    <div class="container">
        <!-- Vídeo do produto -->
        <div class="product-video">
            <h2>Veja o Produto em Ação</h2>
            <video width="100%" controls>
                <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
                Seu navegador não suporta a reprodução de vídeos.
            </video>
        </div>

        <!-- Imagens do produto -->
        <div class="product-images">
            <img src="https://via.placeholder.com/300" alt="Imagem 1 do Produto">
            <img src="https://via.placeholder.com/300" alt="Imagem 2 do Produto">
            <img src="https://via.placeholder.com/300" alt="Imagem 3 do Produto">
        </div>

        <!-- Descrição do produto -->
        <div class="product-description">
            <h2>Descrição do Produto</h2>
            <p>
                Este é o Produto Premium, projetado com tecnologia de ponta e materiais de alta qualidade.
                Perfeito para quem busca o equilíbrio entre design, funcionalidade e durabilidade. 
                Um item indispensável para transformar sua rotina.
            </p>
            <a href="#detalhes" class="btn">Saber Mais</a>
        </div>

        <!-- Avaliações -->
        <div class="reviews">
            <h2>Avaliações de Clientes</h2>

            <div class="review-item">
                <span class="rating">★★★★★</span>
                <p class="review-author">Maria Silva</p>
                <p class="review-content">
                    "Este produto superou minhas expectativas! Excelente qualidade e design impecável."
                </p>
            </div>

            <div class="review-item">
                <span class="rating">★★★★☆</span>
                <p class="review-author">Carlos Andrade</p>
                <p class="review-content">
                    "Ótimo produto! Apenas gostaria de mais opções de cores."
                </p>
            </div>

            <div class="review-item">
                <span class="rating">★★★★★</span>
                <p class="review-author">Juliana Freitas</p>
                <p class="review-content">
                    "Simplesmente incrível. Recomendo a todos!"
                </p>
            </div>
        </div>
    </div>

    <footer>
        <p>Produto Premium &copy; 2025 - Todos os direitos reservados.</p>
    </footer>
</body>
</html>
