# Chrome Dev Tool
Để sửa bất cứ cái gì thì dùng

document.designMode = 'on'

Bấm vào button hover để tìm kiếm element tương ứng.

Chọn vào các active hoặc focus.. để hiển thị trạng thái tương ứng

Bấm vào màu bất kì để tìm mã màu tương ứng

Có thể chọn trang web hiển thị trên điện thoại, chọn device, chọn máy yếu mạnh.
Tương tự ở tag Network có thể chọn mạng nhanh hoặc chậm.

Ở tag Source. Nhấn Ctrl + P để chọn file source và nhấn Ctrl + G để nhảy tới row mong muốn để debug.
Có 1 cách debug nữa là đặt lệnh debugger ngay trong source code

Bấm Ctrl+Shift+F hoặc control + option + F trong mac để search code

Trong tag Console có thể chọn leve(Info, Warning, Error,..) để filter xem loại log cần xem

console.log('%cThanh','color:red; background-color:blue')
Hiển thị css trong code

Dùng Edit Breakpoint để log ra một biến hoặc 1 object. { Tênbien hoac TenObject}

const thanh = {name:"Thanh", deptrai:true, age:30}
Dùng Console.table(thanh) để xem data dưới dạng table

Chức năng autoclick

const delButtons = $$('.oajrlxb2.tdjehn4e.gcieejh5')
Array.from(delButtons).forEach(btn => btn.click())

Link tham khảo thêm
https://developers.google.com/web/tools/chrome-devtools?hl=ja
