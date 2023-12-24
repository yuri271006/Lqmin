# Source code Lqmin

<!--Định nghĩa-->

--> Code được xây dựng dựa trên ý tưởng chia bố cục trang thành các thành phần nhỏ gọi là "min". Chúng được gọi qua trang chính là index.html nhờ kĩ thuật "Ajax" từ thư viện "Jquery".

## Các qui chuẩn code

<!--File Javascript nguồn-->

--> File này nên được định danh mặc định có tên là "lqmin.js" và nằm cùng cấp với file index.html

<!--Cấu trúc của file Javascript nguồn-->

--> Có dạng: 
function lqmin(){
    //Các "min" được load ở đây.
}lqmin();

### Các qui chuẩn về gọi thành phần "min"

--> Chúng nên có dạng:

1. Đối với text: Calltxt = "" hoặc Reqtxt = "" ngắn gọn hơn m-txt = "";
2. Đối với các classname, id thành phần main, nếu sử dụng hãy luôn cho tiền tố m- vào chúng:

--> Đối với "min" cha: m-pa  và "min" con: m-ch
--> Sẽ còn cập nhật thêm

#### Các thẻ đặc biệt: 

--> Chúng tôi không khuyến khích dùng nó vì đây chưa phải là thẻ chính thống, chúng chỉ được hiểu trong lqmin!

1. Thẻ thể hiện văn bản được lấy từ Sever hoặc được thay đổi khi có sự kiện: <mTxt></mTxt> và đừng quên cho chúng các hậu tố định nghĩa CallTxt hay Reqtxt

2. 

