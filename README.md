
---

# ✨ Nam Trần - Interactive Bio Page

> Một trang Bio cá nhân không chỉ là danh sách liên kết, mà là một trải nghiệm thị giác sống động. Kết hợp giữa nghệ thuật thiết kế và kỹ thuật lập trình tối ưu.

## 🌐 Demo
👉 **Trải nghiệm ngay:** [Link Website](https://tranvohoangnam.id.vn/bio/)

---

## 💡 Giới thiệu

Dự án này là một trang "Link-in-Bio" thế hệ mới, được thiết kế để vượt qua giới hạn của các trang tĩnh thông thường. Nó sở hữu hệ thống **Dual-Theme (Sáng/Tối)** hoạt động như hai thế giới song song:
1.  **Chế độ Sáng (The Sky):** Một thảo nguyên yên bình với gió, mây, nắng và sự sống.
2.  **Chế độ Tối (The Space):** Vũ trụ bao la với sao băng, sấm chớp và những bí ẩn.

Mục tiêu của dự án là thể hiện cá tính **Creative • Designer • Technician** thông qua code sạch và hiệu ứng mượt mà.

---

## 🚀 Tính năng Nổi bật

### 🎨 Giao diện & Trải nghiệm (UI/UX)
*   **Phong cách Glassmorphism:** Các thành phần giao diện sử dụng hiệu ứng kính mờ cao cấp, lấy cảm hứng từ hệ sinh thái Apple.
*   **Chuyển đổi Theme Đẳng cấp:** Sử dụng hiệu ứng **"Frosted Glass Ripple"** (Vòng tròn kính mờ lan tỏa) để chuyển đổi giữa hai chế độ, loại bỏ hoàn toàn hiện tượng giật lag hay cắt cảnh thô.
*   **Tương tác Micro-interactions:** Hiệu ứng hover tinh tế trên từng liên kết, avatar và footer.

### ☀️ Chế độ Sáng (Dynamic Nature)
*   **Môi trường 3D giả lập:** Các lớp mây trôi với tốc độ và độ mờ khác nhau tạo chiều sâu.
*   **Hệ thống Gió thực tế:** Cây cối và thảm cỏ đung đưa theo thời gian thực. Khi có "cơn gió mạnh" (ngẫu nhiên), toàn bộ cảnh quan sẽ phản ứng đồng loạt.
*   **Chi tiết:** Lá rơi ngẫu nhiên, đàn chim bay qua, và ánh mặt trời rực rỡ với hiệu ứng lens flare.
*   **Parallax:** Cây và cỏ ở xa mờ hơn và chuyển động chậm hơn so với vật thể ở gần.

### 🌙 Chế độ Tối (Canvas Space)
*   **Starfield:** Hàng trăm ngôi sao được vẽ bằng HTML5 Canvas.
*   **Hiệu ứng ngẫu nhiên:** Sao băng vút qua, sấm chớp ở phía xa và UFO bay lượn.
*   **Hiệu suất cao:** Sử dụng Canvas API để render số lượng lớn phần tử mà không làm nặng DOM.

---

## 🛠 Công nghệ & Kỹ thuật

Dự án được xây dựng hoàn toàn bằng **Vanilla JavaScript (Không thư viện)** để đảm bảo tốc độ tải trang nhanh nhất và quyền kiểm soát tuyệt đối.

| Công nghệ | Mô tả |
| :--- | :--- |
| **HTML5** | Cấu trúc ngữ nghĩa (Semantic HTML), tối ưu SEO và Accessibility. |
| **CSS3** | Animations, Keyframes, Backdrop-filter, CSS Variables, Clip-path transition. |
| **JavaScript (ES6+)** | Module pattern, RequestAnimationFrame, Canvas API. |

### ⚡️ Tối ưu hóa Hiệu suất (Performance Optimization)
*   **DocumentFragment:** Sử dụng để khởi tạo hàng loạt các phần tử (cây, cỏ, sao) và thêm vào DOM trong một lần duy nhất, giảm thiểu Reflow/Repaint.
*   **RequestAnimationFrame:** Quản lý toàn bộ các chuyển động để đảm bảo đạt 60fps mượt mà.
*   **Object-Oriented Approach:** Code được tổ chức trong đối tượng `App` sạch sẽ, dễ bảo trì.
*   **Resource Management:** Tự động hủy (destroy) các interval và event listener của theme cũ trước khi chuyển sang theme mới để tránh rò rỉ bộ nhớ.

---

## 📂 Cài đặt & Chạy thử

Dự án này rất đơn giản để chạy cục bộ vì không cần build tools.

1.  **Clone repository:**
    ```bash
    git clone https://github.com/namtran592005/bio.git
    ```
2.  **Mở thư mục:**
    ```bash
    cd bio
    ```
3.  **Chạy:**
    Mở file `index.html` bằng trình duyệt bất kỳ hoặc sử dụng Live Server trên VS Code.

---

## 🤝 Đóng góp

Mọi ý kiến đóng góp hoặc Pull Request đều được hoan nghênh để làm cho hiệu ứng trở nên tuyệt vời hơn nữa!

---

## ❤️ Tác giả

**Nam Trần**
*   Creative • Designer • Technician
*   GitHub: [@Namtran592005](https://github.com/Namtran592005)
*   Facebook: [Nam Trần](https://fb.com/namtran5905)

---

*Made with ❤️ · Optimized for 🌍*
