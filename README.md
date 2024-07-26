Step1: git init
-> Khởi tạo repo dưới local

Step2: git checkout -b <name-branch>
-> tạo nhánh mới có tên là <name-branch>

- git status: kiểm tra từng nhánh

Step3: Commit code
- git add <fileNane> -> add từng file 1
- git add . -> add tất cả các file
- git commit -m "message"

Step4: Add remote
- git remote add origin <link-your-repo>

Step5: Push code
- git push origin
Login task
-> checkout về branch cần làm task

- Các câu lệnh git cơ bản:
    + git branch -d <branch-name> -> xóa 1 nhánh (lưu ý: khi xóa nhánh -> tất cả code bị mất & không lấy lại được
                                                    -> phải làm xong hết (release lên github) mới xóa nhánh)
    + git checkout -b <branch-name> -> tạo mới 1 nhánh và chuyển sang nhánh đó
    + git branch -> xem danh sách nhánh
    + git checkout <branch-name> -> chuyển nhánh
    + git remote add <remote-name> <link-remote> -> Thêm mới một remote
    # Trước khi commit -> ta phải add code:
    + git add . -> Add nhiều file cùng một lúc
    + git add <file-name> -> add từng file một
    + git commit -m "msg text" -> Commit code : lúc này code vẫn ở dưới local
    + git push origin <branch-name> -> đẩy code lên nhánh (origin : tên remote mà ta đặt)
    + git pull origin <branch-name> -> pull code (kéo code về) mới nhất của nhánh đó về local