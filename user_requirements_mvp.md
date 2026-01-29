# Tài liệu Yêu cầu Người dùng (MVP)
## Hệ thống Quản lý Nhân sự - Trường Đại học Thủy lợi

> **Phiên bản:** MVP - Phase 1  
> **Thời gian triển khai:** 2 tháng  
> **Nhóm thực hiện:** 14 người (5 Teams)

---

## 1. Các nhân tố tham gia (Stakeholders)

### 1.1. Người dùng hệ thống

| Vai trò | Đơn vị | Mô tả |
|---------|--------|-------|
| Quản trị hệ thống | Phòng CNTT | Quản trị, phân quyền |
| Cán bộ TCCB | Phòng TCCB | Quản lý hồ sơ nhân sự |
| Cán bộ TCKT | Phòng TCKT | Quản lý lương, phụ cấp |
| Lãnh đạo | Ban Giám hiệu | Phê duyệt, báo cáo |
| Trưởng đơn vị | Khoa/Phòng | Quản lý nhân sự đơn vị |
| CBGV/NV | Toàn trường | Tra cứu, cập nhật thông tin |

### 1.2. Các bên liên quan khác

- Bộ Nông nghiệp và Môi trường
- Bộ Giáo dục và Đào tạo
- Cơ quan Bảo hiểm xã hội
- Cơ quan Thuế

---

## 2. Các yêu cầu của Stakeholders (Needs) và Tính năng (Features)

### 2.1. Quản lý Hồ sơ Nhân sự

**Needs:**
- Ban giám hiệu muốn quản lý toàn diện thông tin của tất cả cán bộ, giảng viên, nhân viên trong trường.
- Phòng nhân sự muốn tạo lập hồ sơ cá nhân.
- Phòng nhân sự muốn hồ sơ cá nhân lưu trữ thông tin cá nhân: họ tên, ngày sinh, giới tính, CCCD/CMT, nơi sinh, quê quán, dân tộc, tôn giáo.
- Phòng nhân sự muốn lưu trữ thông tin liên hệ: địa chỉ thường trú, địa chỉ tạm trú, số điện thoại, email cá nhân, email công việc.
- Phòng nhân sự muốn lưu trữ thông tin gia đình: tình trạng hôn nhân, thông tin vợ/chồng, con cái, người phụ thuộc (để tính giảm trừ thuế TNCN).
- Phòng nhân sự muốn lưu trữ ảnh chân dung cán bộ (3x4, 4x6).
- Phòng nhân sự muốn lưu trữ thông tin ngân hàng: tên ngân hàng, số tài khoản, chi nhánh.
- Phòng nhân sự muốn lưu trữ quá trình công tác trước khi vào trường.
- Phòng nhân sự muốn lưu trữ thông tin Đảng viên: ngày vào Đảng, ngày chính thức, đảng bộ trực thuộc.
- Phòng nhân sự muốn lưu trữ thông tin đoàn viên công đoàn.
- Phòng nhân sự muốn mã cán bộ có thể được tạo tự động.
- Khách hàng muốn cho phép tìm kiếm, lọc hồ sơ theo nhiều tiêu chí.
- Khách hàng muốn xuất hồ sơ ra file (PDF, Excel, Word) theo mẫu.
- Phòng nhân sự muốn thông tin được hỗ trợ hiển thị dạng học hàm, học vị.

**Features:**

| Mã | Tính năng | Mô tả |
|----|-----------|-------|
| FEAT-ER-01 | Tạo hồ sơ nhân sự | Form nhập liệu thông tin cá nhân, liên hệ, gia đình |
| FEAT-ER-02 | Upload ảnh chân dung | Upload và lưu trữ ảnh 3x4, 4x6 |
| FEAT-ER-03 | Quản lý thông tin ngân hàng | Nhập/sửa thông tin tài khoản ngân hàng |
| FEAT-ER-04 | Quản lý quá trình công tác | Nhập lịch sử công tác trước khi vào trường |
| FEAT-ER-05 | Quản lý thông tin Đảng viên | Nhập thông tin Đảng: ngày vào, ngày chính thức, đảng bộ |
| FEAT-ER-06 | Quản lý thông tin Công đoàn | Nhập thông tin đoàn viên công đoàn |
| FEAT-ER-07 | Sinh mã cán bộ tự động | Tự động tạo mã theo quy tắc định sẵn |
| FEAT-ER-08 | Tìm kiếm, lọc hồ sơ | Tìm kiếm theo tên, mã, đơn vị, trình độ... |
| FEAT-ER-09 | Xuất hồ sơ | Xuất ra PDF, Excel, Word theo mẫu |
| FEAT-ER-10 | Hiển thị học hàm/học vị | Format hiển thị: PGS.TS. Nguyễn Văn A |

