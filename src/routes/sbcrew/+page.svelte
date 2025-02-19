
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
    <img src='images/logoclb/crew.jpg'>
    Câu Lạc Bộ S&B Crew - THPT Nguyễn Trân
</div>

<div class="nav">
    <a href="#gioithieu">Giới Thiệu</a>
    <a href="#hoatdong">Hoạt Động</a>
    <a href="#hinhanh">Hình Ảnh</a>
    <a href="#tintuc">Tin Tức</a>
    <a href="#lienhe">Liên Hệ</a>
</div>

<div class="container">
    <div class="section" id="gioithieu">
        <h2>Giới Thiệu</h2>
        <p><span class="highlight">S&B Crew</span> là câu lạc bộ nhảy hiện đại của Trường THPT Nguyễn Trân, nơi hội tụ những bạn trẻ yêu thích vũ đạo, sáng tạo và bùng nổ trên sân khấu. CLB không chỉ là nơi luyện tập, mà còn là mái nhà chung của những tâm hồn đam mê nghệ thuật.</p>
    </div>

    <div class="section" id="hoatdong">
        <h2>Hoạt Động Chính</h2>
        <ul>
            <li>Biểu diễn tại các sự kiện lớn của trường và địa phương.</li>
            <li>Huấn luyện kỹ thuật nhảy hiện đại, hip-hop, popping, v.v.</li>
            <li>Tổ chức workshop giao lưu với các nhóm nhảy khác.</li>
            <li>Tham gia và tranh tài tại các cuộc thi vũ đạo.</li>
        </ul>
    </div>

    <div class="section" id="hinhanh">
        <h2>Hình Ảnh Hoạt Động</h2>
        <div class="gallery">
            <div class="image-item">
                <img src="images/sbcrew/1.jpg" alt="Biểu diễn sân khấu">
                <p class="caption"></p>
            </div>
            <div class="image-item">
                <img src="images/sbcrew/2.jpg" alt="Luyện tập nhóm">
                <p class="caption"></p>
            </div>
            <div class="image-item">
                <img src="images/sbcrew/3.jpg" alt="Cuộc thi vũ đạo">
                <p class="caption"></p>
            </div>
        </div>
    </div>

    <div class="section" id="tintuc">
        <h2>Tin Tức & Sự Kiện</h2>
        <p>Cập nhật những hoạt động mới nhất của CLB!</p>
        <ul>
            <li><strong>10/02/2025:</strong> Đêm hội vũ đạo "Dance Revolution 2025".</li>
            <li><strong>15/03/2025:</strong> Workshop "Kỹ Năng Vũ Đạo Cơ Bản" dành cho thành viên mới.</li>
            <li><strong>20/04/2025:</strong> Tham gia cuộc thi "Battle of the Crews".</li>
        </ul>
    </div>

    <div class="section" id="lienhe">
        <h2>Tham Gia Cùng Chúng Tôi</h2>
        <p>Bạn có đam mê nhảy múa và muốn tỏa sáng? Hãy tham gia ngay!</p>
        <p>Email: <a href="mailto:sbcrew@nguyentran.edu.vn" class="highlight">sbcrew@nguyentran.edu.vn</a></p>
        <p>Facebook: <a href="https://www.facebook.com/sbcrewnguyentran" class="highlight">@sbcrewnguyentran</a></p>
        <p>Hoặc đăng ký trực tiếp tại văn phòng Đoàn trường.</p>
    </div>
</div>

<div class="footer">
    © 2025 Câu Lạc Bộ S&B Crew - THPT Nguyễn Trân | Thiết kế bởi CLB S&B Crew
</div>


