<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>การหาค่าอนุพันธ์ของฟังก์ชันจากบทนิยามและอัตราสัมพัทธ์</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>การหาค่าอนุพันธ์ของฟังก์ชันจากบทนิยามและอัตราสัมพัทธ์</h1>
        <section class="content">
            <h2>การหาค่าอนุพันธ์จากบทนิยาม</h2>
            <p>อนุพันธ์ของฟังก์ชัน f(x) ที่จุด x = a สามารถหาได้จากลิมิตของผลต่างอัตราส่วนเมื่อ h เข้าสู่ศูนย์ ตามสูตร:</p>
            <p class="formula">f'(a) = lim<sub>h→0</sub> (f(a+h) - f(a)) / h</p>
            <p>ตัวอย่างเช่น ถ้า f(x) = x<sup>2</sup> การหาค่าอนุพันธ์ที่จุด x = 2 คือ:</p>
            <p class="example">f'(2) = lim<sub>h→0</sub> ((2+h)<sup>2</sup> - 2<sup>2</sup>) / h = lim<sub>h→0</sub> (4 + 4h + h<sup>2</sup> - 4) / h = lim<sub>h→0</sub> (4h + h<sup>2</sup>) / h = 4</p>
        </section>

        <section class="content">
            <h2>อัตราสัมพัทธ์</h2>
            <p>อัตราสัมพัทธ์ของการเปลี่ยนแปลงระหว่างสองปริมาณหมายถึงอัตราส่วนของการเปลี่ยนแปลงของปริมาณหนึ่งต่อการเปลี่ยนแปลงของอีกปริมาณหนึ่ง ซึ่งสามารถแสดงในรูปอนุพันธ์ได้ตามสูตร:</p>
            <p class="formula">อัตราสัมพัทธ์ = (dy/dx) / y</p>
            <p>ตัวอย่างเช่น สำหรับฟังก์ชัน y = e<sup>x</sup>, อัตราสัมพัทธ์ของ y ต่อ x คือ:</p>
            <p class="example">(dy/dx) / y = e<sup>x</sup> / e<sup>x</sup> = 1</p>
        </section>
    </div>
</body>
</html>