---

### 2.2. Quản lý Trình độ Học vấn, Chức danh

**Needs:**
- Phòng nhân sự muốn lưu trữ chi tiết bằng cấp: tên bằng, chuyên ngành, trường cấp, năm tốt nghiệp, xếp loại.
- Phòng nhân sự muốn lưu các chức danh khoa học.
- Phòng nhân sự muốn lưu thông tin về chức danh, ngạch viên chức.
- Phòng nhân sự muốn lưu thông tin về chức vụ có lưu quá trình bổ nhiệm, miễn nhiệm chức vụ.
- Phòng nhân sự muốn lưu các chứng chỉ và có thể biết ngày hết hạn.

**Features:**

| Mã | Tính năng | Mô tả |
|----|-----------|-------|
| FEAT-QM-01 | Quản lý bằng cấp | Nhập/sửa thông tin bằng cấp, chuyên ngành, xếp loại |
| FEAT-QM-02 | Quản lý chức danh khoa học | Lưu GS, PGS, TS, ThS... |
| FEAT-QM-03 | Quản lý ngạch viên chức | Lưu ngạch: Giảng viên, GV chính, GV cao cấp... |
| FEAT-QM-04 | Quản lý chức vụ | Lưu quá trình bổ nhiệm, miễn nhiệm |
| FEAT-QM-05 | Quản lý chứng chỉ | Lưu chứng chỉ + ngày hết hạn, cảnh báo sắp hết hạn |

---

### 2.3. Quản lý Cơ cấu Tổ chức

**Needs:**
- Ban giám hiệu muốn thông tin cơ cấu tổ chức là hệ thống phân cấp theo quan hệ cha con, được xây dựng theo hướng hội đồng trường, hội đồng đảng ủy, các phòng ban quản lý, các khoa (dưới các khoa là các bộ môn).
- Ban giám hiệu muốn có thể phân bổ nhân sự, chuyển công tác vào các khoa, các phòng, các bộ môn qua phần mềm.
- Ban giám hiệu muốn một người có thể kiêm nhiệm nhiều chức vụ ở nhiều đơn vị.
- Phòng nhân sự muốn các đơn vị có thể được lưu lịch sử thành lập, sáp nhập, giải thể đơn vị, có thể đánh dấu trạng thái tồn tại hay đã giải thể.

**Features:**

| Mã | Tính năng | Mô tả |
|----|-----------|-------|
| FEAT-OS-01 | Quản lý đơn vị phân cấp | Cây tổ chức: Trường → Khoa → Bộ môn |
| FEAT-OS-02 | Phân bổ nhân sự | Gán nhân viên vào đơn vị |
| FEAT-OS-03 | Quản lý kiêm nhiệm | Một người nhiều chức vụ ở nhiều đơn vị |
| FEAT-OS-04 | Lịch sử đơn vị | Lưu thành lập, sáp nhập, giải thể |
| FEAT-OS-05 | Sơ đồ tổ chức | Hiển thị sơ đồ cây trực quan |

---

### 2.4. Quản lý Hợp đồng Lao động

**Needs:**
- Phòng nhân sự muốn phần mềm cho phép tạo lập 4 loại hợp đồng lao động: không xác định thời hạn, xác định thời hạn, thử việc, thỉnh giảng.
- Phòng nhân sự muốn hợp đồng lao động có thể lưu trữ các thông tin: số HĐ, ngày ký, ngày hiệu lực, ngày hết hạn, nội dung công việc, phụ lục.
- Phòng nhân sự muốn hợp đồng thỉnh giảng cho phép gia hạn và có cảnh báo hết hạn.
- Phòng nhân sự muốn hợp đồng thử việc có thời gian dựa trên bậc hay ngạch tương ứng.
- Phòng nhân sự muốn hợp đồng có thể in theo chuẩn mẫu.
- Phòng nhân sự muốn hợp đồng có thể chuyển đổi theo quy tắc (từ thử việc → chính thức, từ có thời hạn → vô thời hạn).
- Phòng nhân sự muốn cho phép lập hồ sơ từ các nhân sự đã được ký hợp đồng.

