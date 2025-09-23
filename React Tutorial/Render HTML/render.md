# Render HTML

- Thực ra ngôn ngữ khi ta code là JSX, lúc này Vite sẽ compile JSX này ra JavaScript sau đó React tạo ra Virtual DOM và so sánh với DOM thật của trình duyệt. Cuối cùng trình duyệt sẽ render thành HTML 

- JSX là cú pháp mở rộng của JavaScript, cho phép ta viết HTML trực tiếp trong file JavaScript

- Một website luôn cần HTML để hiển thị, để sử dụng React cho website thì mình cần chèn React vào 1 container HTML. Thông thường, container này là <div id="root"></div> trong index.html file.

- Khi ta gắn React vào 1 div thì React sẽ chỉ kiểm soát cây DOM bên trong div ta chỉ định, những div khác hoạt động bình thường

- Hàm createRoot() tạp một React root để quản lý container HTML

- Hàm render() định nghĩa cái gì sẽ được hiển thị bên trong container HTML. nó nhận JSX hoặc components của React để render thành HTML

- Khi ta gọi: createRoot(document.getElementById("root")).render(<App />);
thì createRoot(...) sẽ chọn container div#root và render(<App />) sẽ xác định nội dung sẽ được hiển thị bên trong container đó


