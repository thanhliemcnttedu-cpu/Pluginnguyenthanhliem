# Bộ cài đặt trợ lý giáo viên

**Cách dễ nhất:** tải tệp **`Tai_Plugin.html`**, nhấp đúp để mở bằng trình duyệt, chọn đúng phần mềm đang dùng và bấm **một nút** để tải gói.

Mỗi thư mục là một gói riêng, chỉ có **một tệp .rar** (cần WinRAR hoặc 7-Zip để giải nén). Trong mỗi gói có tệp PDF hướng dẫn có ảnh minh họa từng bước.

| Thư mục | Dùng khi |
|---|---|
| `1-plugin-Claude-PC` | Máy có ứng dụng Claude |
| `2-Gemini-cach-A-phat-trien-ky-nang-tai-len-tep` | Gemini có thẻ "Kỹ năng" |
| `3-Gemini-cach-B-tao-Gem-moi-mo-tep-sao-chep` | Gemini: tạo Gem mới |
| `4-ChatGPT-plugin-tai-len-zip` | ChatGPT bản web |

## Trợ lý làm được gì
Soạn kế hoạch giáo dục, phân phối chương trình, giáo án, lịch báo giảng, kế hoạch tập huấn, biên bản, báo cáo; viết câu lệnh cho công cụ AI khác. Có thêm 5 chế độ: **bài giảng PowerPoint từ sách giáo khoa**, **ra đề kiểm tra** (ma trận, đặc tả, nhiều mã đề, đáp án), **video AI và trò chơi tương tác** (tệp HTML chạy ngoại tuyến), **sáng kiến kinh nghiệm** (khung, phản biện, mẫu biểu, 10 hướng đề tài), và từ 24/11/2026 **phóng viên giáo dục** (viết tin bài hoạt động nhà trường, tin ngắn, bài fanpage, thư mời; biên tập, rút gọn, kiểm duyệt trước khi đăng; không bịa dữ kiện, không phát ngôn thay lãnh đạo).

Trang tải có mục **Tài liệu đính kèm**: người quản trị thêm tệp Word, Excel bằng cách dán liên kết (Google Drive, GitHub) hoặc đính kèm trực tiếp; thầy cô chỉ cần bấm "Tải về".

## Tệp dữ liệu của trang tải
`Tai_Plugin.data.json` chứa danh sách các gói hiển thị trên trang `Tai_Plugin.html`. Trang tự lấy bản mới nhất của tệp này từ kho khi mở (cần Internet). Người quản trị có thể thêm, sửa, xóa mục ngay trên trang (nút ổ khóa) rồi lưu lên kho bằng token GitHub.

## Lưu ý
- Đây là plugin cá nhân của thầy Nguyễn Thanh Liêm, có thể chỉ phù hợp trong thời điểm hiện tại. Liên hệ: điện thoại và Zalo 0888 358 363.
- Giao diện Claude, Gemini, ChatGPT có thể đổi theo thời gian.
- Tài liệu tải lên các công cụ AI là gửi cho nhà cung cấp; bỏ tên và mã định danh học sinh trước khi tải.
- Đề kiểm tra, bài giảng và trò chơi do AI soạn chỉ là bản nháp: giáo viên cần đối chiếu sách giáo khoa và chơi thử trước khi dùng.
- Gói Claude chứa skill và agent của bên thứ ba; mỗi thành phần theo giấy phép của tác giả gốc.
