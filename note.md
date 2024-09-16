1. git init : được dùng khởi tạo một Repo trên máy local(máy tính cá nhân) mà chưa push lên server(github)
2. git status: được dùng để xem trạng thái những thay đổi
3. git add + tên file/ . / *: cho phép chuẩn bị lưu lại thời điểm hiện tại của dự án
4. git reset : cho phép lấy ra file chuẩn bị lưu
5. git commit -m ‘note’ : cho phép lưu code tại thời điểm và phải note lại để đánh dấu
6. git log : cho phép xem lại những thời điểm chúng ta đã lưu trước đó, được phân chia theo các note ta đã đánh dấu
 Để gọn hơn ta dùng: git log –oneline
7. git checkout id : cho phép ta trở lại các commit đã được lưu trước đó thông qua id của note
8. Git checkout <brand_name>: lệnh chuyển nhánh trong Git
9. Git branch : cho phép xem các branch hiện có trong Git, để thoát chế độ xem,    :q
10. Git checkout -b <branch_name>: cho phép tạo một branch mới 
11. Git merge <branch_name_B>: tổng hợp lại nhánh hiện tại(A) và nhánh cần(B)
12. Git branch -d <branch_name>: xóa branch cần xóa
conflict
13. Git push URL_Repo <branch_name> : giúp đẩy dữ liệu từ local repo lên remote repo
Cách khác: tạo ALIAS(Bí Danh) cho URL nhanh hơn
Git remote add alias URL_Repo  →  git push alias <branch_name>
14. Git clone URL_Repo: lấy code từ git trên mạng public và tải về máy sau đó tự tạo luôn 1 repo kết nối giữa local và remote
   Không cần ALIAS mà chỉ cần git push là sẽ tự động đẩy lên GitHub
15.
Git fetch origin: cập nhật thay đổi từ branch nhưng không merge lại, hình thức: xem lần cuối cập nhật
Git push -u origin <branch_name>: cập nhật branch mới từ local tới remote
16. Git checkout -b <branch_name> origin/<branch_name>: kéo xuống branch từ remote về local
17. Pull request: cho phép merge branch trên GitHub
      Git pull: kéo về dữ liệu cập nhật trên GitHub từ remote tới local
18.  .gitignore: thư mực không muốn Git quan tâm
