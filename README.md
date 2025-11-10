# Nhom5_DAT111_DuAn1_BookingTourDuLich
Nhóm 5: Dự án 1- Phân tích booking Tour Du Lịch
-  Hiện trạng 
Sau đại dịch COVID-19 (2020–2021), ngành du lịch Việt Nam chịu ảnh hưởng nặng nề, hầu hết doanh nghiệp lữ hành phải tạm dừng hoạt động.
Đến năm 2022, khi mở cửa trở lại, công ty XXXX bắt đầu phục hồi bằng các tour nội địa ngắn ngày, giá hợp lý, tập trung vào khách hàng trong nước.
Từ 2022 đến 2024, lượng khách và doanh thu tăng mạnh trở lại, đặc biệt tại các điểm đến như Sapa, Nha Trang, Cần Thơ.
Tuy nhiên, lợi nhuận vẫn tăng chậm, chưa tương xứng với doanh thu do chi phí vận hành và hiệu quả từng vùng chưa đồng đều.
-	Thông tin dữ liệu
Quy mô: 10,002 booking, 29 cột (khách, tour, kênh đặt, giá, chi phí, lợi nhuận, ngày đi/về, vùng, mùa…).
Trường giá chính: unit_price_vnd (đơn giá/khách), tổng hợp doanh thu/chi phí/lợi nhuận: revenue_vnd, total_cost_vnd, profit_vnd.
Thời gian: travel_start từ 2022-01-01 đến 2024-12-31.
Địa điểm: location (thành phố/điểm đến), region (miền).
Loại tour: tour_type (Beach, Cultural, Mountain, River, Adventure, City, Cruise, Food).
Khách: customer_origin (Domestic/Foreign).
Số ngày tour được suy ra từ travel_end - travel_start (mình đã tính trường duration_days, median = 2).
