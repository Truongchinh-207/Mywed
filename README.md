# Mywed
# README.md - MyWeb

## Giới thiệu website cá nhân

Đây là website cá nhân dùng để giới thiệu thông tin bản thân, sở thích, kỹ năng và các dự án đã thực hiện.

## Chức năng website

- Hiển thị thông tin cá nhân
- Giới thiệu sở thích
- Liên hệ người dùng

## Các trang website

- trangchu.html
- thongtin.html
- sothich.html
- lienhe.html

## Công cụ sử dụng

- Acode
- HitHub
- Google Chrome
- <!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Website Thể Thao</title>

<style>

body{
margin:0;
font-family:Arial,sans-serif;
background:#f4f4f4;
}

header{
background:#0066cc;
color:white;
padding:20px;
text-align:center;
}

nav{
background:#004999;
padding:12px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
font-weight:bold;
}

nav a:hover{
color:yellow;
}

.banner{
background:#0099ff;
color:white;
padding:40px;
text-align:center;
font-size:30px;
font-weight:bold;
}

.container{
width:90%;
margin:auto;
}

.card{
background:white;
padding:20px;
margin-top:20px;
border-radius:10px;
box-shadow:0 0 10px gray;
}

.card img{
width:100%;
border-radius:10px;
}

button{
background:green;
color:white;
padding:10px 20px;
border:none;
border-radius:5px;
cursor:pointer;
}

button:hover{
background:darkgreen;
}

textarea{
width:100%;
height:100px;
}

footer{
margin-top:30px;
background:#222;
color:white;
padding:20px;
text-align:center;
}

</style>

</head>

<body>

<header>

<h1>THỂ THAO 24H</h1>

<p>Cập nhật tin thể thao nhanh nhất</p>

</header>

<nav>

<a href="#">Trang chủ</a>

<a href="#">Bóng đá</a>

<a href="#">Quần vợt</a>

<a href="#">Tin tức</a>

<a href="#">Đăng nhập</a>

</nav>

<div class="banner">

CHÀO MỪNG ĐẾN WEBSITE THỂ THAO

</div>

<div class="container">

<div class="card">

<h2>⚽ Bóng đá Việt Nam</h2>

<img src="https://images.unsplash.com/photo-1547347298-4074fc3086f0?w=800">

<p>

Đội tuyển Việt Nam tiếp tục chuẩn bị cho các giải đấu quốc tế với nhiều cầu thủ trẻ đầy triển vọng.

</p>

<button>Xem chi tiết</button>

</div>

<div class="card">

<h2>🌍 Bóng đá Quốc tế</h2>

<img src="https://images.unsplash.com/photo-1517466787929-bc90951d0974?w=800">

<p>

Champions League và Premier League đang diễn ra rất hấp dẫn.

</p>

<button>Xem chi tiết</button>

</div>

<div class="card">

<h2>🎾 Quần vợt</h2>

<img src="https://images.unsplash.com/photo-1554068865-24cecd4e34b8?w=800">

<p>

Wimbledon là giải Grand Slam được nhiều người yêu thích.

</p>

<button>Xem chi tiết</button>

</div>

<div class="card">

<h2>Ý kiến của bạn</h2>

<textarea id="ykien"></textarea>

<br><br>

<button onclick="gui()">Gửi bình luận</button>

</div>

</div>

<footer>

<h3>Site Map</h3>

Trang chủ |

Bóng đá |

Quần vợt |

Tin tức |

Đăng nhập

<p>

© 2026 Website Thể Thao

</p>

</footer>

<script>

function gui(){

alert("Cảm ơn bạn đã gửi ý kiến!");

}

</script>

</body>

</html>
