# Hệ thống Quản lý Nhân sự (HRMS) - Trường Đại học Thủy lợi

Dự án này tập trung vào việc **Phân tích và Thiết kế Hệ thống Quản lý Nhân sự (HRMS)** dành riêng cho **Trường Đại học Thủy lợi (TLU)**. Hệ thống được thiết kế để quản lý toàn diện vòng đời nhân sự của hơn 1,200 cán bộ, giảng viên và nhân viên tại cả 3 cơ sở (Hà Nội, Hưng Yên, TP.HCM).

---

## 📌 Tổng quan dự án

- **Tên dự án:** TLU-HRMS
- **Mục tiêu:** Xây dựng giải pháp quản trị nhân sự hiện đại, tự động hóa các quy trình nghiệp vụ đặc thù của môi trường đại học công lập tại Việt Nam.
- **Đối tượng quản lý:** Giảng viên cơ hữu, giảng viên thỉnh giảng, cán bộ quản lý, nhân viên hành chính và nghiên cứu sinh.

## 🚀 Các Module Chức năng Chính

Hệ thống bao gồm 14 module nghiệp vụ cốt lõi:

1.  **Quản lý Hồ sơ (FR-ER):** Lưu trữ thông tin cá nhân, gia đình, quá trình công tác.
2.  **Trình độ & Chức danh (FR-QM):** Quản lý bằng cấp, học hàm (GS, PGS), học vị (TS, ThS) và ngạch viên chức.
3.  **Cơ cấu Tổ chức (FR-OS):** Mô hình hóa cấu trúc Trường - Khoa/Viện - Bộ môn - Phòng thí nghiệm.
4.  **Hợp đồng Lao động (FR-CM):** Quản lý hợp đồng làm việc xác định thời hạn và không xác định thời hạn.
5.  **Chấm công & Nghỉ phép (FR-TA):** Theo dõi lịch làm việc và quản lý đơn nghỉ phép online.
6.  **Tiền lương & Phúc lợi (FR-PB):** Tính lương theo ngạch bậc, phụ cấp thâm niên, thuê TNCN và BHXH.
7.  **Tuyển dụng (FR-RC):** Quy trình từ đăng tin, nhận hồ sơ ứng viên đến khi tiếp nhận thử việc.
8.  **Đánh giá & Khen thưởng (FR-PR):** Đánh giá viên chức hàng năm và quản lý lịch sử kỷ luật/khen thưởng.
9.  **Đào tạo & Phát triển (FR-TD):** Quản lý kế hoạch cử đi học và cam kết đào tạo.
10. **Nghiên cứu Khoa học (FR-RM):** Theo dõi danh mục các đề tài và công bố khoa học của CBGV.
11. **Giờ giảng (FR-TL):** Quản lý định mức và tính giờ giảng dạy vượt định mức.
12. **Báo cáo & Thống kê (FR-RP):** Hệ thống báo cáo tổng hợp phục vụ lãnh đạo và các Bộ ngành.
13. **Cổng thông tin Nhân viên (FR-SS):** Self-service portal cho phép CBGV xem lương và cập nhật thông tin.
14. **Cấu hình Hệ thống (FR-CF):** Quản lý linh hoạt các tham số nghiệp vụ (mức lương cơ sở, tỷ lệ bảo hiểm, v.v.).

## 📂 Cấu trúc dự án

- [wireframes/](file:///d:/Hoc/PTDAPM/tlu-hr/wireframes/): Chứa các bản thiết kế giao diện chi tiết cho từng module.
- [user_requirements_hrms.md](file:///d:/Hoc/PTDAPM/tlu-hr/user_requirements_hrms.md): Tài liệu đặc tả yêu cầu người dùng (URD) chi tiết gần 1400 dòng.
- [hrms_database.dbml](file:///d:/Hoc/PTDAPM/tlu-hr/hrms_database.dbml): Thiết kế lược đồ cơ sở dữ liệu.
- [.gitignore](file:///d:/Hoc/PTDAPM/tlu-hr/.gitignore): Quy tắc loại bỏ các tệp không cần thiết khi push Git.

## ⚖️ Cơ sở pháp lý

Hệ thống được thiết kế tuân thủ các văn bản pháp luật hiện hành:
- Luật Viên chức 2019.
- Bộ Luật Lao động 2019.
- Luật Giáo dục & Luật Giáo dục Đại học.
- Các quy chế chi tiêu nội bộ đặc thù của TLU.

---
*Dự án đang trong giai đoạn Phân tích & Thiết kế.*
