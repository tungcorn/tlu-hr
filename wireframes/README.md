# Tài liệu Thiết kế Wireframe Giao diện Người dùng

# Hệ thống Quản lý Nhân sự (HRMS) - Trường Đại học Thủy lợi

> **Phiên bản:** 1.0  
> **Ngày tạo:** 24/01/2026  
> **Dự án:** Phân tích và Thiết kế Phần mềm  
> **Đơn vị:** Trường Đại học Thủy lợi (TLU)

---

## Cấu trúc thư mục

| File | Mô tả |
|------|-------|
| [00-design-system.md](./00-design-system.md) | Hệ thống thiết kế: màu sắc, typography, components |
| [01-layout.md](./01-layout.md) | Layout chung và cấu trúc navigation |
| [02-authentication.md](./02-authentication.md) | Đăng nhập, khôi phục mật khẩu, đổi mật khẩu |
| [03-dashboard.md](./03-dashboard.md) | Dashboard cho các vai trò người dùng |
| [04-employee-records.md](./04-employee-records.md) | Quản lý Hồ sơ Nhân sự |
| [05-qualifications.md](./05-qualifications.md) | Quản lý Trình độ và Chức danh |
| [06-organization.md](./06-organization.md) | Quản lý Cơ cấu Tổ chức |
| [07-contracts.md](./07-contracts.md) | Quản lý Hợp đồng Lao động |
| [08-attendance.md](./08-attendance.md) | Chấm công và Quản lý Nghỉ phép |
| [09-payroll.md](./09-payroll.md) | Quản lý Tiền lương và Phúc lợi |
| [10-recruitment.md](./10-recruitment.md) | Module Tuyển dụng |
| [11-performance.md](./11-performance.md) | Đánh giá và Khen thưởng - Kỷ luật |
| [12-training.md](./12-training.md) | Đào tạo và Phát triển |
| [13-research.md](./13-research.md) | Quản lý Nghiên cứu Khoa học |
| [14-teaching-load.md](./14-teaching-load.md) | Quản lý Giờ giảng |
| [15-reports.md](./15-reports.md) | Báo cáo và Thống kê |
| [16-self-service.md](./16-self-service.md) | Cổng Nhân viên (Self-Service Portal) |
| [17-system-config.md](./17-system-config.md) | Quản lý Cấu hình Hệ thống |

---

## Nguyên tắc thiết kế

| Nguyên tắc | Mô tả |
|------------|-------|
| **Nhất quán** | Sử dụng cùng màu sắc, font chữ, kích thước nút bấm xuyên suốt hệ thống |
| **Đơn giản** | Giao diện rõ ràng, dễ hiểu, tập trung vào tác vụ chính |
| **Responsive** | Tương thích với desktop, tablet và mobile |
| **Accessibility** | Hỗ trợ người dùng với các nhu cầu đặc biệt |
| **Tiếng Việt** | Toàn bộ giao diện bằng tiếng Việt |

---

## Vai trò người dùng

| Vai trò | Quyền hạn chính | Module truy cập |
|---------|-----------------|-----------------|
| **Quản trị viên hệ thống** | Toàn quyền quản trị, phân quyền | Tất cả |
| **Cán bộ Phòng TCCB** | Quản lý hồ sơ, hợp đồng, chính sách nhân sự | 04-14, 17 |
| **Cán bộ Phòng TCKT** | Quản lý lương, thưởng, các khoản thu chi | 09, 15 |
| **Lãnh đạo trường** | Phê duyệt, báo cáo tổng hợp | Dashboard, 15 |
| **Trưởng đơn vị** | Quản lý nhân sự đơn vị, đánh giá | 04, 08, 11, 15 (theo đơn vị) |
| **Cán bộ/Giảng viên** | Xem/cập nhật thông tin cá nhân | 16 (Self-Service) |

---

## Ký hiệu trong Wireframe

```
┌───────────┐  Khung/Container
│           │
└───────────┘

[Button]       Nút bấm
[Input Field]  Ô nhập liệu
[Dropdown ▼]   Dropdown/Select
☐              Checkbox
○              Radio button
🔍             Tìm kiếm
📥             Download/Export
✏️             Chỉnh sửa
🗑️             Xóa
👁️             Xem chi tiết
```

---

## Tham chiếu

- [Tài liệu Yêu cầu Người dùng](../user_requirements_hrms.md)
