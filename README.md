# levia-website
<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Le Via Shampoo</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header class="site-header">
    <div class="logo">
        <a href="#">Le Via</a>
    </div>
    <nav class="main-nav">
        <a href="#products">สินค้า</a>
        <a href="#benefits">จุดเด่น</a>
        <a href="#about">เกี่ยวกับ</a>
        <a href="#contact">ติดต่อ</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-copy">
        <span class="eyebrow">แชมพูสมุนไพรเพื่อผมสุขภาพดี</span>
        <h1>ขจัดรังแคบำรุงรากผมและหนังศีรษะเพื่อสุขภาพผมให้แข็งแรง</h1>
        <p>สูตรอ่อนโยนจากธรรมชาติ ช่วยลดผมร่วง ให้ผมนุ่มลื่น มีน้ำหนัก และไม่ทำให้หนังศีรษะแห้ง</p>
        <div class="hero-actions">
            <a href="#products" class="button primary">เลือกซื้อสินค้า</a>
            <a href="#benefits" class="button secondary">ทำไมต้อง Le Via</a>
        </div>
    </div>
    <div class="hero-image">
        <img src="https://via.placeholder.com/620x520?text=Le+Via+Shampoo" alt="Le Via Shampoo">
    </div>
</section>

<section class="brand-story" id="about">
    <div class="section-title">
        <span>อัครมหากาพย์</span>
        <h2>คัมภีร์ยุทธศาสตร์ Le Via</h2>
    </div>
    <div class="brand-copy">
        <article>
            <h3>ที่มาของแบรนด์</h3>
            <p>ในยุคสมัยที่อุตสาหกรรมความงามถูกครอบงำด้วยสารเคมีสังเคราะห์ที่เน้นความรวดเร็วแต่ทิ้งผลกระทบระยะยาวต่อสุขภาพ Le Via ถือกำเนิดขึ้นจากความเชื่อที่ว่า "ธรรมชาติมีคำตอบที่สมบูรณ์แบบที่สุดเสมอ"</p>
            <p>เราไม่ได้มองหาเพียงแค่ส่วนผสมที่ใช้สระผม แต่เรามองหา "จิตวิญญาณแห่งการเยียวยา" ที่หยั่งรากลึกในผืนดินไทย คราม (Indigo) ไม่ได้เป็นเพียงวัถตุดิบสำหรับการย้อมผ้าที่สืบทอดมานับพันปี แต่คือพฤกษาศาสตร์ที่บรรจุพลังแห่งการต้านการอักเสบและเม็ดสีที่บริสุทธิ์ที่สุด</p>
            <p>เรานำความลับนี้มาสกัดด้วยนวัตกรรม Advanced Bio-Extraction เพื่อดึงสาร Indirubin และ Flavonoids ออกมาในรูปแบบโมเลกุลที่เล็กที่สุด เพื่อให้สามารถแทรกซึมเข้าสู่แกนผมและดูแลหนังศีรษะได้อย่างล้ำลึก</p>
            <p>Le Via จึงไม่ใช่แค่ผลิตภัณฑ์ แต่คือ "พันธสัญญา" ระหว่างอดีตที่อ่อนโยนกับอนาคตที่ยั่งยืน เราคือจุดบรรจบของภูมิปัญญาชาวบ้านและวิทยาศาสตร์ระดับสากล เพื่อส่งมอบนิยามใหม่ของความหรูหราที่มาพร้อมกับความปลอดภัย (Safety is the New Luxury)</p>
        </article>
    </div>
</section>

<section class="store" id="products">
    <div class="products-panel">
        <div class="section-title">
            <span>สินค้า</span>
            <h2>คอลเลคชันแชมพูฟื้นฟูเส้นผม</h2>
        </div>
        <div class="products-grid" id="productsGrid"></div>
    </div>

    <aside class="cart" id="cart">
        <h2>ตะกร้าสินค้า</h2>
        <div id="cartItems" class="cart-items">
            <p>ยังไม่มีสินค้าในตะกร้า</p>
        </div>
        <p class="cart-total">ยอดรวม: <span id="cartTotal">0</span> บาท</p>
        <button id="checkoutButton" class="checkout-button">สั่งซื้อเลย</button>
    </aside>
</section>

<section class="benefits" id="benefits">
    <div class="section-title">
        <span>ทำไมต้องเลือก</span>
        <h2>จุดเด่นของ Le Via</h2>
    </div>
    <div class="benefit-grid">
        <div class="benefit-card">
            <h3>ลดผมร่วง</h3>
            <p>สารสกัดสมุนไพรช่วยบำรุงรากผมให้แข็งแรง ลดปัญหาผมร่วงและบาง</p>
        </div>
        <div class="benefit-card">
            <h3>อ่อนโยนต่อหนังศีรษะ</h3>
            <p>สูตรไม่มีสาร SLS, Silicone, พาราเบน เหมาะกับทุกสภาพผม</p>
        </div>
        <div class="benefit-card">
            <h3>ผมสวยมีน้ำหนัก</h3>
            <p>บำรุงลึกถึงเส้นผม ช่วยให้ผมนุ่มลื่น มีวอลลุ่มและสุขภาพดี</p>
        </div>
    </div>
</section>

<section class="about" id="about">
    <div class="about-card">
        <h2>Le Via คืออะไร?</h2>
        <p>Le Via มุ่งมั่นสร้างแชมพูสูตรสมุนไพรไทย ที่เหมาะกับทั้งชายและหญิง เน้นความปลอดภัย พร้อมคุณค่าบำรุงผมจากธรรมชาติ</p>
    </div>
</section>

<section class="contact" id="contact">
    <div class="section-title">
        <span>ติดต่อเรา</span>
        <h2>สอบถามหรือสั่งซื้อ</h2>
    </div>
    <div class="contact-cards">
        <div>
            <h3>Line</h3>
            <p>@levia</p>
        </div>
        <div>
            <h3>Facebook</h3>
            <p>Le Via</p>
        </div>
        <div>
            <h3>โทร</h3>
            <p>099-999-9999</p>
        </div>
    </div>
</section>

<section class="mini-contact">
    <div class="mini-contact-card">
        <div>
            <strong>ติดต่อด่วน</strong>
            <p>บริการลูกค้าและสั่งซื้อผ่าน Line หรือโทรทันที</p>
        </div>
        <a href="https://line.me/R/ti/p/%40levia" target="_blank" rel="noreferrer">Line: @levia</a>
        <a href="tel:0999999999">โทร: 099-999-9999</a>
    </div>
</section>

<footer>
    <p>© 2026 Le Via. สินค้าสมุนไพรแท้ เพื่อผมสวยทุกวัน</p>
</footer>

<script src="script.js"></script>
</body>
</html>
