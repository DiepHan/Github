#Github là gì?  
- Github, còn được gọi là social network dành cho developer đi vào hoạt động tháng 2 năm 2008.    
- Github được viết bằng Ruby on Rails. 

**1.Cách thức làm việc với GitHub**
- Làm việc với GitHub nói riêng hay hệ thống GIT nói chung có 2 workflow chính là local workflow và server workflow.  

*a.Làm việc với repository ở local* 
- Với 2 command thường dùng là git add và git commit
  - git add: add file đã thay đổi vào stage  
  - git commit commit các file đã add vào stage lên repository ở local Ngoài ra bạn xem một số command khác  

*b.Làm việc với repository ở server github*
- push: push thay đổi từ repository local lên repository server  
- fetch: cập nhật thay đổi từ repository server về repository local  
- pull/rebase: sao chép source code từ server về local workspace 

**2.Setting up git**  
 Cài đặt Git tại địa chỉ http://git-scm.com/download/win 
 
**3.Generating and add SSH key** 
 - Để Tạo lại ssh key, bạn có thể nhấn vào nút Generate Key. Nếu có thể sẽ cần yêu cầu nhập passphrase (mật khẩu bảo mật). Hãy nhớ chuỗi mật khẩu này, bạn sẽ cần dùng lần sau.
 Lệnh tạo ssh keys trên giao diện tương ứng với command line:
`ssh-keygen -t rsa` 

- Thêm một ssh key:  
B1: Copy ssh key vào clipboard:  
`pbcopy < ~/.ssh/id_rsa.pub`  
B2: Sau đó lên tài khoản của bạn, vào mục setting, tìm tới mục Add ssh key và dán nội dung đã copy lúc nãy vào:  
![](https://i0.wp.com/appconus.com/blog/wp-content/uploads/2015/08/Screen-Shot-2015-08-06-at-10.52.07-PM.png)
