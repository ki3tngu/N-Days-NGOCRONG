<div align="center">
  
# N-Days-NGOCRONG - Bài 1
Build và chạy server, nhận biết và chỉnh sửa thông số cơ bản

 <a class="header-badge" target="_blank" href="https://www.facebook.com/Ki3tNgu/">
        <img src="https://img.shields.io/badge/style--5eba00.svg?label=Facebook&logo=facebook&style=social">
    </a>
    <a class="header-badge" target="_blank" href="https://www.youtube.com/@JINN1368">
        <img alt="Youtube" src="https://img.shields.io/badge/style--5eba00.svg?label=Youtube&logo=youtube&style=social">
    </a>
     <a class="header-badge" target="_blank" href="https://github.com/ki3tngu/">
        <img alt="Github" src="https://img.shields.io/badge/style--5eba00.svg?label=Github&logo=github&style=social">
    </a><br>
    <img alt="Donate" src="https://cdn.worldvectorlogo.com/logos/momo-2.svg" style="width:20px;" /> 0853035354
    <img alt="Donate" src="https://play-lh.googleusercontent.com/eropcks-sakGkOkCHQzpd87FKK4efHTLY5b93H2FwNLjoPnPcAMSzOHsm3s6lguSgw" style="width:20px;" /> 0853035354<br>
    <a href="https://github.com/ki3tngu/NgocRongTermux" target="_blank">Ngọc Rồng Offline</a>
    <br>
    <sub>Tác giả:
        <a href="https://www.youtube.com/@JINN1368" target="_blank">JINN1368</a><br>
        <small> Tháng 11, 2024</small>
    </sub>
</div>

Giải nén file source đã tải ở bài 0 và mở tệp `girlkundb.properties` <br>
- Đường dẫn: `..\data\config\girlkundb.properties`

    - Giải thích: <br>
`girlkun.database.name=jinro`: `jinro` là tên database hiện tại, bạn có thể đổi lạim khi đổi phải đổi lại tên trong src game<br>
- Đường dẫn: `..\data\girlkun.girlkundb.properties`

    - Giải thích:<br>
`server.girlkun.sv=1`: số server, giống vũ trụ 1, 2,3 ... ở đây chỉ có 1 server<br>
`server.girlkun.port=14445`: port của server, ví dụ server game có ip: 127.0.0.1:14445<br>
`server.girlkun.name=JINN`: Tên server, khi đổi không ảnh hưởng đến src game<br>
        ```
        server.girlkun.waitlogin=0
        server.girlkun.maxperip=20
        server.girlkun.maxplayer=20000
        server.girlkun.expserver=5
        ```
        lần lượt là: 
        - thời gian đăng nhập khi bị đăng xuất đột ngột
        - Số tài khoản / 1 thiết bị ( mặc định 5 tài khoản / 1 thiết bị)
        - Số người chơi tối đa của server
        - Exp khi farm
### Chạy và build server
- ${{\color{red}{\textsf{Bật XAMPP và khởi động database \}}}}\$
<img src="xampp.png">
    - Truy cập [http://localhost/phpmyadmin/] để tạo database
- để chạy server nhấn vào biếu tượng này ở IDE: <br>
<img src="buildAndRun.png">
    - Phần khoanh đỏ là build server, xanh là chạy server
    - Để test server háy tự tải cho mình một phiên bản nro
