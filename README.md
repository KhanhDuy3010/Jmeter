# Jmeter
**Kiểm tra hiệu năng**
--
Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://facebook.com Chạy kịch bản kiểm tra và ghi lại kết quả. Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v. Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

**Kịch bản kiểm tra**
--
* Thread Group:
  
  *Số lượng thread: 1000*

  *Thời gian chạy: 1 phút 40 giây*

  *Ramp-up period: 10 giây*
  
* HTTP Request:
  
  *URL: https://facebook.com/*

  *Method: GET*

  *Content encoding: UTF-8*

* Listeners:
  
  *View Results Tree*

  *View Results In Table*

  *Aggregate Report*

**Kết quả kiểm tra**

* Thread group
  
![thread](https://github.com/KhanhDuy3010/Jmeter/assets/96983545/f855673b-234f-4231-bc4e-887d62b5341b)

* HTTP request

![http](https://github.com/KhanhDuy3010/Jmeter/assets/96983545/9ce0e448-0bbf-4c7a-893b-a8a92a75b8eb)

* View results tree

![tree](https://github.com/KhanhDuy3010/Jmeter/assets/96983545/6662a11e-14d1-4889-a2bb-f4cb89a48745)

* View results in table

![table](https://github.com/KhanhDuy3010/Jmeter/assets/96983545/a0f50a96-ac0a-4209-ba24-62570b521a2a)

* Aggregate Report

![report](https://github.com/KhanhDuy3010/Jmeter/assets/96983545/419aa773-dbd4-4cab-9483-7711048bff56)


  
