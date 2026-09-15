# HiAgency Featured Image Skill

**Dán skill + nội dung bài vào AI có khả năng tạo ảnh → nhận thumbnail featured image HiAgency trực tiếp.**

Không cần Canva, Photoshop, tài khoản thiết kế hay kết nối ứng dụng khác.

## Cách dùng cho team

1. Mở [SKILL.md](hiagency-featured-image/SKILL.md), chọn **Raw** và copy toàn bộ nội dung.
2. Paste vào cuộc hội thoại AI có công cụ tạo ảnh.
3. Dán nội dung bài bên dưới, ví dụ:

```text
Áp dụng skill ở trên, tạo ngay một featured image HiAgency cho bài này.

NỘI DUNG BÀI:
[dán nội dung bài viết]
```

Có focus keyphrase hoặc headline muốn dùng thì thêm vào; không có thì AI tự chọn từ bài. Không cần tự viết prompt tạo ảnh hay chọn màu, font và bố cục.

## Nếu đã cài skill vào agent

Copy thư mục `hiagency-featured-image` vào thư mục skills của agent đang dùng, rồi gọi:

```text
Dùng $hiagency-featured-image tạo ảnh cho bài sau:
[dán nội dung bài viết]
```

## Ảnh được tạo theo chuẩn nào?

- Một ảnh ngang, tràn khung; đích xuất **1200 × 700 px, WebP**.
- Headline chỉ định → focus keyphrase → headline tự rút từ bài.
- Minh hoạ đúng chủ đề, chữ rõ, bố cục thoáng và chừa lề an toàn.
- Không logo HiAgency, tagline, dải trắng đầu ảnh, watermark hay subtitle tự thêm.
- Tạo ảnh AI trực tiếp, kiểm tra và sửa lỗi chữ/bố cục khi công cụ hỗ trợ.
- Trả ảnh trong chat, file tải nếu có, kèm alt text và media title khi công cụ cho phép.

**Khả năng xuất file phụ thuộc môi trường AI:** nếu chỉ xuất được PNG/JPEG hoặc kích thước khác, skill vẫn giao ảnh và nói rõ phần chưa đạt. Chỉ công bố WebP 1200 × 700 khi file thực tế đã được kiểm tra. Nếu không có công cụ tạo ảnh, skill trả prompt dự phòng và ghi rõ chưa tạo ảnh.

Skill giữ đúng nguồn gốc AI và không tự upload WordPress. Quy trình đăng bài, nếu được yêu cầu sau đó, áp dụng riêng.
