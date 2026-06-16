<div align="center">
  
  <img src="banner.png" alt="Ngăn Nắp Hậu Kỳ Banner" width="100%" style="border-radius: 8px; margin-bottom: 20px;"/>

  # NGĂN NẮP HẬU KỲ
  
  **Giải pháp tự động hóa cấu trúc dữ liệu, giúp tối ưu hóa hiệu suất và chuẩn hóa quy trình làm việc dành riêng cho Nhà làm phim chuyên nghiệp.**
  
  *Thiết kế và phát triển bởi **TESU***

  [![Phiên bản](https://img.shields.io/badge/Version-v1.0.0-00A3FF?style=for-the-badge)](https://github.com/TesuDevDTP/NganNapHauKy/releases)
  [![Hệ điều hành](https://img.shields.io/badge/Platform-Windows_10_|_11-11192E?style=for-the-badge&logo=windows)](https://github.com/TesuDevDTP/NganNapHauKy)
  [![Đối tượng](https://img.shields.io/badge/Target-Video_Editors_|_Filmmakers-060B14?style=for-the-badge)](https://github.com/TesuDevDTP/NganNapHauKy)

</div>

---

## 💡 Tầm Nhìn Dự Án: "10 giây đổi lại sự cứu rỗi cho não bộ"

Một dự án hậu kỳ hỗn loạn với hàng trăm file Footage, Audio, Graphic nằm rải rác chính là "cơn ác mộng" chí mạng làm giảm 50% tốc độ dựng hình và dễ gây ra lỗi **Media Offline** khi bàn giao. Quy trình tạo thư mục thủ công lặp đi lặp lại mỗi ngày vừa tốn thời gian, vừa thiếu tính nhất quán giữa các dự án.

**Ngăn Nắp Hậu Kỳ** ra đời để định hình lại cuộc chơi. Chỉ với **10 giây** trước khi bấm nút `New Project` trên Adobe Premiere Pro hay DaVinci Resolve, ứng dụng sẽ tự động tạo một cấu trúc hệ thống thư mục tiêu chuẩn, giúp bạn quản lý tài nguyên logic tuyệt đối, tối ưu hóa tốc độ tìm kiếm và giải phóng không gian sáng tạo.

---

## ✨ Các Tính Năng Đột Phá Khai Thác Sức Mạnh Quy Trình

### 🧠 Thuật Toán Tách Từ Thông Minh (Smart Word Segmentation)
* Người dùng có thể gõ tiếng Việt có dấu thoải mái (VD: `Sự Kiện Âm Nhạc`).
* Hệ thống sẽ kích hoạt bộ từ điển chuyên ngành tích hợp sẵn để tự động loại bỏ dấu, chuẩn hóa chữ in hoa và bóc tách các cụm từ thương hiệu, địa danh một cách hoàn hảo: `260616_SU_KIEN_AM_NHAC`.

### 🎥 Khai Báo Camera Linh Hoạt (Dynamic Multi-Cam Matrix)
* Hỗ trợ tích chọn nhanh các góc máy tiêu chuẩn: `CAN`, `TOAN`, `GIMBAL`, `FLYCAM`, `FPV`.
* Cho phép gõ thêm các dòng máy phụ trợ tùy ý (cách nhau bởi dấu phẩy). Hệ thống tự sắp xếp thứ tự ưu tiên tăng dần một cách khoa học.

### 🔄 Đồng Bộ Hóa Cấu Trúc Proxy Tự Động
* Ứng dụng tự động khởi tạo nhánh thư mục `PROXY` riêng biệt, chính xác theo số lượng và tên các camera đã khai báo. Editor chỉ cần chép file proxy vào đúng vị trí mà không sợ nhầm lẫn mã máy.

---

## 📂 Sơ Đồ Cấu Trúc Thư Mục Được Khởi Tạo

Mỗi dự án sau khi xử lý qua phần mềm sẽ có cấu trúc thư mục chuẩn hóa như sau:

```text
📁 [YYMMDD_TEN_SU_KIEN_CHUAN_HOA]
├── 📁 1. PROJECT (Chứa file gốc Premiere, After Effects, DaVinci, Avid...)
│   └── 📁 [FINAL] (Nơi xuất file nghiệm thu các phiên bản)
├── 📁 2. CAM 1 [TÊN_MÁY_1] (Footage gốc máy 1)
├── 📁 2. CAM 2 [TÊN_MÁY_2] (Footage gốc máy 2)
├── 📁 2. CAM ...
├── 📁 2. CAM [X] PROXY (Hệ thống lưu trữ Proxy đồng bộ ngầm)
│   ├── 📁 2. CAM 1 [TÊN_MÁY_1]
│   └── 📁 2. CAM 2 [TÊN_MÁY_2]
├── 📁 3. ASSET (File dạng video)
├── 📁 4. MUSIC (Nhạc nền được sử dụng trong dự án)
├── 📁 5. GRAPHIC (File PSD, AI, Motion Graphic template)
├── 📁 6. SOUNDFX (Hiệu ứng âm thanh, tiếng động môi trường)
├── 📁 7. TRANSITIONS (Các gói chuyển cảnh, overlay bổ trợ)
└── 📄 README.md (File báo cáo tự động ghi nhận thông số ngày quay)
```
---

## 🤝 Đóng Góp (Contributing)
Mọi ý kiến đóng góp nhằm tối ưu hóa bộ từ điển bóc tách từ ngữ hoặc đề xuất cấu trúc thư mục mới cho các ngách hậu kỳ luôn được hoan nghênh. Bạn có thể mở một thẻ mới tại mục Issues hoặc gửi Pull Request để cùng phát triển công cụ.

---

## 📞 Liên Hệ (Contact)
* Nhà phát triển: TESU
* GitHub: @TesuDevDTP
* Email: dothanhphat.tesu@gmail.com

---

## 📄 Bản Quyền (License)
Dự án này được cấp phép theo các điều khoản của MIT License. Bạn được toàn quyền sử dụng, sửa đổi, sao chép và phân phối lại phần mềm này cho các mục đích cá nhân hoặc thương mại, miễn là đính kèm tệp bản quyền gốc của nhà phát triển.
