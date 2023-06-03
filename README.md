# <h1 align="center">IS403.N21.HTTT_Nhom5<h1>

  
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="">
  </a>

  <h3 align="center">Paper Intermediate Statistical Analyst</h3>

  <p align="center">
    <a href="https://github.com/QuocTrungNQT/IS403.N21.HTTT_Nhom5"><strong>Khám phá »</strong></a>
  </p>
</div>

  
  
  <!-- TABLE OF CONTENTS -->
<details>
  <summary>Mục lục</summary>
  <ol>
    <li>
      <a href="#abtract">Abtract</a>
    </li>
    <li>
      <a href="#introduce">Giới thiệu</a>
    </li>
    <li><a href="#memeberslist">Danh sách thành viên</a></li>
    <li>
      <a href="#material">Nguồn</a>
    </li>
    <li><a href="#model">Thuật toán</a></li>
  </ol>
</details>
  
  
  <!-- ABOUT THE PROJECT -->
## <h2 id="abstract">Abstract</h2>
## <h2 id="introduce">Giới thiệu</h2>
  <p>Chứng khoán là một trong những lĩnh vực không còn quá xa lạ đối với các nhà đầu tư và doanh nghiệp lớn. Cổ phiếu là một loại chứng khoán và là một phương tiện tài chính phổ biến và quan trọng trong thị trường tài chính. Những biến động của cổ phiếu là trong những điều khó để dự đoán chính xác, gây khó khăn cho các doanh nghiệp trong việc định giá cổ phiếu.</p>
  <p>Mục đích của việc định giá cổ phiếu giúp doanh nghiệp phân tích được tìm năng của cổ phiếu từ đó đưa ra những quyết định phù hợp. Do vậy việc dự đoán chính xác giá cổ phiếu là một trong những yếu tố rất quan trọng giúp đưa ra các quyết định trong tương lai. Trong nghiên cứu này, chúng tôi sử dụng các mô hình ARIMA, Linear Regression, LSTM, RNN, GRU, Holt-Winters, Kalman Filter (KF), Dynamic Factor Model (DFM), Time Series Anomaly Detection, Random Forest (RF) để dự báo giá mở cửa của cổ phiếu.</p>
  <p>Việc lựa chọn đề tài về cổ phiếu để phân tích và đưa ra dự đoán tương lai vì cổ phiếu cung cấp các thông tin kinh doanh phản ánh được hiệu quả của doanh nghiệp, các thông tin về hoạt động kinh doanh cũng như kế hoạch tương lai. Cổ phiếu có tính biến động cao giúp việc sử dụng các thông tin này để dự đoán về hành vi giá cả cũng như xu hướng trong tương lai. Dữ liệu cổ phiếu thường có sẵn và dễ dàng truy cập, điều này tạo điều kiện thuận lợi cho các nhà phân tích thu thập và sử dụng trong phân tích, dự đoán.</p>
<h2 id="memberslist">Các thành viên tham gia paper</h2>
 
| STT| Họ tên            | MSSV     | FB                                                                           |   SĐT     |            Nhiệm vụ            |
|:--:|-------------------|----------|------------------------------------------------------------------------------|-----------|--------------------------------|
| 1  | Chu Quyết Thắng   | 20521892 |[Quyết Thắng](https://www.facebook.com/chuquyetthang2952)                     |0353241981 | CEDN, GRU                      |
| 2  | Nguyễn Quốc Trung | 20522073 |[Nguyễn Quốc Trung](https://www.facebook.com/QuocTrung.0101)                  |0378269526 | Dynamic Factor, RNN            | 
| 3  | Đỗ Mạnh Tuấn      | 20522108 |[Mạnh Tuấn](https://www.facebook.com/23072002td)                              |0355978908 | Kalman Filter, LSTM            |
| 4  | Nguyễn Đức Thuần  | 20521993 |[Nguyễn Thuần](https://www.facebook.com/profile.php?id=100091965523539)       |0886339784 | Random Forest, Arima           |
| 5  | Lê Hoàng Duyên    | 20521252 |[Duyên Hoàng Lê](https://www.facebook.com/profile.php?id=100012111349079)     |0395309824 | Holt-Winter, Linear Regression |
## <h2 id="material">Material</h2>
- Dữ liệu:<br/>
  + Dữ liệu về giá chứng khoán theo từng ngày của 3 công ty Amazon, Apple, Netflix từ 7/2017 đến 6/2023. <br/>
  + Nguồn dữ liệu: trên Yahoo ! Finance. <br/>
  + Trong nghiên cứu này, chúng tôi sẽ dự đoán giá đóng cửa của 30 ngày sau đó cụ thể là từ ngày 1/7/2023 đến 30/1/2023. <br/>
- Tool: <br/>
  Sử dụng Visual Studio Code, Google Colab, Anaconda, Python. <br/>
- Độ chia dữ liệu: <br/>
  Chúng tôi đã đề xuất ra 3 cách chia dữ liệu là: (7:2:1), (6:3:1), (5:3:2) <br/>
- Độ đo dự liệuL <br/>
  Sử dụng độ đo về RMSE và MAPE <br/>
## <h2 id="model">Thuật toán</h2>
