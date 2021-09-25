# Credit-Card
<p>Các ngân hàng thương mại nhận được rất nhiều đơn đăng ký làm thẻ tín dụng. Nhiều người trong số họ bị từ chối vì nhiều lý do, chẳng hạn như số dư khoản vay cao, mức thu nhập thấp hoặc quá nhiều yêu cầu trên báo cáo tín dụng của một cá nhân chẳng hạn. Việc phân tích các ứng dụng này theo cách thủ công là rất đơn giản, dễ xảy ra lỗi và tốn thời gian (và thời gian là tiền bạc). May mắn thay, nhiệm vụ này có thể được tự động hóa với sức mạnh của máy học và hầu hết mọi ngân hàng thương mại đều làm như vậy hiện nay. Trong sổ tay này, chúng tôi sẽ xây dựng một công cụ dự đoán phê duyệt thẻ tín dụng tự động bằng cách sử dụng các kỹ thuật máy học, giống như các ngân hàng thực thường làm.<pp>
<p> <img src = "https://assets.datacamp.com/production/project_558/img/credit_card.jpg" alt = "Thẻ tín dụng đang cầm trên tay"> </p>
<p> Chúng tôi sẽ sử dụng <a href="http://archive.ics.uci.edu/ml/datasets/credit+approval"> tập dữ liệu Phê duyệt thẻ tín dụng </a> từ Kho lưu trữ Máy học UCI. Cấu trúc của sổ ghi chép này như sau: </p>
<ul>
<li> Trước tiên, chúng ta sẽ bắt đầu bằng cách tải và xem tập dữ liệu. </li>
<li> Chúng ta sẽ thấy rằng tập dữ liệu có sự kết hợp của cả tính năng số và không phải số, nó chứa các giá trị từ các phạm vi khác nhau, cộng với việc nó chứa một số mục nhập bị thiếu. </li>
<li> Chúng tôi sẽ phải xử lý trước tập dữ liệu để đảm bảo mô hình học máy mà chúng tôi chọn có thể đưa ra dự đoán tốt. </li>
<li> Sau khi dữ liệu của chúng tôi ở trạng thái tốt, chúng tôi sẽ thực hiện một số phân tích dữ liệu khám phá để xây dựng trực giác của chúng tôi. </li>
<li> Cuối cùng, chúng tôi sẽ xây dựng một mô hình máy học có thể dự đoán liệu đơn đăng ký thẻ tín dụng của một cá nhân có được chấp nhận hay không. </li>
</ul>

