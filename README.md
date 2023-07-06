# DE-Project01

1. Giới thiệu về data
   Data nằm ở file csv, là 1 dataset về thương mại điện tử , với 10000 dòng mô tả thông tin cá nhân về người mua hàng, thông tin giao dịch mà khách hàng thực hiện ở trên website và những thông tin về cách thức truy cập của khách hàng. 

Thông tin cá nhân bao gồm địa chỉ, email, nghề nghiệp, nơi họ làm việc . Những thông tin giao dịch chủ yếu về thông tin của credit card, số tiền họ bỏ ra để mua hàng. Bên cạnh đó dataset này còn có các thông tin khách hàng truy cập trang web từ IP nào, browser, ngôn ngữ và thời gian mua hàng

Lưu ý các thông tin nhạy cảm của khách hàng như credit card , cc security code đều không được mã hóa trong data set này

2. File CommonFunction
   Để hiều về data, bạn có thể dùng các CommonFunction trong file CommonFunction.ipynb
Các thao tác cơ bản để hiểu data bao gồm: 
- Function để kiểm tra shape của data,
- Function để kiểm tra tên và loại của từng cột
- Function để kiểm tra giá trị lặp lại ( dùng nếu cần)
- Function để kiểm tra các giá trị trống trong cột ( dùng nếu cần)
- Function để kiểm tra các giá trị duy nhất trong cột ( dùng cho category nếu cần)
- Function để vẽ bar plot- Function để vẽ box plot- Function để vẽ pie chart
