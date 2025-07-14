# law-data-showcase
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="utf-8">
  <title></title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: none;
      position: relative;
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: white;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .menu {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }
    .menu button {
      font-size: 1.2em;
      padding: 20px;
      background-color: #222;
      color: #fff;
      border: 2px solid #4CAF50;
      border-radius: 12px;
      cursor: pointer;
      transition: transform 0.2s, background-color 0.3s;
    }
    .menu button:hover {
      background-color: #4CAF50;
      transform: scale(1.1);
    }
    .content {
      display: none;
      max-width: 800px;
      margin-top: 30px;
      padding: 20px;
      background-color: #222;
      border-radius: 10px;
    }
    .content.active {
      display: block;
    }
    .animated-title h1, .animated-title h2 {
      animation: fadeInUp 1s ease-out;
      animation-fill-mode: both;
    }
    .animated-title h1 {
      animation-delay: 0s;
    }
    .animated-title h2 {
      animation-delay: 0.3s;
    }
    .glow {
      animation: glowAnim 2s infinite alternate;
    }
    @keyframes glowAnim {
      0% {
        text-shadow: 0 0 5px #FFD700, 0 0 10px #FFD700;
      }
      100% {
        text-shadow: 0 0 10px #FFD700, 0 0 20px #FFD700;
      }
    }
    @keyframes marquee {
      0% { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
  </style>
<style>
    #video-background {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }
</style>
<body>
 
  <video id="video-background" autoplay loop muted>
    <source src="videonen1.mp4" type="video/mp4">
  </video>
  <div class="animated-title" style="background-color: rgba(0,0,0,0.6); padding: 30px 20px; margin: 30px auto; border-radius: 15px; text-align: center; max-width: 1000px; box-shadow: 0 0 10px rgba(0,0,0,0.5);">
<img src="logobca.png" alt="Logo Bộ Công an" style="height: 190px; position: absolute; top: 30px; left: 130px;">
    <h1 class="glow" style="margin: 0 0 10px; font-size: 2em; color: #FFD700; line-height: 1.3;">PHẦN MỀM TRÌNH CHIẾU TƯƠNG TÁC</h1>
    <h1 class="glow" style="margin: 0 0 10px; font-size: 2em; color: #FFD700; line-height: 1.3;">BÀI DỰ THI</h1>
    <h2 style="margin: 0; font-size: 1.6em; color: #FFE066; font-weight: bold;">"TÌM HIỂU LUẬT DỮ LIỆU TRONG CÔNG AN NHÂN DÂN"</h2>
  </div>

  <div style="margin-bottom: 20px; width: 100%; overflow: hidden; background: rgba(0,0,0,0.6); padding: 10px 0;">
    <div style="display: inline-block; white-space: nowrap; animation: marquee 20s linear infinite; font-size: 1.1em; color: #FFD700;">
      📢 Luật dữ liệu trong thời kỳ chuyển đổi số quốc gia - Bước đột phá trong Kỷ nguyên mới - Kỷ nguyên vươn mình của Dân tộc 📢
    </div>
  </div>
 <video id="video-background" autoplay loop muted>
    <source src="nen.mp4" type="video/mp4">
  </video>
  <div style="background-color: rgba(0,0,0,0.6); padding: 20px; margin: 20px auto 10px auto; border-radius: 10px; text-align: center; max-width: 1000px;">
    <p><span style="color: #FFD700;">Nhóm Tác giả:</span> <strong style="color: #FFD700;">CHIẾN BINH VIỄN THÔNG</strong></p>
    <p><span style="color: #FFD700;">Thành viên:</span> <strong style="color: #FFD700;">Thiếu tá Mai Hồ Trung Trinh - Thiếu úy Huỳnh Văn Tài</strong></p>
    <p><span style="color: #FFD700;">Đơn vị:</span> <strong style="color: #FFD700;">Phòng Thông tin liên lạc miền Nam - Cục H04 - Bộ Công an</strong></p>
  </div>
  <div class="menu">
    <button onclick="showContent('gioithieu')">🏠 Giới thiệu</button>
    <button onclick="showContent('capthiet')">📌 Cấp thiết</button>
    <button onclick="showContent('luat')">📚 Luật</button>
    <button onclick="showContent('video')">🎥 Tình huống</button>
    <button onclick="showContent('baove')">🛡️ Bảo vệ</button>
    <button onclick="showContent('quiz')">🧠 Quiz</button>
    <button onclick="showContent('tailieu')">📎 Tài liệu</button>
    <button onclick="showContent('thankyou')">🎯 Kết thúc</button>
  </div>

  

  <div id="capthiet" class="content">
    <h2>Tính cấp thiết</h2>
    <ul>
      <li>Dữ liệu KH&CN là mục tiêu tấn công và đánh cắp.</li>
      <li>Rò rỉ dữ liệu có thể ảnh hưởng nghiêm trọng đến an ninh và công nghệ.</li>
      <li>Cần nắm vững luật bảo vệ dữ liệu và sở hữu trí tuệ.</li>
    </ul>
  </div>

  <div id="luat" class="content">
    <h2>Các văn bản luật liên quan</h2>
    <ul>
      <li>Nghị định 13/2023/NĐ-CP</li>
      <li>Luật An toàn thông tin mạng</li>
      <li>Luật Sở hữu trí tuệ (sửa đổi)</li>
      <li>Quy định bảo mật trong nghiên cứu quốc phòng</li>
    </ul>
  </div>

  <div id="video" class="content" style="max-height: 500px; overflow-y: auto;">
    <h2>Video minh họa vi phạm dữ liệu KH&CN</h2>
    <p>1. Viện nghiên cứu bị tấn công mạng, rò rỉ dữ liệu AI quốc phòng.</p>
    <video controls style="width: 480px; height: 270px; border: 2px solid #444; border-radius: 8px;">
      <source src="onmt.mp4" type="video/mp4">
    </video>
    <p>2. Video về triển khai luật dữ liệu trong Công an nhân dân.</p>
    <video controls style="width: 480px; height: 270px; border: 2px solid #444; border-radius: 8px;">
      <source src="nen1.mp4" type="video/mp4">
    </video>
  </div>

  <div id="baove" class="content">
    <h2>Hướng dẫn bảo vệ dữ liệu KH&CN</h2>
    <ul>
      <li>Mã hóa dữ liệu</li>
      <li>Phân quyền truy cập</li>
      <li>Sao lưu định kỳ</li>
      <li>Không chia sẻ công khai</li>
      <li>Xác thực đa yếu tố</li>
    </ul>
  </div>

  <div id="quiz" class="content">
    <h2>Trắc nghiệm luật dữ liệu</h2>
    <p>1. Luật nào bảo vệ dữ liệu cá nhân tại VN?</p>
    <p>☐ Luật Giao thông</p>
    <p>☑ Nghị định 13/2023/NĐ-CP</p>
    <p>2. Chia sẻ dữ liệu nghiên cứu trái phép vi phạm gì?</p>
    <p>☑ Luật Sở hữu trí tuệ</p>
    <p>☐ Luật Xây dựng</p>
  </div>

  <div id="tailieu" class="content">
    <p><a href="files/LawTech_Showcase_Final.pptx" target="_blank" style="color: #4CAF50; text-decoration: underline;">📥 Tải bài trình chiếu PowerPoint tại đây</a></p>
    <img src="img/qrcode_tai_lieu.png" style="width: 150px;">
  </div>

  <div id="thankyou" class="content">
    <h2>Cảm ơn!</h2>
    <p>Nhóm Chiến Binh Viễn Thông<br>Phòng Thông tin Liên lạc Miền Nam</p>
    <p><em>Đồng hành cùng cuộc thi Tìm hiểu Luật Dữ liệu</em></p>
  </div>

  <script>
    function showContent(id) {
      document.querySelectorAll('.content').forEach(el => el.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
  </script>
</body>
</html>
