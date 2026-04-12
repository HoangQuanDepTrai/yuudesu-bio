# 🎬 DatVeXemPhim - Hệ Thống Đặt Vé Xem Phim Trực Tuyến

[![Status](https://img.shields.io/badge/Status-In--Development-yellow)]()
[![Framework](https://img.shields.io/badge/Framework-React/NextJS-blue)]()
[![Backend](https://img.shields.io/badge/Backend-NodeJS/NestJS-green)]()

**DatVeXemPhim** là một nền tảng web hiện đại cho phép người dùng xem lịch chiếu, chọn phim, chọn ghế ngồi và thanh toán vé xem phim trực tuyến một cách nhanh chóng và tiện lợi.

---

## 📸 Giao diện ứng dụng (Screenshots)

| Trang chủ & Lịch chiếu | Chọn Ghế (Real-time) |
| :---: | :---: |
| <img src="https://via.placeholder.com/400x250?text=Home+Page" width="400"> | <img src="https://via.placeholder.com/400x250?text=Seat+Selection" width="400"> |

---

## ✨ Tính năng nổi bật

### 👤 Đối với Người dùng (Customer)
- **Duyệt phim:** Xem danh sách phim đang chiếu và sắp chiếu với trailer HD.
- **Lọc phim:** Tìm kiếm phim theo thể loại, rạp hoặc ngày chiếu.
- **Đặt ghế Real-time:** Chọn ghế ngồi và xem trạng thái ghế (đã đặt/đang chọn) theo thời gian thực (sử dụng Socket.io).
- **Thanh toán:** Tích hợp cổng thanh toán (VNPAY/Momo/Stripe).
- **Lịch sử đặt vé:** Xem lại các vé đã mua và mã QR để check-in tại rạp.

### 🔐 Đối với Quản trị viên (Admin)
- **Quản lý Phim:** Thêm/Sửa/Xóa phim, quản lý trailer và thời lượng.
- **Quản lý Lịch chiếu:** Sắp xếp suất chiếu theo phòng và rạp.
- **Thống kê doanh thu:** Biểu đồ doanh thu theo ngày/tháng/năm.

---

## 🛠️ Công nghệ sử dụng (Tech Stack)

| Thành phần | Công nghệ |
| :--- | :--- |
| **Frontend** | ReactJS / Next.js, Tailwind CSS, Redux Toolkit |
| **Backend** | Node.js (Express/NestJS) |
| **Database** | MongoDB / PostgreSQL |
| **Real-time** | Socket.io (cho việc chọn ghế) |
| **Thanh toán** | VNPAY API / Momo API |

---

## ⚙️ Hướng dẫn cài đặt

### 1. Yêu cầu hệ thống
- Node.js (v18.x trở lên)
- MongoDB hoặc PostgreSQL

### 2. Cài đặt các bước
```bash
# Clone repository
git clone [https://github.com/user/datVeXemPhim.git](https://github.com/user/datVeXemPhim.git)

# Cài đặt Backend
cd backend
npm install
npm run dev

# Cài đặt Frontend
cd ../frontend
npm install
npm run start
