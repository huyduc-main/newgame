## BÀI TẬP LỚN : TESTRIS GAME PROJECT
  Họ và tên sinh viên : Trần Huy Đức
  
  Mã số sinh viên : 23021401
 # Gioi thiệu về game 
  Đây là game Tetris cổ điển được phát triển bằng C++ với thư viện SDL2. Game bao gồm các tính năng cơ bản của Tetris như xoay/di chuyển khối gạch, tính điểm, tăng tốc độ theo level, cùng nhiều chế độ chơi và tùy chỉnh đặc biệt.
 
 🏆 Ngưỡng điểm tự đánh giá
     9.5/10

📊 Lý do đề xuất điểm số

  ✅ Tính năng chính đã hoàn thiện
 1.Core Gameplay

    Hệ thống 7 Tetromino chuẩn với physics chính xác

    Cơ chế Hard Drop (Space) và Soft Drop (Mũi tên xuống)

    Xử lý va chạm, xoay khối (Wall Kick)

    Tự động lock piece sau khi move

 2.Hệ thống nâng cao

    Hold System: Giữ khối (phím C/L)

    Next Queue: Hiển thị 3 khối tiếp theo

    Ghost Piece: Bóng mờ dự đoán vị trí đặt

    Scoring System: Tính điểm theo tiêu chuẩn Tetris Guideline

 3.Đa chế độ

    Chế độ Solo Classic

    Chế độ 2 người chơi local (PvP)

    Menu lựa chọn độ khó (5 levels từ Easy đến Asian)

 🎮 Điều khiển
 Chức năng 	   Player 1	    Player 2
 
 Di chuyển trái	   ←	           A
 
 Di chuyển phải	   →    	       D
 
 Xoay khối      	↑	             W

 Soft Drop      	↓	             S

 Hard Drop 	    Space	         Space

 Hold	           C	            L

 4.Giao diện đồ họa

    Sử dụng SDL2 để render đồ họa

    Hệ thống button, text, animation

    Hiệu ứng âm thanh cho các hành động

 5.Thuật toán đã cài đặt

    Thuật toán xử lý va chạm khối gạch

    Thuật toán kiểm tra/xóa dòng hoàn chỉnh

    Thuật toán sinh khối gạch ngẫu nhiên

    Thuật toán tính tốc độ rơi theo level

 6.Các tính năng phụ trợ

    Pause/Continue game

    Countdown khi bắt đầu/bắt đầu lại

    Lưu cài đặt game

    Xử lý sự kiện bàn phím linh hoạt
 
 ⚠️ Cần cải thiện
    Chưa implement multiplayer online

    Thiếu hệ thống replay/save game

    Hiệu ứng hình ảnh có thể phong phú hơn
 
 🙏 Lời cảm ơn
               Em xin chân thành cảm ơn thầy/cô đã tạo điều kiện để em thể hiện khả năng qua project này. Rất mong nhận được sự đánh giá công tâm từ thầy/cô!   
