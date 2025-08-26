<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>T & P BRA Bangsaen Shop | ร้านบรา & ไอเท็มเด็ดสำหรับสาวๆ</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- ฟอนต์ Google สำหรับภาษาไทย -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@400;700&display=swap" rel="stylesheet">
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
.product-card {
  background: #fff;
  border: 1px solid #ffe4f0;
  border-radius: 12px;
  box-shadow: 0 2px 8px #f9e6ef33;
  width: 320px;
  padding: 1rem;
  text-align: center;
  transition: box-shadow .2s;
  margin: 1.2rem auto;
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
.thumb:hover {
  border-color: #d1005d;
}
@media (max-width: 900px) {
  .product-card { width: 95%; }
}
@media (max-width: 600px) {
  .product-card { width: 100%; }
  #cart-section, #customer-form-section { margin: 1rem 0; }
  .main-img { max-width: 98vw; }
}
  </style>
</head>
<body>
  <header>
    <h1>✨🩷 T & P BRA Bangsaen Shop 🩷✨</h1>
    <p>ร้านบรา & ไอเท็มเด็ดสำหรับสาวๆ<br>
    บราไร้สาย บราปีกนก บราดูม บราแปะ แผ่นซิลิโคนกันโป๊ แผ่นดันทรง และอีกเพียบ!!</p>
    <ul>
      <li>ใส่สบาย ไม่เจ็บ ไม่อึดอัด</li>
      <li>มีหลายแบบให้เลือก ใส่กับเสื้อผ้าได้ทุกสไตล์</li>
      <li>ราคาเริ่มต้นแค่ 49 บาท เท่านั้น!</li>
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
      <!-- สินค้าจะแสดงจาก JS -->
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
const PRODUCTS = [
  // กลุ่มบราทรงต่างๆ
  {
    id: "bra1",
    name: "บราทรงกลมไร้ขอบ",
    price: 69,
    images: [
      "https://drive.google.com/uc?export=view&id=1ITb0vp1alC6h-NfFvjTaqDuNI7B8FT-3",
      "https://drive.google.com/uc?export=view&id=1oSxvKg-h3_imn9AUJ6GNf2w_g1lkC5p3"
    ],
    colors: ["ดำ", "เนื้อ", "ขาว"],
    sizes: ["A", "B", "C", "D"],
    desc: "บราไร้ขอบ สัมผัสนุ่ม ไม่บีบรัด รูปทรงกลม สวยเรียบหรู ใส่สบายทุกชุด เหมาะกับสาวๆ ทุกสไตล์"
  },
  {
    id: "bra2",
    name: "บราดูมดูม หนา 3 ซม.",
    price: 99,
    images: [
      "https://drive.google.com/uc?export=view&id=1JiVgzjFEuZyYn244o5leGT6xRVkdzGJB"
    ],
    colors: ["ดำ", "เนื้อ"],
    sizes: ["A", "B", "C", "D"],
    desc: "บราเสริมทรงหนา 3 ซม. ดันอกให้ดูมขึ้น ใส่แล้วมั่นใจ สวยโดดเด่นทุกสไตล์"
  },
  {
    id: "bra3",
    name: "บราลูกไม้ บราเจ้าสาว",
    price: 89,
    images: [
      "https://drive.google.com/uc?export=view&id=1hubGD2Qci7llZxb1fzr_FggmfxROooqJ"
    ],
    colors: ["ดำ", "เนื้อ", "ขาว"],
    sizes: ["A", "B", "C", "D"],
    desc: "บราเจ้าสาวหรูหราด้วยลูกไม้พร้อมสายใส แถมฟรี 1 เส้น ใส่แล้วดูสวยหวานและมีเสน่ห์"
  },
  {
    id: "bra4",
    name: "บราปีกผีเสื้อ เชือกหน้า",
    price: 79,
    images: [
      "https://drive.google.com/uc?export=view&id=1NkJLDW1Ce2dBgUajzbhjTEHBkH-Smznt"
    ],
    colors: ["ดำ", "เนื้อ", "ขาว"],
    sizes: ["A", "B", "C", "D"],
    desc: "บราปีกผีเสื้อทรงสวย ดึงเชือกหน้าเพื่อปรับเข้ารูป เนียนแนบกับผิว สวยมั่นใจ"
  },
  {
    id: "bra5",
    name: "บรากาวแผ่นดันทรง",
    price: 79,
    images: [
      "https://drive.google.com/uc?export=view&id=1XnQcPz2NfVFowESvuzv46pN_tZooBjlV"
    ],
    colors: ["ดำ", "เนื้อ"],
    sizes: ["A", "B", "C", "D"],
    desc: "บรากาวแผ่นดันทรง ใช้ง่าย ติดแน่น เนียนเรียบทุกชุด เหมาะกับเสื้อผ้าเปิดหลังหรือเกาะอก"
  },
  {
    id: "bra6",
    name: "บราปีกนก",
    price: 59,
    images: [
      "https://drive.google.com/uc?export=view&id=13xGnEZJ8DJXLtqT1CUGUzExCLJGWnXi1"
    ],
    colors: ["ดำ", "เนื้อ"],
    sizes: ["A", "B", "C", "D"],
    desc: "บราปีกนก ดีไซน์เบาเนียนไร้ขอบ ติดง่าย ไม่หลุดระหว่างวัน"
  },
  // กลุ่มแผ่นปิด/แปะ/สติ๊กเกอร์
  {
    id: "item1",
    name: "ปิดจุกดันทรง 6.5 ซม. (A/B)",
    price: 49,
    images: [
      "https://drive.google.com/uc?export=view&id=1B8R4J8qrEmJpsoSrSUroFnwP2yS040D-"
    ],
    sizes: ["A", "B"],
    desc: "ปิดจุกดันทรง 6.5 ซม. สำหรับคัพ A/B เนียนแนบผิว ไม่โป๊!"
  },
  {
    id: "item2",
    name: "ปิดจุกดันทรง 10 ซม. (C/D)",
    price: 69,
    images: [
      "https://drive.google.com/uc?export=view&id=1FwMo4pK4qntWZTWLOP-hFKPo4MG-EW3a"
    ],
    sizes: ["C", "D"],
    desc: "ปิดจุกดันทรง 10 ซม. สำหรับคัพ C/D เนียนแนบผิว ไม่โป๊!"
  },
  {
    id: "item3",
    name: "ปิดกาวซิลิโคน",
    price: 59,
    images: [
      "https://drive.google.com/uc?export=view&id=1bfWRNGLr-QnPwbhoY-6mU_oFosnAgH_n"
    ],
    desc: "ปิดจุกแบบกาวซิลิโคน ยึดติดมั่นใจ ไม่เลื่อนหลุด"
  },
  {
    id: "item4",
    name: "ปิดจุกไร้กาว",
    price: 79,
    images: [
      "https://drive.google.com/uc?export=view&id=1EGHWh5zcn0ZSM0YvwPLbYW2xZTPQMcUz"
    ],
    desc: "ปิดจุกไร้กาว เนียนนุ่ม ไม่ระคายเคือง ผิวแพ้ง่ายใช้ได้"
  },
  {
    id: "item5",
    name: "สติ๊กเกอร์ใสกันโป๊ (36 ชิ้น)",
    price: 69,
    images: [
      "https://drive.google.com/uc?export=view&id=1gEjLgYePD_-qvDGK83uGJBffgyGKZMaU"
    ],
    desc: "สติ๊กเกอร์ใส 1 กล่องมี 36 ชิ้น กันโป๊ได้มั่นใจ เหมาะกับชุดบาง"
  },
  {
    id: "item6",
    name: "แผ่นแปะซิลิโคนใส",
    price: 59,
    images: [
      "https://drive.google.com/uc?export=view&id=1qVSDduuEZiMddGkW874ox9dSc3JzuaTI"
    ],
    desc: "แผ่นแปะซิลิโคนใสสำหรับกันโป๊ ติดแนบเนียน ถอดล้างใช้ซ้ำได้"
  },
  {
    id: "item7",
    name: "สติ๊กเกอร์ยกกระชับหน้าอก + ปิดจุกกระดาษ",
    price: 69,
    images: [
      "https://drive.google.com/uc?export=view&id=1aGNGe99jAE4ziarhBaxY9mQJHOnChYgd"
    ],
    desc: "สติ๊กเกอร์ยกกระชับหน้าอก + ปิดจุกกระดาษ สำหรับสาวๆ ที่ต้องการความมั่นใจ"
  },
  // กลุ่มเทป/แผ่นฟองน้ำ/นวัตกรรมเสริมทรง
  {
    id: "item8",
    name: "เทปกาวแปะหน้าอก 5 ซม. * 5 เมตร",
    price: 89,
    images: [
      "https://drive.google.com/uc?export=view&id=1Urm_GJKnjw_jeqVFKBzZp_o1AxZ_Lj62"
    ],
    colors: ["ดำ", "เนื้อ"],
    desc: "เทปกาวแปะหน้าอก ขนาด 5 ซม. * 5 เมตร ยกกระชับหน้าอก เนียนแนบผิว"
  },
  {
    id: "item9",
    name: "เทปกาวแปะหน้าอก แบบใส 5 ซม. * 1 เมตร",
    price: 99,
    images: [
      "https://drive.google.com/uc?export=view&id=1wjxakui82JZ1Ievb3UHCjnuMEA8KI7PD"
    ],
    desc: "เทปกาวแปะหน้าอกแบบใส ขนาด 5 ซม. * 1 เมตร ไม่เห็นรอยกาว ใช้สำหรับชุดเปิดหลัง"
  },
  {
    id: "item10",
    name: "แผ่นฟองน้ำเสริมหน้าอก กาวด้านเดียว (ธรรมดา/หัวใจ)",
    price: 59,
    images: [
      "https://drive.google.com/uc?export=view&id=1ukvvTP8g4cKZMUmZN_UauAiy4F05_ItA"
    ],
    colors: ["ดำ", "เนื้อ"],
    desc: "แผ่นฟองน้ำเสริมหน้าอก กาวด้านเดียว มีแบบธรรมดา 59.- ทรงหัวใจ 69.- เสริมทรงสวย"
  },
  {
    id: "item11",
    name: "ฟองน้ำดันทรงกาว 2 ด้าน (Nanny Bra)",
    price: 179,
    images: [
      "https://drive.google.com/uc?export=view&id=1Al6hy9_UCzOVv4mnI9EWM7WjJt8jrS-U"
    ],
    colors: ["ดำ", "เนื้อ"],
    sizes: ["A/B", "C/D"],
    desc: "ฟองน้ำดันทรงกาว 2 ด้าน สำหรับคัพ A/B หรือ C/D เพิ่มความอึ๋ม มั่นใจ"
  },
  {
    id: "item12",
    name: "แผ่นซิลิโคนปิดเป้า แบบใส S/L",
    price: 99,
    images: [
      "https://drive.google.com/uc?export=view&id=1ECN0AkVwZ8PWbYSZviFSOYFQoe6D6xY9"
    ],
    sizes: ["S", "L"],
    desc: "แผ่นซิลิโคนปิดเป้า แบบใส ไซส์ S และ L สาวๆ ใส่บิกินี่มั่นใจ"
  },
  // กลุ่มกางเกง/สายเดี่ยว
  {
    id: "pant1",
    name: "กางเกงซับในไร้ขอบ",
    price: 49,
    images: [
      "https://drive.google.com/uc?export=view&id=1YXabYxW3dA8ktFeCd1nKwxjIU2JLmMBt"
    ],
    colors: ["เนื้อ", "ดำ", "ชมพู"],
    desc: "กางเกงซับในไร้ขอบ เนื้อผ้านุ่ม ใส่สบาย ไม่อึดอัด เหมาะกับทุกชุด"
  },
  {
    id: "strap1",
    name: "สายเดี่ยว ทรงเกาะอก ไร้ขอบ",
    price: 59,
    images: [
      "https://drive.google.com/uc?export=view&id=1lroD3vu2eyRfydARtQnCpU5niLuNbV-Z"
    ],
    colors: ["เนื้อ", "ดำ", "ชมพู", "เทา"],
    desc: "สายเดี่ยวสวยเรียบหรู ใส่กับชุดได้ทุกสไตล์ ผ้านุ่ม ไม่ระคายเคือง"
  }
];

function renderProducts() {
  const section = document.getElementById('products-section');
  section.innerHTML = "";
  // แบ่งกลุ่มสินค้า
  const groups = [
    { name: "บราทรงต่างๆ", ids: ["bra1", "bra2", "bra3", "bra4", "bra5", "bra6"] },
    { name: "แผ่นปิด & สติ๊กเกอร์", ids: ["item1", "item2", "item3", "item4", "item5", "item6", "item7"] },
    { name: "เทป/ฟองน้ำ/นวัตกรรมเสริมทรง", ids: ["item8", "item9", "item10", "item11", "item12"] },
    { name: "กางเกง/สายเดี่ยว", ids: ["pant1", "strap1"] }
  ];
  groups.forEach(g => {
    section.innerHTML += `<h2 style="margin-top:2em;color:#d1005d;">${g.name}</h2>`;
    g.ids.forEach(id => {
      const prod = PRODUCTS.find(p => p.id === id);
      if (!prod) return;
      section.innerHTML += `
      <div class="product-card">
        <div class="gallery-container">
          <img id="main-${prod.id}" src="${prod.images[0]}" class="main-img" alt="${prod.name}">
          <div class="gallery-controls">
            <button onclick="prevImg('${prod.id}')">◀️</button>
            <span id="imgIndex-${prod.id}">1/${prod.images.length}</span>
            <button onclick="nextImg('${prod.id}')">▶️</button>
          </div>
          <div class="thumbnails">
            ${prod.images.map((img, i) => `<img src="${img}" class="thumb" onclick="showImg('${prod.id}',${i})">`).join('')}
          </div>
        </div>
        <h3>${prod.name}</h3>
        <p>${prod.desc}</p>
        <p class="price">ราคา ${prod.price} บาท</p>
        <div class="options">
          ${prod.colors ? `
            <label>สี:</label>
            <select id="color-${prod.id}">
              ${prod.colors.map(c => `<option value="${c}">${c}</option>`).join("")}
            </select>` : ""}
          ${prod.sizes ? `
            <label>ไซส์:</label>
            <select id="size-${prod.id}">
              ${prod.sizes.map(s => `<option value="${s}">${s}</option>`).join("")}
            </select>` : ""}
          <label>จำนวน:</label>
          <input type="number" min="1" value="1" id="qty-${prod.id}">
        </div>
        <button class="add-cart-btn" onclick="addToCart('${prod.id}')">ใส่ตะกร้า</button>
      </div>
    `;
    });
  });
  window.galleryState = {};
  PRODUCTS.forEach(prod => {
    window.galleryState[prod.id] = { idx: 0, images: prod.images };
    showImg(prod.id, 0);
  });
}
window.renderProducts = renderProducts;

function showImg(id, i) {
  window.galleryState[id].idx = i;
  document.getElementById('main-' + id).src = window.galleryState[id].images[i];
  document.getElementById('imgIndex-' + id).textContent = (i+1) + '/' + window.galleryState[id].images.length;
}
function prevImg(id) {
  let st = window.galleryState[id];
  st.idx = (st.idx + st.images.length - 1) % st.images.length;
  showImg(id, st.idx);
}
function nextImg(id) {
  let st = window.galleryState[id];
  st.idx = (st.idx + 1) % st.images.length;
  showImg(id, st.idx);
}

document.addEventListener("DOMContentLoaded", function() {
  renderProducts();
  renderCart();
});

let cart = [];
function addToCart(productId) {
  const prod = PRODUCTS.find(p => p.id === productId);
  if (!prod) return;
  const color = prod.colors ? document.getElementById(`color-${productId}`).value : "";
  const size = prod.sizes ? document.getElementById(`size-${productId}`).value : "";
  let qty = parseInt(document.getElementById(`qty-${productId}`).value, 10);
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
    const prod = PRODUCTS.find(p => p.id === item.productId);
    if (!prod) return;
    total += prod.price * item.qty;
    cartList.innerHTML += `
      <div class="cart-item">
        <img src="${prod.images[0]}" alt="${prod.name}" width="50">
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
  window.scrollTo({ top: document.getElementById("customer-form-section").offsetTop, behavior: "smooth" });
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
    const prod = PRODUCTS.find(p => p.id === item.productId);
    if (prod)
      msg += `${prod.name}${item.color ? " ("+item.color+")" : ""}${item.size ? " / "+item.size : ""} x ${item.qty} = ${prod.price * item.qty} บาท\n`;
  });
  let total = cart.reduce((sum, item) => {
    const prod = PRODUCTS.find(p => p.id === item.productId);
    return sum + (prod ? prod.price * item.qty : 0);
  }, 0);
  let shipping = total >= 100 ? 0 : 15;
  msg += `รวมทั้งสิ้น ${total + shipping} บาท (ค่าส่ง ${shipping} บาท)\n`;
  const lineUrl = `https://lin.ee/NZfUsZ3`;
  const sendUrl = `https://line.me/R/msg/text/?${encodeURIComponent(msg + '\nติดต่อร้าน: ' + lineUrl)}`;
  window.open(sendUrl, "_blank");
  alert("ส่งออเดอร์ไปที่ LINE แล้วค่ะ");
};
  </script>
</body>
</html>
