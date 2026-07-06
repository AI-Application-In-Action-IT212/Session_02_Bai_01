# BÀI 1: Phân tích & Lựa chọn (Lựa chọn công cụ tối ưu & Hạn chế chuyển đổi ngữ cảnh)

## Đáp án lựa chọn

**Phương án C**

## Phân tích

Phương án C là tối ưu nhất vì lựa chọn đúng công cụ cho từng loại công việc, giúp tận dụng tối đa khả năng xử lý ngữ cảnh của AI và giảm thiểu việc chuyển đổi ngữ cảnh (Context Switching).

* Đối với việc viết tài liệu API Guide, Web Chat có khả năng diễn đạt ngôn ngữ tự nhiên tốt, hỗ trợ tạo tài liệu Markdown rõ ràng và dễ đọc.
* Đối với việc refactor đối tượng Book trên nhiều tệp như Book.java, BookService.java, BookController.java và BookRepository.java, Trợ lý lập trình cấp cao (Agentic/Repository-wide Assistant) có thể hiểu cấu trúc toàn bộ dự án, phân tích mối liên hệ giữa các tệp và cập nhật đồng bộ, giảm nguy cơ bỏ sót hoặc gây lỗi không nhất quán.
* Đối với lỗi cú pháp nhỏ tại một dòng cụ thể, Inline Code Assistant là lựa chọn nhanh nhất vì có thể sửa trực tiếp trong IDE mà không cần rời khỏi môi trường làm việc.

Cách tiếp cận này giúp giảm thời gian sao chép dữ liệu, tận dụng đúng phạm vi ngữ cảnh của từng công cụ và nâng cao năng suất phát triển phần mềm.

## Nhược điểm của phương án A

Phương án A yêu cầu liên tục sao chép mã nguồn giữa IDE và Web Chat. Điều này làm tăng chi phí chuyển đổi ngữ cảnh, mất thời gian và dễ xảy ra sai sót khi bỏ sót hoặc sao chép không đầy đủ các tệp liên quan.

Ngoài ra, Web Chat thường không có khả năng theo dõi toàn bộ cấu trúc dự án một cách tự động nên việc refactor nhiều tệp phụ thuộc lẫn nhau có nguy cơ thiếu nhất quán và phát sinh lỗi.

## Nhược điểm của phương án B

Inline Code Assistant hoạt động rất tốt với các tác vụ cục bộ và sửa lỗi nhanh, nhưng thường không phải công cụ tối ưu cho việc tạo tài liệu dài hoặc phân tích phạm vi toàn bộ dự án.

Đối với tác vụ refactor nhiều tệp phụ thuộc lẫn nhau, trợ lý dạng inline có thể chỉ nhìn thấy một phần ngữ cảnh đang mở trong IDE, dẫn đến khả năng bỏ sót các vị trí cần cập nhật. Đồng thời, việc soạn thảo tài liệu API quy mô lớn bằng công cụ inline cũng kém hiệu quả hơn so với Web Chat chuyên về xử lý ngôn ngữ tự nhiên.
