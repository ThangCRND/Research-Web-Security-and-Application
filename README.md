# Research-Web-Security-and-Application

Web Application Firewall using Character-level Convolutional Neural Network

Dưới đây là một bảng bạn có thể thêm vào file README.md để tóm tắt thông tin từ đoạn văn của bạn:

| **#** | **Nội dung**                              |
|-------|----------------------------------------|
| 1     | **Tóm tắt đề tài**                      |
|       | Trong bối cảnh ngày càng phát triển của ứng dụng web và kỷ nguyên số hoá, việc bảo mật các hệ thống web trở nên cực kỳ quan trọng. Đồ án đề xuất xây dựng một hệ thống tường lửa ứng dụng web (WAF) dựa trên mô hình Mạng nơ-ron tích cập ký tự (CharCNN). |
| 2     | **Mục tiêu nghiên cứu**                 |
|       | - Nghiên cứu, tổng hợp kiến thức và hiểu rõ hơn về hệ thống tường lửa ứng dụng web (WAF) và nguyên lý hoạt động của Mạng nơ-ron tích cập ký tự (CharCNN). <br>- Đề xuất một mô hình WAF dựa trên CharCNN để cải thiện khả năng phát hiện và ngăn chặn các cuộc tấn công và đảm bảo an toàn cho các ứng dụng web. <br>- Đánh giá hiệu quả của mô hình đề xuất thông qua các tiêu chí đánh giá và so sánh với các phương pháp WAF hiện nay. |
| 3     | **Phạm vi nghiên cứu**                   |
|       | - Tập trung vào nghiên cứu các công trình liên quan đến hệ thống tường lửa ứng dụng web (WAF) và Mạng nơ-ron tích cập ký tự (CharCNN). <br>- Xây dựng một mô hình WAF sử dụng CharCNN dựa trên các nghiên cứu đã có và tiến hành huấn luyện, đánh giá. <br>- Mô hình được áp dụng cho các ứng dụng web phổ biến, xác định độ hiệu quả cùng với khả năng chống lại các loại tấn công web. |
| 4     | **Tiêu chí đánh giá**                    |
|       | - Đánh giá mức độ chính xác của mô hình WAF-CharCNN trong việc phát hiện các cuộc tấn công, giảm thiểu false positives và false negatives. <br>- Đánh giá tỉ lệ phát hiện tối ưu cách đánh giá độ chính xác trên WAF (precision, recall, f1-score, accuracy). <br>- Đánh giá tốc độ xử lý của mô hình WAF-CharCNN, đảm bảo đáp ứng nhu cầu và không làm gián đoạn hoạt động của ứng dụng web. <br>- Đánh giá khả năng mở rộng, tính linh hoạt của mô hình WAF-CharCNN để ứng dụng cho nhiều loại ứng dụng web khác nhau và điều chỉnh dễ dàng theo yêu cầu. |
| 5     | **Thiết kế mô hình và triển khai**       |
|       | - Xây dựng mô hình WAF-CharCNN, bao gồm quá trình tiền xử lý dữ liệu, thiết kế mạng nơ-ron tích cập ký tự, huấn luyện và tối ưu hóa hệ thống. <br>- Cài đặt mô hình WAF-CharCNN trên platform Colaboratory và tiến hành thử nghiệm. <br>- Thu thập dữ liệu thực tế và dữ liệu thử nghiệm để huấn luyện mô hình từ đó đưa ra độ chính xác, độ phức tạp tính toán, khả năng xử lý thời gian, độ bảo mật và độ tin cậy trong việc phát hiện và ngăn chặn các loại tấn công web. <br>- So sánh kết quả đánh giá của mô hình WAF-CharCNN với các phương pháp WAF hiện nay và đề xuất các hướng phát triển tiếp theo (Deep learning). |
| 6     | **Kết quả triển khai**                   |
|       | - Xây dựng được mô hình WAF-CharCNN trong bài báo theo kiến trúc của model A. <br>- Thực hiện thử nghiệm trên bộ dữ liệu dataset SCIC2010 trong bài báo, ngoài ra đã mở rộng huấn luyện trên 1 bộ dataset ISCX-URL-2016 để so sánh các thuộc tính tương tự. |






-	Kết quả triển khai 
Built model 
-	Xây dựng 1 model theo kiến trúc của model A 
 ![image](https://github.com/ThangCRND/Research-Web-Security-and-Application/assets/130020047/cda5eb75-bc9b-44e6-8ae2-83f62d80a195)

![image](https://github.com/ThangCRND/Research-Web-Security-and-Application/assets/130020047/d14f8882-d882-4ef7-832f-000f0666e5e5)

 



Dataset SCIC2010
-	Cài đặt: model được học với 30 Epochs, input_size là 1400 ký tự và output_size là 2.

-	Evaluate sau khi train:
 ![image](https://github.com/ThangCRND/Research-Web-Security-and-Application/assets/130020047/a3fc92fd-f963-4073-99ab-11de49fd6c77)


-	Predict trên test data:
labels:
•	valid = 0
•	malicious = 1
 ![image](https://github.com/ThangCRND/Research-Web-Security-and-Application/assets/130020047/f641d212-5146-4c94-a3e8-f82cf50c3970)


ISCX-URL-2016
-	Cài đặt: model được học với 50 Epochs, input_size là 1500 ký tự và output_size là 5.
-	Evaluate sau khi train:
 ![image](https://github.com/ThangCRND/Research-Web-Security-and-Application/assets/130020047/b4f89223-24d5-491c-b288-ea8f61efe1ab)


-	Predict trên test dataset:
Labels:
•	benign = 0
•	defacement = 1
•	malware = 2
•	phishing = 3
•	spam = 4
 ![image](https://github.com/ThangCRND/Research-Web-Security-and-Application/assets/130020047/3591dbe8-9c23-4782-8b18-3db8a6754caf)


