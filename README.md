# 🚀 Tổng Hợp Kiến Thức Cốt Lõi Về Backend & Hệ Thống

Chào mừng bạn đến với kho lưu trữ các khái niệm nền tảng về phát triển ứng dụng Web Backend và Cơ sở dữ liệu. Tài liệu này được thiết kế để tra cứu nhanh các thuật ngữ công nghệ quan trọng.

---

## 🌐 1. Giao Tiếp Mạng & API (Networking)

### 📌 HTTP
> **HTTP** = *HyperText Transfer Protocol* (Giao thức truyền tải siêu văn bản)
* **Định nghĩa:** Là giao thức tiêu chuẩn được sử dụng phổ biến để **trao đổi dữ liệu** qua lại giữa **Trình duyệt (Client)** và **Máy chủ Web (Server)**.

### 🔌 API
> **API** = *Application Programming Interface* (Giao diện lập trình ứng dụng)
* **Định nghĩa:** Đóng vai trò là một **cổng giao tiếp trung gian**, cho phép các phần mềm, hệ thống hoặc ứng dụng khác nhau có thể **trao đổi dữ liệu** với nhau một cách an toàn và có cấu trúc.

### 📐 RESTful API
> **REST** = *Representational State Transfer*
* **REST:** Là **bộ quy tắc, quy chuẩn thiết kế chung** được các lập trình viên trên thế giới thống nhất sử dụng khi xây dựng API.
* **RESTful API:** Là những API được viết tuân thủ nghiêm ngặt theo các quy tắc của REST.

### 📦 JSON
> **JSON** = *JavaScript Object Notation*
* **Định nghĩa:** Là **một định dạng dữ liệu** văn bản gọn nhẹ, tuân theo một quy luật nhất định (Dạng `Key: Value`), chuyên dùng để lưu trữ và truyền tải dữ liệu giữa các hệ thống khác nhau.

---

## 🛠️ 2. Lập Trình Backend & Framework

### ⚡ FastAPI
* **Định nghĩa:** Là một **Web Framework** hiện đại của Python dùng để **build API** với hiệu năng cực cao, dễ code, đơn giản và hỗ trợ tối ưu cho việc triển khai sản phẩm thực tế.
* **Động cơ bên dưới:** Được xây dựng dựa trên **ASGI** (như *Uvicorn*) — đóng vai trò là "thông dịch viên" bất đồng bộ siêu tốc giữa Web Server và mã nguồn Python.

### 🔄 Thao tác CRUD
**CRUD** là tập hợp 4 thao tác cơ bản và nền tảng nhất khi làm việc với bất kỳ hệ thống dữ liệu nào:

| Ký tự | Thao tác gốc | Ý nghĩa tiếng Việt |
| :---: | :--- | :--- |
| **C** | **Create** | Tạo mới dữ liệu |
| **R** | **Read** | Đọc / Tra cứu dữ liệu |
| **U** | **Update** | Cập nhật / Sửa dữ liệu |
| **D** | **Delete** | Xóa bỏ dữ liệu |

---

## 💾 3. Cơ Sở Dữ Liệu (Database)

### 🗄️ Database (Tổng quan)
Là nơi lưu trữ dữ liệu tập trung của hệ thống, được chia làm 2 trường phái phổ biến:

* **Relational Database (CSDL Quan hệ):** Hệ thống lưu trữ dữ liệu chặt chẽ dưới dạng các **Bảng** (gồm hàng và cột), liên kết chặt chẽ với nhau thông qua các từ khóa chìa khóa (thường gọi là **ID**).
* **NoSQL Database (CSDL phi quan hệ):** Loại cơ sở dữ liệu không dùng cấu trúc bảng mà được sinh ra để chứa các kiểu dữ liệu tự do, không có hình dạng cố định và biến đổi liên tục.

### 🗣️ SQL
> **SQL** = *Structured Query Language* (Ngôn ngữ truy vấn có cấu trúc)
* **Định nghĩa:** Là **ngôn ngữ tiêu chuẩn** dùng để giao tiếp, truy vấn và tương tác với các Hệ thống quản trị cơ sở dữ liệu quan hệ (RDBMS).

### 🐘 PostgreSQL
* **Định nghĩa:** Là một hệ thống quản trị **cơ sở dữ liệu quan hệ và đối tượng (RDBMS)** mã nguồn mở miễn phí. Hiện nay, PostgreSQL được đánh giá là hệ thống cơ sở dữ liệu tiên tiến, mạnh mẽ và đáng tin cậy nhất thế giới.