**Features:**

| Mã | Tính năng | Mô tả |
|----|-----------|-------|
| FEAT-CM-01 | Tạo hợp đồng | Form tạo HĐ với 4 loại |
| FEAT-CM-02 | Lưu thông tin HĐ | Số HĐ, ngày ký, hiệu lực, hết hạn, phụ lục |
| FEAT-CM-03 | Gia hạn HĐ thỉnh giảng | Chức năng gia hạn + cảnh báo |
| FEAT-CM-04 | Cảnh báo hết hạn | Thông báo HĐ sắp hết hạn |
| FEAT-CM-05 | In hợp đồng | Xuất HĐ theo mẫu chuẩn |
| FEAT-CM-06 | Chuyển đổi HĐ | Thử việc → Chính thức |
| FEAT-CM-07 | Tạo hồ sơ từ HĐ | Tự động tạo hồ sơ nhân sự khi ký HĐ |

---

### 2.5. Quản lý Bậc lương (Cơ bản - Chỉ lưu trữ)

**Needs:**
- Phòng nhân sự muốn mỗi nhân sự sở hữu một hệ số lương và mức lương cơ sở, lương lấy theo ngạch bậc công chức, viên chức.
- Phòng nhân sự muốn mỗi nhân sự cũng được lưu các loại phụ cấp.
- Phòng nhân sự muốn có một bảng hệ số lương theo ngạch/bậc (Giảng viên, GV chính, GV cao cấp, Chuyên viên...) để tiện thay đổi bậc và ngạch.
- Phòng nhân sự muốn lưu số bậc và hệ số tương ứng cho mỗi ngạch (VD: Giảng viên có 9 bậc, hệ số 2.34 - 4.98).
- Phòng nhân sự muốn lưu hệ số phụ cấp chức vụ theo từng vị trí.
- Phòng nhân sự muốn yêu cầu có các loại phụ cấp mặc định sau: chức vụ, thâm niên, ưu đãi ngành, trách nhiệm, độc hại, khu vực.

**Features:**

| Mã | Tính năng | Mô tả |
|----|-----------|-------|
| FEAT-PB-01 | Quản lý bảng ngạch/bậc | Danh mục ngạch, bậc và hệ số lương |
| FEAT-PB-02 | Gán ngạch/bậc cho nhân sự | Lưu hệ số lương của từng người |
| FEAT-PB-03 | Quản lý danh mục phụ cấp | 6 loại: chức vụ, thâm niên, ưu đãi, trách nhiệm, độc hại, khu vực |
| FEAT-PB-04 | Gán phụ cấp cho nhân sự | Lưu các khoản phụ cấp của từng người |

> **Lưu ý MVP:** Phase 1 chỉ lưu trữ thông tin lương, KHÔNG tính lương tự động và KHÔNG thông báo tăng bậc tự động.

---

### 2.6. Báo cáo Thống kê (Cơ bản)

**Needs:**
- Lãnh đạo muốn thống kê nhân sự theo toàn trường, theo đơn vị dạng bảng.
- Lãnh đạo muốn có thể xuất thống kê ra PDF, Excel.

**Features:**

| Mã | Tính năng | Mô tả |
|----|-----------|-------|
| FEAT-RP-01 | Thống kê nhân sự | Báo cáo số lượng theo đơn vị, toàn trường |
| FEAT-RP-02 | Xuất báo cáo | Xuất ra PDF, Excel |

> **Lưu ý MVP:** Phase 1 không bao gồm thống kê biến động nhân sự phức tạp.

---

### 2.7. Self-Service Portal (Cơ bản)

