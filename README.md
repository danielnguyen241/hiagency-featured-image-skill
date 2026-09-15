# HiAgency Featured Image Skill

Team dán nội dung bài viết để agent tự chọn headline, thiết kế và xuất một featured image HiAgency **1200 × 700 WebP**.

## Dùng bằng copy–paste

1. Mở [SKILL.md](hiagency-featured-image/SKILL.md), bấm **Raw**, copy toàn bộ.
2. Paste vào công cụ AI/agent có quyền dùng Canva hoặc Photoshop và khả năng xuất file.
3. Dán tiếp prompt này cùng nội dung bài:

```text
Áp dụng skill ở trên để tạo 1 featured image HiAgency cho bài dưới đây.
Tự chọn bố cục và headline theo skill, tạo ảnh hoàn chỉnh và trả file WebP.

Focus keyphrase: [điền nếu có, không có thì bỏ dòng này]

NỘI DUNG BÀI:
[dán toàn bộ bài viết]
```

Không cần tự điền màu, font hay bố cục. Nếu không có keyphrase, agent tự rút headline từ bài và ghi rõ đó là lựa chọn suy ra.

## Dùng như skill đã cài

Copy thư mục `hiagency-featured-image` vào thư mục skills mà agent của team hỗ trợ, rồi gọi:

```text
Dùng $hiagency-featured-image tạo featured image cho bài sau:
[dán nội dung]
```

## Điều kiện và kết quả

- Cần Canva hoặc Photoshop đã kết nối/đăng nhập, quyền tạo thiết kế và export; chỉ paste skill không tự cấp công cụ hay tài khoản.
- Kết quả: ảnh WebP, export gốc, tham chiếu thiết kế chỉnh sửa được nếu có, và `image-handoff.json` chứa metadata cùng kết quả QA.
- Không logo/tagline/dải trắng đầu ảnh/watermark; không tự thêm subtitle.
- AI imagery chỉ dùng khi được yêu cầu rõ; giữ đúng nguồn gốc và đánh dấu review theo quy trình HiAgency.
- Nếu thiếu công cụ, agent trả brief và ghi rõ chưa tạo xong ảnh.
- Skill không upload WordPress. Bước blog-draft kiểm tra provenance và metadata riêng trước khi đăng tải.

Repo không chứa nội dung bài khách hàng, tài khoản, credentials hay assets chưa rõ quyền sử dụng.
