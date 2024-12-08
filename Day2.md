<div align="center">
  
# N-Days-NGOCRONG - Bài 2
Chỉnh sửa tỉ lệ đập đồ

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
        <small> Tháng 12, 2024</small>
    </sub>
</div>

- Truy cập đường dẫn: `com.girlkun.services.func\CombineServicesNew.java`
    - getGold: Vàng cần để nâng cấp
    - getRatio: Tỉ lệ thành công
    - getGem: Ngọc, hồng ngọc cần để nâng cấp
    - Các `case`: càng nhiều `case` thì càng nhiều sao<br>
    ví dụ: cho phép tối đa 5 sao hoặc 5 level:
    ```
    case 0:
        return 50000000;
    case 1:
        return 60000000;
    case 2:
        return 70000000;
    case 3:
        return 80000000;
    case 4:
        return 90000000;
    case 5:
        return 100000000;
    ```
    - ví dụ 2: chỉnh sửa để lên 7 sao:
    ```
    case 0:
        return 50000000;
    case 1:
        return 60000000;
    case 2:
        return 70000000;
    case 3:
        return 80000000;
    case 4:
        return 90000000;
    case 5:
        return 100000000;
    case 6:
        return 110000000;
    case 7:
        return 120000000;
    ```
    - **Lưu ý**: khi chỉnh sửa các `case` thì các hàm khác đều phải có thêm `case` tương ứng
    ví dụ: hàm `getRatio...` có `7 case` thì hàm `getGem`, `getGold` đều phải có 7 case