**Needs:**
- CBGV/NV muốn xem thông tin cá nhân.
- CBGV/NV muốn xem lịch sử hợp đồng.
- CBGV/NV muốn xem thông tin chức vụ, chức danh, học vấn, thông tin bậc lương.

**Features:**

| Mã | Tính năng | Mô tả |
|----|-----------|-------|
| FEAT-SS-01 | Xem hồ sơ cá nhân | Trang xem thông tin của chính mình |
| FEAT-SS-02 | Xem lịch sử hợp đồng | Danh sách các HĐ đã ký |
| FEAT-SS-03 | Xem thông tin lương | Xem ngạch/bậc, phụ cấp hiện tại |

> **Lưu ý MVP:** Phase 1 không bao gồm chức năng yêu cầu cập nhật thông tin online.

---

## 3. Yêu cầu Chung

- Với mỗi nhân sự có thể xem thông tin cá nhân.
- Trước khi lưu một mục phải có kiểm tra tính hợp lệ của dữ liệu.
- Mỗi danh mục hỗ trợ: thêm/sửa, đánh dấu active/inactive, sắp xếp thứ tự hiển thị.
- Hỗ trợ danh mục phân cấp cho một số loại (VD: Quốc gia → Tỉnh/Thành phố).
- Không cho phép xóa mục danh mục đang được sử dụng, chỉ cho phép đánh dấu inactive.

---

## 4. Yêu cầu Phi chức năng

**Hiệu năng:**
- Trang thông thường < 2 giây, báo cáo phức tạp < 10 giây.

**Bảo mật:**
- Mã hóa dữ liệu nhạy cảm (lương, CCCD); HTTPS cho web.
- Ghi lại tất cả thao tác quan trọng.

**Khả năng sử dụng:**
- Giao diện tiếng Việt, thân thiện, responsive.
- Có tài liệu hướng dẫn sử dụng đầy đủ.
- Người dùng mới sử dụng được các chức năng cơ bản sau 4 giờ đào tạo.

**Tích hợp:**
- Hỗ trợ xuất file theo chuẩn.
- Hỗ trợ quản lý đa cơ sở: Hà Nội, Phố Hiến, TP.HCM.

**Tuân thủ pháp luật:**
- Tuân thủ Bộ Luật Lao động 2019.
- Tuân thủ Luật Viên chức và các văn bản hướng dẫn.

---

## 5. Tổng hợp Features (Phase 1)

| Module | Số FEAT | Mã FEAT |
|--------|---------|---------|
| Hồ sơ nhân sự | 10 | FEAT-ER-01 → FEAT-ER-10 |
| Trình độ, Chức danh | 5 | FEAT-QM-01 → FEAT-QM-05 |
| Cơ cấu tổ chức | 5 | FEAT-OS-01 → FEAT-OS-05 |
| Hợp đồng lao động | 7 | FEAT-CM-01 → FEAT-CM-07 |
| Bậc lương | 4 | FEAT-PB-01 → FEAT-PB-04 |
| Báo cáo thống kê | 2 | FEAT-RP-01 → FEAT-RP-02 |
| Self-Service | 3 | FEAT-SS-01 → FEAT-SS-03 |
| **Tổng cộng** | **36 FEAT** | |

---

## 6. Phạm vi KHÔNG nằm trong Phase 1

Các module sau sẽ được phát triển trong Phase 2:

- **Quản lý Tuyển dụng:** Lập hồ sơ ứng tuyển, lịch phỏng vấn → Hoãn.
- **Quản lý Đào tạo:** Khóa đào tạo, cam kết, chi phí → Hoãn.
- **Chấm công:** Cần tích hợp máy chấm công → Hoãn.
- **Nghiên cứu khoa học:** Quy tắc quy đổi phức tạp → Hoãn.
- **Giờ giảng:** Nhiều quy tắc đặc thù → Hoãn.
- **Đánh giá viên chức:** Ưu tiên thấp hơn → Hoãn.
- **Tính lương tự động:** Chỉ lưu trữ trong Phase 1 → Hoãn.
- **Thông báo tăng bậc lương tự động:** → Hoãn.

---

> *Tài liệu này là phiên bản rút gọn MVP với 36 Features. Các yêu cầu bị hoãn sẽ được triển khai trong Phase 2.*
