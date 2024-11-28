<?php
include 'db_connection.php'; // الاتصال بقاعدة البيانات

// استعلام للحصول على العقارات
$sql = "SELECT * FROM properties WHERE available = 1"; // العقارات المتاحة فقط
$result = $conn->query($sql);
?>

<!DOCTYPE html>
<html lang="ar">
<head>    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>عرض العقارات</title>
    <link rel="stylesheet" href="style.css"> <!-- رابط لملف الـ CSS -->
</head>
<body>

<header>
    <div class="container">
        <h1>إضافة عقار جديد</h1>
        <nav>
            <ul>
                <li><a href="index.php">الرئيسية</a></li>
                <li><a href="add_property.php">إضافة عقار</a></li>
                <li><a href="view_properties.php">عرض العقارات</a></li>
            </ul>
        </nav>
        <!-- خانة البحث -->
        <form action="view_properties.php" method="GET">
            <input type="text" name="search" placeholder="ابحث عن عقار..." required>
            <button type="submit">بحث</button>
        </form>
    </div>
</header>



<section class="property-grid">
<?php
if ($result->num_rows > 0) {
    // عرض العقارات
    while($row = $result->fetch_assoc()) {
        // التحقق من وجود صورة
        $image_url = $row["image_url"] ? $row["image_url"] : 'default_image.jpg';
        echo "<div class='property'>";
        echo "<img src='" . $image_url . "' alt='صورة العقار' class='property-image'>";
        echo "<h2>" . $row["title"] . "</h2>";
        echo "<p>" . $row["description"] . "</p>";
        echo "<p><strong>السعر: </strong>" . number_format($row["price"], 2) . " ج.م</p>";
        echo "<p><strong>الموقع: </strong>" . $row["location"] . "</p>";
        echo "<p><strong>النوع: </strong>" . $row["type"] . "</p>";
        echo "</div>";
    }
} else {
    echo "<p>لا توجد عقارات متاحة حالياً.</p>";
}
$conn->close(); // إغلاق الاتصال بعد الانتهاء
?>
</section>

<footer>
    <div class="container">
        <p>&copy; 2024 موقع بيع العقارات. جميع الحقوق محفوظة.</p>
        <ul>
            <li><a href="tel:0123456789">اتصل بنا: 0123456789</a></li>
            <li><a href="mailto:info@realestate.com">البريد الإلكتروني: info@realestate.com</a></li>
            <li><a href="https://www.facebook.com/yourpage" target="_blank">فيسبوك</a></li>
            <li><a href="https://www.instagram.com/yourpage" target="_blank">إنستغرام</a></li>
        </ul>
    </div>
</footer>


<script>
    window.onload = function() {
        const images = document.querySelectorAll('.property-image');
        images.forEach(image => {
            image.style.animation = 'fadeIn 2s ease-in-out';
        });
    }
</script>




</body>
</html>




