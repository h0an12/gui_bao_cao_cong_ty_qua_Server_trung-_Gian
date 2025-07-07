# gui_bao_cao_cong_ty_qua_Server_trung-_Gian
Đây là một hệ thống truyền file bảo mật mô phỏng tình huống gửi báo cáo từ công ty đến đối tác thông qua một server trung gian. Hệ thống đảm bảo:

🔐 Bảo mật nội dung bằng thuật toán AES-GCM
🔑 Trao đổi khóa AES bằng RSA 1024-bit (OAEP)
🧾 Xác thực người gửi bằng chữ ký số RSA/SHA-512
🧩 Kiểm tra toàn vẹn bằng SHA-512
🕒 Ghi log thời gian giao dịch tại server trung gian
🚫 Không có kết nối trực tiếp giữa người gửi và người nhận
