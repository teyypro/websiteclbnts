
<style>
@keyframes appear {
from {
opacity: 0;
scale:0.5;

}
to {
opacity: 1;
scale: 1;
}
}
* {
animation: appear linear;
animation-timeline: view();
animation-range: entry 0%;
}
    /* Header */
    .header {
        background-color: #0D47A1;
color: white;
padding: 20px;
font-size: 2.5em;
font-weight: bold;
text-align: left;
display: flex
;
align-items: flex-end;
gap: 1rem;
    }
    /* Navigation Menu */
    .nav {
        background-color: #1976D2;
        overflow: hidden;
    }
    .nav a {
        float: left;
        display: block;
        color: #f4f4f4;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
    }
    .nav a:hover {
        background-color: #1565C0;
    }
    /* Main Content */
    .container {
        max-width: 1200px;
        margin: 20px auto;
        background: white;
        padding: 30px;
        border-radius: 5px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .section {
        margin-bottom: 40px;
    }
    .section h2 {
        color: #0D47A1;
        margin-bottom: 20px;
    }
    .section p, .section ul {
        line-height: 1.6;
        font-size: 16px;
        text-align: justify;
    }
    .highlight {
        color: #0D47A1;
        font-weight: bold;
    }
    /* Image Gallery */
    .gallery {
display: flex;
flex-wrap: wrap;
gap: 15px;
}

.image-item {
width: calc(33.333% - 10px);
text-align: center;
min-width: 200px;
}

.image-item img {
width: 100%;
border-radius: 5px;
min-width: 200px;
}

.caption {
margin-top: 8px;
font-size: 14px;
color: #555;
}
    /* Footer */
    .footer {
        background-color: #0D47A1;
        color: white;
        padding: 15px;
        font-size: 14px;
        text-align: center;
    }

    /* Responsive */
    @media screen and (max-width: 768px) {
        .gallery img {
            width: calc(50% - 10px);
        }
    }
    @media screen and (max-width: 480px) {
        .nav a {
            float: none;
            width: 100%;
        }
        .gallery img {
            width: 100%;
        }
    }
    .header img{
        border-radius: 100%;
height: 12rem;
    }
    
</style>

<div class="header">
    <img src='images/logoclb/femb.jpg' style="border-radius: 100%; height: 12rem;">
    Câu Lạc Bộ Hát FEMB - THPT Nguyễn Trân
</div>

<div class="nav">
    <a href="#gioithieu">Giới Thiệu</a>
    <a href="#hoatdong">Hoạt Động</a>
    <a href="#tintuc">Tin Tức</a>
    <a href="#lienhe">Liên Hệ</a>
</div>

<div class="container">
    <div class="section" id="gioithieu">
        <h2>Giới Thiệu</h2>
        <p><span class="highlight">CLB Hát FEMB</span> là nơi dành cho những bạn trẻ đam mê ca hát và âm nhạc. Chúng tôi không chỉ hát mà còn cùng nhau học hỏi, rèn luyện giọng hát và trình diễn trên sân khấu.</p>
    </div>

    <div class="section" id="hoatdong">
        <h2>Hoạt Động Chính</h2>
        <ul>
            <li>Tập luyện thanh nhạc và biểu diễn.</li>
            <li>Tham gia các cuộc thi ca hát.</li>
            <li>Giao lưu âm nhạc với các CLB khác.</li>
            <li>Trình diễn trong các sự kiện lớn của trường.</li>
        </ul>
    </div>

    <div class="section" id="hinhanh">
        <h2>Hình Ảnh Hoạt Động</h2>
        <div class="gallery">
            <div class="image-item">
                <img src="images/femb/1.jpg" alt="Biểu diễn sân khấu">
                <p class="caption"></p>
            </div>
            <div class="image-item">
                <img src="images/femb/2.jpg" alt="Luyện tập nhóm">
                <p class="caption"></p>
            </div>
            <div class="image-item">
                <img src="images/femb/3.jpg" alt="Cuộc thi vũ đạo">
                <p class="caption"></p>
            </div>
        </div>
    </div>
    <div class="section" id="tintuc">
        <h2>Tin Tức & Sự Kiện</h2>
        <p>Cập nhật những hoạt động mới nhất của CLB!</p>
        <ul>
            <li><strong>05/03/2025:</strong> Cuộc thi hát "Voice of Nguyễn Trân 2025".</li>
            <li><strong>20/04/2025:</strong> Buổi giao lưu âm nhạc với CLB Nhạc Trẻ TP Quy Nhơn.</li>
            <li><strong>15/05/2025:</strong> Chương trình biểu diễn gây quỹ từ thiện "Giai Điệu Yêu Thương".</li>
        </ul>
    </div>

    <div class="section" id="lienhe">
        <h2>Tham Gia Cùng Chúng Tôi</h2>
        <p>Bạn có đam mê ca hát và muốn thể hiện tài năng của mình? Hãy tham gia ngay!</p>
        <p>Email: <a href="mailto:femb@nguyentran.edu.vn" class="highlight">femb@nguyentran.edu.vn</a></p>
        <p>Facebook: <a href="https://www.facebook.com/fembnguyentran" class="highlight">@fembnguyentran</a></p>
        <p>Hoặc đăng ký trực tiếp tại văn phòng Đoàn trường.</p>
    </div>
</div>

<div class="footer">
    © 2025 CLB Hát FEMB - THPT Nguyễn Trân | Âm Nhạc - Đam Mê - Tỏa Sáng
</div>
