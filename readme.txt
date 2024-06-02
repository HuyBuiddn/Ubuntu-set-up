- Cap quyen truy cap 
https://www.youtube.com/watch?v=aQ3_HxHXR5o

- Chinh ten hien thi trong terminal
Mở Tệp Cấu Hình Shell:
Nếu bạn đang sử dụng Bash, mở tệp .bashrc:
sh
Copy code
nano ~/.bashrc
Nếu bạn đang sử dụng Zsh, mở tệp .zshrc:
sh
Copy code
nano ~/.zshrc
Chỉnh Sửa Prompt (PS1):
Tìm dòng bắt đầu bằng PS1= và chỉnh sửa nó. Ví dụ, bạn có thể thay đổi từ:
sh
Copy code
PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\$ '
thành một chuỗi ngắn hơn:
sh
Copy code
PS1='\u:\w\$ '
Trong đó:
\u: Tên người dùng hiện tại.
\h: Tên host (máy chủ) hiện tại.
\w: Thư mục hiện tại.
Bạn có thể tuỳ chỉnh các thành phần này theo ý muốn để làm cho tên hiển thị ngắn hơn. Ví dụ, để chỉ hiển thị tên người dùng và thư mục hiện tại:
sh
Copy code
PS1='\u:\w\$ '
Lưu và Đóng Tệp:
Để lưu tệp trong nano, nhấn Ctrl + O, sau đó nhấn Enter để xác nhận. Để thoát nano, nhấn Ctrl + X.
Tải Lại Cấu Hình Shell:
Để áp dụng thay đổi ngay lập tức, bạn cần tải lại tệp cấu hình:
sh
Copy code
source ~/.bashrc   # Đối với Bash
source ~/.zshrc    # Đối với Zsh

Chinh mau

Mở Tệp Cấu Hình Shell:
Nếu bạn đang sử dụng Bash, mở tệp .bashrc:
sh
Copy code
nano ~/.bashrc
Nếu bạn đang sử dụng Zsh, mở tệp .zshrc:
sh
Copy code
nano ~/.zshrc
Chỉnh Sửa Prompt (PS1):
Tìm dòng bắt đầu bằng PS1= và chỉnh sửa nó. Ví dụ, bạn có thể thay đổi từ:
sh
Copy code
PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\$ '
thành một chuỗi ngắn hơn:
sh
Copy code
PS1='\u:\w\$ '
Trong đó:
\u: Tên người dùng hiện tại.
\h: Tên host (máy chủ) hiện tại.
\w: Thư mục hiện tại.
Bạn có thể tuỳ chỉnh các thành phần này theo ý muốn để làm cho tên hiển thị ngắn hơn. Ví dụ, để chỉ hiển thị tên người dùng và thư mục hiện tại:
sh
Copy code
PS1='\u:\w\$ '
Lưu và Đóng Tệp:
Để lưu tệp trong nano, nhấn Ctrl + O, sau đó nhấn Enter để xác nhận. Để thoát nano, nhấn Ctrl + X.
Tải Lại Cấu Hình Shell:
Để áp dụng thay đổi ngay lập tức, bạn cần tải lại tệp cấu hình:
sh
Copy code
source ~/.bashrc   # Đối với Bash
source ~/.zshrc    # Đối với Zsh
