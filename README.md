# [F1 Race Predictor]
*Hệ thống Dự đoán Kết quả Đua xe Công thức 1*

---

* **Bài tập lớn môn**: Lập trình với Python (INT13162) - Học viện Công nghệ Bưu chính Viễn thông (PTIT)

* **Giảng viên hướng dẫn**: Cô Phan Thị Hà

* **Nhóm thực hiện**: Nhóm 4

Đua xe Công thức 1 (*Formula 1 - F1*) là một trong những môn thể thao tốc độ hấp dẫn và có tính chiến thuật phức tạp nhất thế giới, nơi kết quả phụ thuộc vào hàng loạt yếu tố như phong độ tay đua, hiệu suất xe, vị trí xuất phát, lịch sử đường đua và điều kiện thời tiết.

Để giúp những người hâm mộ dễ dàng phân tích và dự đoán cục diện chặng đua, chúng em đã xây dựng ứng dụng web **F1 Race Predictor** có tích hợp trí tuệ nhân tạo / học máy (Machine Learning).

Ứng dụng cung cấp các giải pháp dự đoán thứ hạng chặng đua, xác suất bước lên bục nhận giải (Podium), thống kê dữ liệu lịch sử các mùa giải và trực quan hóa thông số của từng tay đua cũng như đội đua.


## Authors (Nhóm 4 - PTIT)

- **Nguyễn Quốc Khánh** - `B24DCCN311` - https://github.com/NgQKhanh2906
- **Nguyễn Tiến Thịnh** - `B24DCCN546` - [@github_username](https://www.github.com/)
- **Phạm Văn Vĩ** - `B24DCCN608` - [@github_username](https://www.github.com/)
- **Phạm Hoàng Hiệp** - `B24DCCN201` - [@github_username](https://www.github.com/)
- **Nguyễn Đình Lộc** - `B24DCCN355` - [@github_username](https://www.github.com/)
- **Trần Phi Anh** - `B24DCCN047` - [@github_username](https://www.github.com/)
- **Nguyễn Văn Hậu** - `B24DCCN197` - [@github_username](https://www.github.com/)
- **Phạm Hải Giang** - `B24DCCN179` - [@github_username](https://www.github.com/)
- **Đoàn Xuân Đại** - `B24DCCN089` - [@github_username](https://www.github.com/)
- **Lại Đức Toàn** - `B24DCCN557` - [@github_username](https://www.github.com/)


## Demo

[Link Video Demo dự án tại đây](https://www.youtube.com/)


## Screenshots

Giao diện Trang chủ & Bảng điều khiển dự đoán
![App Screenshot](https://via.placeholder.com/800x450?text=Giao+Dien+Trang+Chu+F1+Predictor)

Giao diện Kết quả dự đoán từ mô hình Machine Learning
![Prediction Screenshot](https://via.placeholder.com/800x450?text=Ket+Qua+Du+Doan+Chặng+Đua)


## Features

- **Dự đoán kết quả chặng đua (ML Prediction):** Ứng dụng mô hình học máy để dự đoán người chiến thắng, Top 3 (Podium) và thứ hạng chung cuộc dựa trên kết quả phân hạng (Qualifying), lịch sử đường đua và phong độ hiện tại.
- **Thống kê & Trực quan hóa dữ liệu:** Hiển thị biểu đồ so sánh thành tích giữa các tay đua (Drivers) và đội đua (Constructors) qua từng mùa giải.
- **Tra cứu thông tin mùa giải:** Cung cấp lịch thi đấu, thông tin chi tiết về các trường đua (Circuits) và bảng xếp hạng điểm số cập nhật.
- **Giao diện Web trực quan:** Dễ dàng tùy chỉnh các tham số đầu vào (thời tiết, vị trí xuất phát, đội đua) để xem mô hình thay đổi kết quả dự đoán theo thời gian thực.


## Requirements

- Python 3.9 trở lên
- Pip (Python package installer)
- Các thư viện xử lý dữ liệu & Machine Learning: `scikit-learn`, `pandas`, `numpy`, `matplotlib` / `seaborn`
- Framework Web: `Flask` / `Streamlit` / `Django` *(tùy chỉnh lại theo đúng thư viện nhóm bạn dùng)*


## Installation

Cách cài đặt và chạy dự án trên máy cá nhân:

```bash
  # 1. Clone dự án về máy
  git clone https://github.com/ten-tai-khoan/ten-repo-cua-nhom.git
  cd ten-repo-cua-nhom

  # 2. Tạo và kích hoạt môi trường ảo (Khuyến nghị)
  python -m venv venv
  # Trên Windows:
  venv\Scripts\activate
  # Trên macOS/Linux:
  source venv/bin/activate

  # 3. Cài đặt các thư viện cần thiết
  pip install -r requirements.txt

  # 4. Chạy ứng dụng web
  python app.py
  # (Hoặc nếu dùng Streamlit: streamlit run app.py)
```
    

## License

[MIT](https://choosealicense.com/licenses/mit/)