bu# selamualey.com
Selamualey.com için ana açılış sayfası
# Selam verdik, kazançlı çıktık.

/urunler/index.html
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <esselamualey.com>Ürünler | Selamualey</esselamualey.com>

  <meta name="description" content="Güncel fiyatlarla en çok aranan ürünler. Satın alma işlemleri ilgili mağazalar üzerinden gerçekleştirilir.">

  <style>
    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      background: #ffffff;
      color: #111;
    }

    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 32px 20px 80px;
    }

    h1 {
      font-size: 34px;
      margin-bottom: 8px;
    }

    .subtitle {
      font-size: 15px;
      color: #555;
      margin-bottom: 32px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
      gap: 24px;
    }

    .product {
      border: 1px solid #eee;
      border-radius: 14px;
      padding: 16px;
      background: #fff;
      display: flex;
      flex-direction: column;
    }

    .product img {
      width: 100%;
      height: 200px;
      object-fit: contain;
      margin-bottom: 14px;
    }

    .product h2 {
      font-size: 18px;
      line-height: 1.4;
      margin: 0 0 10px;
      flex-grow: 1;
    }

    .price {
      font-size: 17px;
      font-weight: 600;
      margin-bottom: 14px;
    }

    .buy {
      text-align: center;
      background: #111;
      color: #fff;
      padding: 12px;
      border-radius: 10px;
      text-decoration: none;
      font-size: 15px;
    }

    .buy:hover {
      background: #000;
    }

    footer {
      margin-top: 48px;
      font-size: 13px;
      color: #777;
      line-height: 1.6;
      border-top: 1px solid #eee;
      padding-top: 24px;
    }
  </style>
</head>

<body>

  <div class="container">

    <h1>Ürünler</h1>
    <p class="subtitle">
      Bu sayfada listelenen ürünler iş ortaklığı (affiliate) bağlantıları içerebilir.
    </p>

    <div class="grid">

      <!-- ÜRÜN KARTI -->
      <div class="product">
        <img src="/assets/img/xiaomi-15t-pro.jpg" alt="Xiaomi 15T Pro 512 GB">
        <h2>Xiaomi 15T Pro (512 GB)</h2>
        <div class="price">39.975 TL</div>
        <a class="buy" href="AFFILIATE_LINK_BURAYA" target="_blank" rel="nofollow sponsored">
          Satın Al
        </a>
      </div>

      <!-- YENİ ÜRÜN BURAYA KOPYALANIR -->

    </div>

    <footer>
      Bu sitede yer alan ürünler yönlendirme (affiliate) bağlantıları içerebilir.
      Satış ve teslimat işlemleri ilgili satıcı tarafından gerçekleştirilir.
    </footer>

  </div>

</body>
</html>

