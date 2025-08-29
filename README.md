<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>T & P BRA Bangsaen Shop | ร้านบรา & ไอเท็มเด็ดสำหรับสาวๆ</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
body {
  font-family: 'Noto Sans Thai', sans-serif;
  background: #fffdfa;
  color: #333;
  margin: 0;
  padding: 0;
}
header, footer {
  background: #f9e6ef;
  text-align: center;
  padding: 1.5rem 0;
}
.shop-contact .contact-btn {
  margin: 0 0.7em;
  background: #ffb6c1;
  color: #fff;
  padding: 0.7em 1.2em;
  border-radius: 30px;
  text-decoration: none;
  font-weight: bold;
  display: inline-block;
}
.shop-contact .fb { background: #4267B2; }
.shop-contact .line { background: #00c300; }
.product-group-title {
  margin-top: 2em;
  color: #d1005d;
  font-size: 1.5em;
  text-align: left;
  border-left: 6px solid #d1005d;
  padding-left: .7em;
  margin-bottom: 1em;
}
.product-card {
  background: #fff;
  border: 1px solid #ffe4f0;
  border-radius: 12px;
  box-shadow: 0 2px 8px #f9e6ef33;
  width: 330px;
  padding: 1rem;
  text-align: center;
  transition: box-shadow .2s;
  margin: 1.2rem auto;
  position: relative;
}
.product-card:hover {
  box-shadow: 0 4px 16px #f9e6ef88;
}
.product-card h3 { margin: .5em 0 .3em; }
.product-card .price { font-size: 1.2em; color: #d1005d; font-weight: bold; }
.product-card .options { margin: .7em 0; }
.product-card .options label { margin-right: .4em; }
.product-card .qty-input { width: 52px; }
.add-cart-btn {
  background: #d1005d;
  color: #fff;
  border: none;
  border-radius: 24px;
  padding: .5em 1.2em;
  font-size: 1em;
  cursor: pointer;
  margin-top: .8em;
  transition: background .2s;
}
.add-cart-btn:hover { background: #b1004a; }
#cart-section {
  margin: 2rem 1rem;
  background: #fdf6f6;
  padding: 1.2em;
  border-radius: 16px;
  box-shadow: 0 2px 12px #f9e6ef33;
}
.cart-item {
  display: flex;
  align-items: center;
  gap: .7em;
  margin-bottom: .5em;
  font-size: 1em;
}
.cart-item img { border-radius: 4px; }
.cart-item button {
  background: #ffb6c1; color: #fff; border: none; border-radius: 50%;
  width: 28px; height: 28px; cursor: pointer; font-size: 1em;
}
#cart-total { font-size: 1.2em; margin-top: 1em; }
#checkout-btn {
  background: #00c300;
  color: #fff;
  border: none;
  border-radius: 30px;
  padding: .7em 1.5em;
  font-size: 1.1em;
  cursor: pointer;
  margin-top: 1.2em;
}
#customer-form-section {
  margin: 2rem 1rem;
  background: #f3f6fd;
  padding: 1.2em;
  border-radius: 16px;
}
#customer-form label { display: block; margin: .7em 0; }
#customer-form input, #customer-form textarea {
  padding: .5em; border-radius: 8px; border: 1px solid #e0e0e0; width: 100%;
  box-sizing: border-box;
}
.payment-info { margin-top: 1em; background: #fffdfa; border-radius: 12px; padding: .8em; }
.gallery-container {
  margin-bottom: .7em;
}
.main-img {
  width: 100%;
  max-width: 240px;
  height: 240px;
  object-fit: cover;
  border-radius: 12px;
  margin-bottom: .3em;
}
.gallery-controls {
  text-align: center;
  margin-bottom: .3em;
}
.thumbnails {
  display: flex;
  flex-wrap: wrap;
  gap: 4px;
  justify-content: center;
}
.thumb {
  width: 32px;
  height: 32px;
  object-fit: cover;
  border-radius: 6px;
  cursor: pointer;
  border: 2px solid #fff;
  box-shadow: 0 2px 6px #e3e3e3;
  transition: border .2s;
}
.thumb.active {
  border-color: #d1005d;
}
@media (max-width: 900px) {
  .product-card { width: 95%; }
}
@media (max-width: 600px) {
  .product-card { width: 100%; }
  #cart-section, #customer-form-section { margin: 1rem 0; }
  .main-img { max-width: 98vw; }
  .product-group-title { font-size: 1.1em; padding-left: .3em; }
}
  </style>
</head>
<body>
  <header>
    <h1>✨🩷 T & P BRA Bangsaen Shop 🩷✨</h1>
    <p>ร้านบรา & ไอเท็มเด็ดสำหรับสาวๆ<br>
    บราไร้สาย บราปีกนก บราดูม บราแปะ แผ่นซิลิโคนกันโป๊ แผ่นดันทรง และอีกเพียบ!!</p>
    <ul>
      <li>📌 ใส่สบาย ไม่เจ็บ ไม่อึดอัด</li>
      <li>📌 มีหลายแบบให้เลือก ใส่กับเสื้อผ้าได้ทุกสไตล์</li>
      <li>📌 ราคาเริ่มต้นแค่ 49 บาท เท่านั้น!</li>
    </ul>
    <div class="shop-contact">
      <a href="https://www.facebook.com/share/19jpJGSYSV/?mibextid=wwXIfr" target="_blank" class="contact-btn fb">Facebook</a>
      <a href="https://lin.ee/NZfUsZ3" target="_blank" class="contact-btn line">Line</a>
    </div>
    <div class="shop-promo">
      <p>🛍️ <strong>โปรโมชั่นพิเศษ</strong></p>
      <ul>
        <li>✅ สั่งครบ 100 บาท จัดส่งฟรีในเขตบางแสน</li>
        <li>✅ ไม่ถึง 100 บาท ค่าส่งแค่ 15 บาทเอง</li>
        <li>🚖 นอกพื้นที่ก็ส่งได้นะคะ (มี Grab)</li>
      </ul>
      <p>🕙 เปิดทุกวัน 10.30 – 23.00 น.</p>
    </div>
  </header>

  <main>
    <section id="products-section">
      </section>

    <section id="cart-section">
      <h2>ตะกร้าสินค้า 🛒</h2>
      <div id="cart-list"></div>
      <div id="cart-total"></div>
      <button id="checkout-btn">สั่งซื้อสินค้า</button>
    </section>

    <section id="customer-form-section" style="display:none;">
      <h2>ข้อมูลผู้สั่งซื้อ</h2>
      <form id="customer-form">
        <label>ชื่อ-นามสกุล: <input type="text" name="name" required></label>
        <label>ที่อยู่จัดส่ง: <textarea name="address" required></textarea></label>
        <label>เบอร์ติดต่อ: <input type="tel" name="phone" required></label>
        <label>รหัสไปรษณีย์: <input type="text" name="zipcode" required></label>
        <button type="submit">ส่งออเดอร์</button>
      </form>
      <div class="payment-info">
        <h3>ข้อมูลชำระเงิน</h3>
        <p>ธนาคาร กสิกรไทย<br>
        กนกวรรณ รุ่งเรืองสินงาม<br>
        เลขบัญชี : 2058457151<br>
        พร้อมเพย์ 0635898555</p>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2025 T & P BRA Bangsaen Shop</p>
  </footer>

  <script>
    // Moved all script code here
const PRODUCT_GROUPS = [
  {
    name: "บราทรงต่างๆ",
    products: [
      {
        id: "bra1",
        name: "บราทรงกลมไร้ขอบ",
        price: 69,
        colors: ["ดำ", "เนื้อ", "ขาว"],
        sizes: ["A", "B", "C", "D"],
        desc: "บราไร้ขอบ ทรงกลม ใส่สบาย ไม่บีบรัด เหมาะสำหรับทุกชุด",
        images: [
        "https://live.staticflickr.com/65535/53590912413_47424d70d5_m.jpg",
        "https://live.staticflickr.com/65535/53590972626_6dbb4b4dd0_m.jpg",
        "https://live.staticflickr.com/65535/53591339165_8a1aefe3ba_m.jpg",
        "https://live.staticflickr.com/65535/53591109518_4b43b7a1a7_m.jpg",
        "https://live.staticflickr.com/65535/53591339425_2fbc1cfc09_m.jpg",
        "https://live.staticflickr.com/65535/53591339270_7b3d7ea290_m.jpg",
        "https://live.staticflickr.com/65535/53591109728_7b9e3f6dba_m.jpg"
        ]
      },
      {
        id: "bra2",
        name: "บราดูมดูม หนา 3 ซม.",
        price: 99,
        colors: ["ดำ", "เนื้อ"],
        sizes: ["A", "B", "C", "D"],
        desc: "บราดูมดูม ฟองน้ำเสริม 3 ซม. ดันอกให้ดูมขึ้น ใส่แล้วมั่นใจ สวยโดดเด่นทุกสไตล์",
        images: [
           "https://live.staticflickr.com/65535/53590911943_7f8c9f6d5d_m.jpg",
        "https://live.staticflickr.com/65535/53590972126_55533e656f_m.jpg",
        "https://live.staticflickr.com/65535/53591338965_17838d4e2d_m.jpg",
        "https://live.staticflickr.com/65535/53590911998_6e2b2c6f5f_m.jpg",
        "https://live.staticflickr.com/65535/53591339905_7c4e5c5a8d_m.jpg",
        "https://live.staticflickr.com/65535/53591339940_e399a71a26_m.jpg"
        ]
      },
      {
        id: "bra3",
        name: "บราลูกไม้ บราเจ้าสาว",
        price: 89,
        colors: ["ดำ", "เนื้อ", "ขาว"],
        sizes: ["A", "B", "C", "D"],
        desc: "บราเจ้าสาวหรูหราด้วยลูกไม้พร้อมสายใส แถมฟรี 1 เส้น ใส่แล้วดูสวยหวานและมีเสน่ห์",
        images: [
         "https://live.staticflickr.com/65535/53590911778_8f6b6e9c4a_m.jpg",
          "https://live.staticflickr.com/65535/53591109873_1e3e5d9a7a_m.jpg",
          "https://live.staticflickr.com/65535/53591339715_8c60a7e2d9_m.jpg",
          "https://live.staticflickr.com/65535/53591109913_026fcdaffa_m.jpg",
          "https://live.staticflickr.com/65535/53591339740_28c2daaf93_m.jpg",
          "https://live.staticflickr.com/65535/53590972281_7c8e3d9f3a_m.jpg",
          "https://live.staticflickr.com/65535/53590972701_9f1d8e6d5d_m.jpg",
          "https://live.staticflickr.com/65535/53590912453_8a6b5e9c4a_m.jpg"
        ]
      },
      {
        id: "bra4",
        name: "บราปีกผีเสื้อ เชือกหน้า",
        price: 79,
        colors: ["ดำ", "เนื้อ", "ขาว"],
        sizes: ["A", "B", "C", "D"],
        desc: "บราปีกผีเสื้อทรงสวย ดึงเชือกหน้าเพื่อปรับเข้ารูป เนียนแนบกับผิว สวยมั่นใจ",
        images: [
 "https://live.staticflickr.com/65535/53591339055_3c6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53591109973_ae6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53590972866_2a6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53591340125_2a6b5e9c4a_m.jpg",
          "https://live.staticflickr.com/65535/53591110053_5a6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53591339615_4a6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53591339795_1a6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53590972686_7a6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53591109918_6a6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53591109728_7b9e3f6dba_m.jpg"
        ]
      },
      {
        id: "bra5",
        name: "บรากาวแผ่นดันทรง",
        price: 79,
        colors: ["ดำ", "เนื้อ"],
        sizes: ["A", "B", "C", "D"],
        desc: "บรากาวแผ่นดันทรง ใช้ง่าย ติดแน่น เนียนเรียบทุกชุด เหมาะกับเสื้อผ้าเปิดหลังหรือเกาะอก",
        images: [
          "https://live.staticflickr.com/65535/53591340180_7e1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53590972961_8da4b2e5c7_m.jpg",
          "https://live.staticflickr.com/65535/53591339090_8a2a813fdd_m.jpg",
          "https://live.staticflickr.com/65535/53591340125_2a6b5e9c4a_m.jpg",
          "https://live.staticflickr.com/65535/53591340290_8593e0e6de_m.jpg",
          "https://live.staticflickr.com/65535/53591339170_3b6e2b5f1a_m.jpg"
        ]
      },
      {
        id: "bra6",
        name: "บราปีกนก",
        price: 59,
        colors: ["ดำ", "เนื้อ"],
        sizes: ["A", "B", "C", "D"],
        desc: "บราปีกนก ดีไซน์เบาเนียนไร้ขอบ ติดง่าย ไม่หลุดระหว่างวัน",
        images: [
   "https://live.staticflickr.com/65535/53591340240_9a1cc2a43b_m.jpg",
          "https://live.staticflickr.com/65535/53591338925_4f8d0c7a7b_m.jpg",
          "https://live.staticflickr.com/65535/53591339825_0c09b24e61_m.jpg",
          "https://live.staticflickr.com/65535/53591339785_ba5b4e2a95_m.jpg",
          "https://live.staticflickr.com/65535/53591109953_4e5b6bda62_m.jpg",
          "https://live.staticflickr.com/65535/53591109938_c4b9a1b6ca_m.jpg",
          "https://live.staticflickr.com/65535/53591339775_2f2f9b1f1f_m.jpg",
          "https://live.staticflickr.com/65535/53591109963_3e9f7e1a3f_m.jpg"
        ]
      }
    ]
  },
  {
    name: "กลุ่มแผ่นปิด/แปะ/สติ๊กเกอร์",
    products: [
      {
        id: "cover1",
        name: "ซิลิโคนปิดจุกกาว",
        price: 59,
        colors: ["เนื้อ", "ดำ"],
        sizes: [],
        desc: "ซิลิโคนปิดจุกแบบมีกาว เนียนแนบ กระชับ ติดทนนาน กันโป๊มั่นใจ! เหมาะกับทุกชุด เปิดไหล่ แฟชั่นเกาะอก หรือชุดราตรี",
        images: [
         "https://live.staticflickr.com/65535/53591339685_4f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590972786_7b3e1e1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591339575_3b3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591339660_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591109908_1e3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591109903_7a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591109913_8b3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591339805_5a3dbe1a4f_m.jpg"
        ]
      },
      {
        id: "cover2",
        name: "ซิลิโคนปิดจุก ไร้กาว",
        price: 79,
        colors: ["เนื้อ", "ดำ"],
        sizes: [],
        desc: "ซิลิโคนปิดจุกแบบไร้กาว ใส่สบาย ไม่ระคายเคือง เหมาะกับสาวผิวแพ้ง่าย ไม่หลุดระหว่างวัน ใช้ซ้ำได้",
        images: [
        "https://live.staticflickr.com/65535/53590973026_7720c686s1_m.jpg",
          "https://live.staticflickr.com/65535/53591110003_8f6b6e9c4a_m.jpg",
          "https://live.staticflickr.com/65535/53591110053_1e3e5d9a7a_m.jpg",
          "https://live.staticflickr.com/65535/53591339660_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973041_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973056_7a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591110063_5a3dbe1a4f_m.jpg"
        ]
      },
      {
        id: "cover3",
        name: "ซิลิโคนปิดจุกดันทรง",
        price: 49,
        colors: ["เนื้อ"],
        sizes: ["A/B", "C/D"],
        desc: "ซิลิโคนปิดจุกดันทรง เสริมทรงสวย ดูเป็นธรรมชาติ เนียนแนบผิว ใส่สบาย ไม่โป๊ เหมาะกับทุกชุด ทั้งชุดออกงานและชุดประจำวัน มี 2 ขนาด (A/B 49 บาท, C/D 69 บาท)",
        images: [
        "https://live.staticflickr.com/65535/53590972876_2a6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53591109953_4e5b6bda62_m.jpg",
          "https://live.staticflickr.com/65535/53590972921_7c8e3d9f3a_m.jpg",
          "https://live.staticflickr.com/65535/53590972891_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591110078_8a2a813fdd_m.jpg",
          "https://live.staticflickr.com/65535/53591339180_3b6e2b5f1a_m.jpg",
          "https://live.staticflickr.com/65535/53590972936_5a3dbe1a4f_m.jpg"
        ]
      },
      {
        id: "item2",
        name: "ปิดจุกดันทรง 10 ซม. (C/D)",
        price: 69,
        sizes: ["C", "D"],
        desc: "ปิดจุกดันทรง 10 ซม. สำหรับคัพ C/D เนียนแนบผิว ไม่โป๊!",
        images: [
            "https://live.staticflickr.com/65535/53590972876_2a6b0e7e8b_m.jpg",
          "https://live.staticflickr.com/65535/53591109953_4e5b6bda62_m.jpg",
          "https://live.staticflickr.com/65535/53590972921_7c8e3d9f3a_m.jpg",
          "https://live.staticflickr.com/65535/53590972891_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591110078_8a2a813fdd_m.jpg",
          "https://live.staticflickr.com/65535/53591339180_3b6e2b5f1a_m.jpg",
          "https://live.staticflickr.com/65535/53590972936_5a3dbe1a4f_m.jpg"
        ]
      },
      {
           id: "item3",
        name: "ปิดกาวซิลิโคน",
        price: 59,
        desc: "ปิดจุกแบบกาวซิลิโคน ยึดติดมั่นใจ ไม่เลื่อนหลุด",
        images: [
          "https://live.staticflickr.com/65535/53591339575_3b3dbe1a4f_m.jpg"
        ]
      },
      {
             id: "item5",
        name: "สติ๊กเกอร์ใสกันโป๊ (36 ชิ้น)",
        price: 69,
        desc: "สติ๊กเกอร์ใส 1 กล่องมี 36 ชิ้น กันโป๊ได้มั่นใจ เหมาะกับชุดบาง",
        images: [
          "https://live.staticflickr.com/65535/53591340380_1f3e8d1a3f_m.jpg",
          "https://live.staticflickr.com/65535/53590973161_2a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340405_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53590973176_3b1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53590973191_7a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340430_5a1e8e2d7f_m.jpg"
             ]
      },
      {
        id: "item7",
        name: "สติ๊กเกอร์ยกกระชับหน้าอก + ปิดจุกกระดาษ",
        price: 69,
        desc: "สติ๊กเกอร์ยกกระชับหน้าอก + ปิดจุกกระดาษ สำหรับสาวๆ ที่ต้องการความมั่นใจ",
        images: [
   "https://live.staticflickr.com/65535/53591340480_1e1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340505_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110113_3b1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340530_7a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110128_5a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110143_2a1e8e2d7f_m.jpg"
        ]
      }
    ]
  },
  {
    name: "กลุ่มเทป/แผ่นฟองน้ำ/เสริมหน้าอก",
    products: [
      {
        id: "item8",
        name: "เทปกาวแปะหน้าอก 5 ซม. * 5 เมตร",
        price: 89,
        colors: ["ดำ", "เนื้อ"],
        desc: "เทปกาวแปะหน้าอก ขนาด 5 ซม. * 5 เมตร ยกกระชับหน้าอก เนียนแนบผิว",
        images: [
       "https://live.staticflickr.com/65535/53591110153_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340580_8f6b6e9c4a_m.jpg",
          "https://live.staticflickr.com/65535/53591340605_1e3e5d9a7a_m.jpg",
          "https://live.staticflickr.com/65535/53591340630_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973206_7a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591110173_5a3dbe1a4f_m.jpg"
        ]
      },
      {
        id: "item9",
        name: "เทปกาวแปะหน้าอก แบบใส 5 ซม. * 1 เมตร",
        price: 99,
        desc: "เทปกาวแปะหน้าอกแบบใส ขนาด 5 ซม. * 1 เมตร ไม่เห็นรอยกาว ใช้สำหรับชุดเปิดหลัง",
        images: [
         "https://live.staticflickr.com/65535/53590973221_2a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110183_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110198_1e1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53590973236_3b1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53590973251_7a3dbe1a4f_m.jpg"
        ]
      },
      {
        id: "item10",
        name: "แผ่นฟองน้ำเสริมหน้าอก กาวด้านเดียว (ธรรมดา/หัวใจ)",
        price: 59,
        colors: ["ดำ", "เนื้อ"],
        desc: "แผ่นฟองน้ำเสริมหน้าอก กาวด้านเดียว มีแบบธรรมดา 59.- ทรงหัวใจ 69.- เสริมทรงสวย",
        images: [
          "https://live.staticflickr.com/65535/53590973261_1f3e8d1a3f_m.jpg",
          "https://live.staticflickr.com/65535/53590973271_2a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110213_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340680_1e1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340705_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110228_1e3e5d9a7a_m.jpg",
          "https://live.staticflickr.com/65535/53591110233_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973286_7a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973291_5a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973296_1f3e8d1a3f_m.jpg"
        ]
      },
      {
        id: "item11",
        name: "ฟองน้ำดันทรงกาว 2 ด้าน (Nanny Bra)",
        price: 179,
        colors: ["ดำ", "เนื้อ"],
        sizes: ["A/B", "C/D"],
        desc: "ฟองน้ำดันทรงกาว 2 ด้าน สำหรับคัพ A/B หรือ C/D เพิ่มความอึ๋ม มั่นใจ",
        images: [
           "https://live.staticflickr.com/65535/53591340730_8f6b6e9c4a_m.jpg",
          "https://live.staticflickr.com/65535/53591340755_1e3e5d9a7a_m.jpg",
          "https://live.staticflickr.com/65535/53591340780_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973301_7a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973306_5a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591110248_1f3e8d1a3f_m.jpg",
          "https://live.staticflickr.com/65535/53591110253_2a1e8e2d7f_m.jpg"
        ]
      },
      {
        id: "item12",
        name: "แผ่นซิลิโคนปิดเป้า แบบใส S/L",
        price: 99,
        sizes: ["S", "L"],
        desc: "แผ่นซิลิโคนปิดเป้า แบบใส ไซส์ S และ L สาวๆ ใส่บิกินี่มั่นใจ",
        images: [
          "https://live.staticflickr.com/65535/53591110263_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340805_1e1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340830_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110278_1e3e5d9a7a_m.jpg",
          "https://live.staticflickr.com/65535/53591110283_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973311_7a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973316_5a3dbe1a4f_m.jpg"
        ]
      }
    ]
  },
  {
    name: "กลุ่มกางเกง/สายเดี่ยว",
    products: [
      {
        id: "pant1",
        name: "กางเกงซับในไร้ขอบ",
        price: 49,
        colors: ["เนื้อ", "ดำ", "ชมพู"],
        desc: "กางเกงซับในไร้ขอบ เนื้อผ้านุ่ม ใส่สบาย ไม่อึดอัด เหมาะกับทุกชุด",
        images: [
          "https://live.staticflickr.com/65535/53591340855_8f6b6e9c4a_m.jpg",
          "https://live.staticflickr.com/65535/53591340880_1e3e5d9a7a_m.jpg",
          "https://live.staticflickr.com/65535/53591340905_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973321_7a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973326_5a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591110298_1f3e8d1a3f_m.jpg",
          "https://live.staticflickr.com/65535/53591110303_2a1e8e2d7f_m.jpg"
        ]
      },
      {
        id: "strap1",
        name: "สายเดี่ยว ทรงเกาะอก ไร้ขอบ",
        price: 59,
        colors: ["เนื้อ", "ดำ", "ชมพู", "เทา"],
        desc: "สายเดี่ยวสวยเรียบหรู ใส่กับชุดได้ทุกสไตล์ ผ้านุ่ม ไม่ระคายเคือง",
        images: [
          "https://live.staticflickr.com/65535/53591110313_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340930_1e1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591340955_8a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110328_1e3e5d9a7a_m.jpg",
          "https://live.staticflickr.com/65535/53591110333_2f3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973331_7a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53590973336_5a3dbe1a4f_m.jpg",
          "https://live.staticflickr.com/65535/53591110348_1f3e8d1a3f_m.jpg",
          "https://live.staticflickr.com/65535/53591110353_2a1e8e2d7f_m.jpg",
          "https://live.staticflickr.com/65535/53591110358_8a1e8e2d7f_m.jpg"
        ]
      }
    ]
  }
];

function findProduct(id) {
  for (const group of PRODUCT_GROUPS) {
    for (const prod of group.products) {
      if (prod.id === id) {
        return prod;
      }
    }
  }
  return null;
}

function renderProducts() {
  const section = document.getElementById('products-section');
  section.innerHTML = "";
  PRODUCT_GROUPS.forEach(group => {
    section.innerHTML += `<div class="product-group-title">${group.name}</div>`;
    group.products.forEach(prod => {
      section.innerHTML += `
      <div class="product-card">
        <div class="gallery-container">
          <img id="main-${prod.id}" src="${prod.images[0]}" class="main-img" alt="${prod.name}">
          <div class="gallery-controls">
            <button onclick="prevImg('${prod.id}')">◀️</button>
            <span id="imgIndex-${prod.id}">1/${prod.images.length}</span>
            <button onclick="nextImg('${prod.id}')">▶️</button>
          </div>
          <div class="thumbnails" id="thumbs-${prod.id}">
            ${prod.images.map((img, i) => `<img src="${img}" class="thumb" onclick="showImg('${prod.id}',${i})">`).join('')}
          </div>
        </div>
        <h3>${prod.name}</h3>
        <p>${prod.desc}</p>
        <p class="price">ราคา ${prod.price} บาท</p>
        <div class="options">
          ${prod.colors && prod.colors.length ? `
            <label>สี:</label>
            <select id="color-${prod.id}">
              ${prod.colors.map(c => `<option value="${c}">${c}</option>`).join("")}
            </select>` : ""}
          ${prod.sizes && prod.sizes.length ? `
            <label>ไซส์:</label>
            <select id="size-${prod.id}">
              ${prod.sizes.map(s => `<option value="${s}">${s}</option>`).join("")}
            </select>` : ""}
          <label>จำนวน:</label>
          <input type="number" min="1" value="1" id="qty-${prod.id}" class="qty-input">
        </div>
        <button class="add-cart-btn" onclick="addToCart('${prod.id}')">ใส่ตะกร้า</button>
      </div>
      `;
    });
  });
  window.galleryState = {};
  PRODUCT_GROUPS.forEach(g => g.products.forEach(prod => {
    galleryState[prod.id] = { idx: 0, images: prod.images };
    showImg(prod.id, 0);
  }));
}
window.renderProducts = renderProducts;

function showImg(id, i) {
  const prod = findProduct(id);
  if (!prod) return;
  const mainImg = document.getElementById('main-' + id);
  const imgIndexSpan = document.getElementById('imgIndex-' + id);
  const thumbs = document.querySelectorAll(`#thumbs-${id} .thumb`);

  if (mainImg) {
    mainImg.src = prod.images[i];
  }
  if (imgIndexSpan) {
    imgIndexSpan.textContent = (i + 1) + '/' + prod.images.length;
  }
  if (thumbs.length) {
    thumbs.forEach(thumb => thumb.classList.remove('active'));
    thumbs[i].classList.add('active');
  }
  window.galleryState[id].idx = i;
}

function prevImg(id) {
  const prod = findProduct(id);
  if (!prod) return;
  let st = window.galleryState[id];
  st.idx = (st.idx - 1 + st.images.length) % st.images.length;
  showImg(id, st.idx);
}
function nextImg(id) {
  const prod = findProduct(id);
  if (!prod) return;
  let st = window.galleryState[id];
  st.idx = (st.idx + 1) % st.images.length;
  showImg(id, st.idx);
}

document.addEventListener("DOMContentLoaded", renderProducts);

let cart = [];
function addToCart(productId) {
  const prod = findProduct(productId);
  if (!prod) return;
  const color = prod.colors && prod.colors.length ? document.getElementById("color-"+productId).value : "";
  const size = prod.sizes && prod.sizes.length ? document.getElementById("size-"+productId).value : "";
  let qty = parseInt(document.getElementById("qty-"+productId).value, 10);
  if (!qty || qty < 1) qty = 1;
  const index = cart.findIndex(item =>
    item.productId === productId && item.color === color && item.size === size
  );
  if (index > -1) {
    cart[index].qty += qty;
  } else {
    cart.push({ productId, color, size, qty });
  }
  renderCart();
}
function renderCart() {
  const cartList = document.getElementById("cart-list");
  cartList.innerHTML = "";
  let total = 0;
  cart.forEach((item, idx) => {
    const prod = findProduct(item.productId);
    if (!prod) return;
    total += prod.price * item.qty;
    const prodImg = prod.images[0];
    cartList.innerHTML += `
      <div class="cart-item">
        <img src="${prodImg}" alt="${prod.name}" width="50">
        <span>${prod.name}${item.color ? " ("+item.color+")" : ""}${item.size ? " / "+item.size : ""} x ${item.qty}</span>
        <span>${prod.price * item.qty} บาท</span>
        <button onclick="changeQty(${idx}, -1)">-</button>
        <button onclick="changeQty(${idx}, 1)">+</button>
        <button onclick="removeCartItem(${idx})">ลบ</button>
      </div>
    `;
  });
  let shipping = total >= 100 ? 0 : (cart.length > 0 ? 15 : 0);
  document.getElementById("cart-total").innerHTML = `
    <strong>รวม: ${total} บาท</strong> + ค่าส่ง: ${shipping} บาท
    <br><strong>ยอดสุทธิ: ${total + shipping} บาท</strong>
  `;
}
function changeQty(idx, delta) {
  cart[idx].qty += delta;
  if (cart[idx].qty < 1) cart[idx].qty = 1;
  renderCart();
}
function removeCartItem(idx) {
  cart.splice(idx, 1);
  renderCart();
}
document.getElementById("checkout-btn").onclick = function() {
  if (cart.length === 0) {
    alert("กรุณาเลือกสินค้าใส่ตะกร้าก่อนค่ะ");
    return;
  }
  document.getElementById("customer-form-section").style.display = "block";
  window.scrollTo(0, document.getElementById("customer-form-section").offsetTop);
};
document.getElementById("customer-form").onsubmit = function(e) {
  e.preventDefault();
  const fd = new FormData(this);
  const customer = {
    name: fd.get("name"),
    address: fd.get("address"),
    phone: fd.get("phone"),
    zipcode: fd.get("zipcode")
  };
  let msg = `🩷 ออเดอร์ใหม่ T & P BRA Bangsaen Shop 🩷\n`;
  msg += `ชื่อ: ${customer.name}\nที่อยู่: ${customer.address}\nเบอร์: ${customer.phone}\nรหัสไปรษณีย์: ${customer.zipcode}\n\n`;
  msg += `รายการสินค้า:\n`;
  cart.forEach(item => {
    const prod = findProduct(item.productId);
    if (prod)
      msg += `${prod.name}${item.color ? " ("+item.color+")" : ""}${item.size ? " / "+item.size : ""} x ${item.qty} = ${prod.price * item.qty} บาท\n`;
  });
  let total = cart.reduce((sum, item) => {
    const prod = findProduct(item.productId);
    return sum + (prod ? prod.price * item.qty : 0);
  }, 0);
  let shipping = total >= 100 ? 0 : 15;
  msg += `รวมทั้งสิ้น ${total + shipping} บาท (ค่าส่ง ${shipping} บาท)\n`;
  const lineUrl = "https://lin.ee/NZfUsZ3";
  const sendUrl = `https://line.me/R/msg/text/?${encodeURIComponent(msg + '\nติดต่อร้าน: ' + lineUrl)}`;
  window.open(sendUrl, "_blank");
  alert("ส่งออเดอร์ไปที่ LINE แล้วค่ะ");
};
document.addEventListener("DOMContentLoaded", renderCart);
  </script>
</body>
</html>
