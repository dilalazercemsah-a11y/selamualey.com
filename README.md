bu# selamualey.com
Selamualey.com için ana açılış sayfası
# Selam verdik, kazançlı çıktık.

/urunler/index.html
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>Ürünler | esselamualey.com</title>

  <meta name="description" content="esselamualey.com ürün kataloğu. Satın alma işlemleri ilgili siteler üzerinden yapılır.">

  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #ffffff;
      color: #111;
    }

    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 32px 20px 80px;
    }

    h1 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .info {
      font-size: 14px;
      color: #555;
      margin-bottom: 30px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 24px;
    }

    .product {
      border: 1px solid #ddd;
      border-radius: 12px;
      padding: 16px;
      display: flex;
      flex-direction: column;
    }

    .product img {
      width: 100%;
      height: 180px;
      object-fit: contain;
      margin-bottom: 12px;
      background: #f5f5f5;
    }

    .product h2 {
      font-size: 16px;
      margin: 0 0 10px;
    }

    .price {
      font-weight: bold;
      margin-bottom: 12px;
    }

    .buy {
      margin-top: auto;
      text-align: center;
      padding: 10px;
      background: #111;
      color: #fff;
      text-decoration: none;
      border-radius: 8px;
      font-size: 14px;
    }

    footer {
      margin-top: 50px;
      font-size: 13px;
      color: #666;
      border-top: 1px solid #eee;
      padding-top: 20px;
    }
  </style>
</head>

<body>

<div class="container">

  <h1>Ürünler</h1>

  <p class="info">
    Bu sayfada yer alan ürünler yönlendirme (affiliate) bağlantıları içerebilir.
  </p>

  <div class="grid">

    <!-- ÜRÜN 1 -->
    <div class="product">
      <img src="/assets/img/urun-gorseli.jpg" alt="ürün ismi">
      <h2>ürün ismi</h2>
      <div class="price">ürün fiyatı</div>
      <a class="buy" href="ürün linki" target="_blank" rel="nofollow sponsored">
        Satın Al
      </a>
    </div>

    <!-- ÜRÜN 2 -->
    <div class="product">
      <img src="/assets/img/urun-gorseli.jpg" alt="ürün ismi">
      <h2>ürün ismi</h2>
      <div class="price">ürün fiyatı</div>
      <a class="buy" href="ürün linki" target="_blank" rel="nofollow sponsored">
        Satın Al
      </a>
    </div>

    <!-- 165. ÜRÜN DE AYNI ŞEKİLDE EKLENİR -->

  </div>

  <footer>
    esselamualey.com sitesinde yer alan ürünler bilgilendirme amaçlıdır.
    Satış ve teslimat işlemleri ilgili satıcı tarafından gerçekleştirilir.
  </footer>

</div>

</body>
</html>
