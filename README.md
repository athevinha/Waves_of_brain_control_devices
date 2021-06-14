  BỐI CẢNH: Trong bối cảnh cuộc cách mạng công nghiệp lần thứ tư (4.0), công nghệ giao diện máy tính-não (BCI) là công nghệ dựa trên các phương pháp giao tiếp không dây và điều khiển tự động. Đến nay nhiều các nghiên cứu đã cố gắng phát triển một hệ thống BCI dựa trên tín hiệu điện sinh học trích xuất từ bộ não (EEG, EcorG, v.v.) để phục vụ các mục đích giao tiếp nhằm cải thiện chất lượng cuộc sống của những người khuyết tật nặng, chẳng hạn như bệnh xơ cứng teo cơ một bên (ALS), tê liệt, đột quỵ não, v.v. <br/>
  Trong công trình này chúng tôi đề xuất thiết bị hệ thống không xâm lấn VHBCIS (tên do chúng tôi đặt) có thể giúp cung cấp phương pháp mới để hỗ trợ cuộc sống của người bại liệt và người già.
  MỤC TIÊU: Mục tiêu của bài báo này là khám phá cách thiết lập VHBCIS hiệu quả về chi phí và an toàn nhằm dùng để sử dụng hỗn hợp đa kênh (kết hợp giữa tín hiệu sóng não và các tín hiệu cơ mặt) hướng tới việc điều khiển các thiết bị nhà thông minh.
  PHƯƠNG PHÁP: Thiết bị thu nhận EEG di động (Emotiv EPOC X) được sử dụng để thu thập các tín hiệu biến đổi liên tục theo thời gian chưa qua xử lý EEG (tín hiệu EEG thô). 
còn lại nhóm nghiên cứu tìm tòi và lập trình dựa trên các các giao thức WebSocket, JSON sử dụng ngôn ngữ lập trình Python và C. Các tín hiệu thô sau đó được rời rạc hóa  nhờ vào phép biến đổi wavelet rời rạc (DWT).
  Tiếp theo phương pháp phân tích tương quan chính tắc (CCA) được sử dụng để thu được các dạng sóng đặc trưng và phân loại (classification). Kết quả phân loại sóng có thể được dịch thành các lệnh để điều khiển một số thiết bị cho ngôi nhà thông minh thông qua giao thức giao tiếp hai chiều tiên tiến MQTT. 
KẾT QUẢ DỰ KIẾN: Thiết bị hệ thống VHBCIS bao gồm: Thiết bị thu nhận EEG di động (Emotiv EPOC X), Arduino Mega  tích hợp modul wifi ESP8266 (lua), nguồn điều khiển 5V-3A và nguồn điện lưới, các đầu nối, dây và phíc cắm v.v. 
  Chúng tôi dự kiến tích hợp vào VHBCIS 5 lệnh điều khiển khác nhau để điều khiển bốn thiết bị cơ bản trong một căn phòng bệnh nhân bị bại liệt, bao gồm: đèn, quạt máy, Radio, rèm thông minh. Kết quả thử nghiệm đạt được mức độ chính xác trên 90% cho người thử nghiệm có tinh thần khỏe mạnh.
