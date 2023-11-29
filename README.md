# Research-Web-Security-and-Application

Web Application Firewall using Character-level Convolutional Neural Network


1.	Tóm tắt đề tài 	-	Trong bối cảnh ngày càng phát triển của ứng dụng web và kỷ nguyên số hoá, việc bảo mật các hệ thống web trở nên cực kỳ quan trọng. Đồ án đề xuất xây dựng một hệ thống tường lửa ứng dụng web (Web Application Firewall - WAF) dựa trên mô hình Mạng nơ-ron tích chập cấp ký tự (Character-Level Convolutional Neural Network - CharCNN).
Mục tiêu nghiên cứu	-	Nghiên cứu, tổng hợp kiến thức và hiểu rõ hơn về hệ thống tường lửa ứng dụng web (WAF) và nguyên lý hoạt động của Mạng nơ-ron tích chập cấp ký tự (CharCNN).
-	Đề xuất một mô hình WAF dựa trên CharCNN để cải thiện khả năng phát hiện và ngăn chặn các cuộc tấn công và đảm bảo an toàn cho các ứng dụng web.
-	Đánh giá hiệu quả của mô hình đề xuất thông qua các tiêu chí đánh giá và so sánh với các phương pháp WAF hiện nay.
Phạm vi nghiên cứu	-	Tập trung vào nghiên cứu các công trình liên quan đến hệ thống tường lửa ứng dụng web (WAF) và Mạng nơ-ron tích chập cấp ký tự (CharCNN).
-	Xây dựng một mô hình WAF sử dụng CharCNN dựa trên các nghiên cứu đã có và tiến hành huấn luyện, đánh giá.
-	Mô hình được áp dụng cho các ứng dụng web phổ biến, xác định độ hiệu quả cùng với khả năng chống lại các loại tấn công web thông thường cũng như mới xuất hiện, và triển khai kết quả nghiên cứu trên một ứng dụng thực tế.
Tiêu chí đánh giá	-	Đánh giá mức độ chính xác của mô hình WAF-CharCNN trong việc phát hiện các cuộc tấn công, giảm thiểu false positives và false negatives.
-	trên WAF  đánh giá tỉ lệ phát hiện tối ưu cách đánh giá độ chính xác.(trên 4 thông số precision, recall, f1-score, accuracy)
-	Đánh giá tốc độ xử lý của mô hình WAF-CharCNN, đảm bảo đáp ứng nhu cầu và không làm gián đoạn hoạt động của ứng dụng web.
-	Đánh giá khả năng mở rộng, tính linh hoạt của mô hình WAF-CharCNN để ứng dụng cho nhiều loại ứng dụng web khác nhau và điều chỉnh dễ dàng theo yêu cầu.
2.	Thiết kế mô hình và triển khai  	-	Xây dựng mô hình WAF-CharCNN, bao gồm quá trình tiền xử lý dữ liệu, thiết kế mạng nơ-ron tích chập cấp ký tự, huấn luyện và tối ưu hóa hệ thống.
-	Cài đặt mô hình WAF-CharCNN trên platform Colaboratory và tiến hành thử nghiệm.
-	Thu thập dữ liệu thực tế và dữ liệu thử nghiệm để huấn luyện mô hình từ đó đưa ra độ chính xác, độ phức tạp tính toán, khả năng xử lý thời gian, độ bảo mật và độ tin cậy trong việc phát hiện và ngăn chặn các loại tấn công web.
-	So sánh kết quả đánh giá của mô hình WAF-CharCNN với các phương pháp WAF hiện nay và đề xuất các hướng phát triển tiếp theo(Deep learning).
