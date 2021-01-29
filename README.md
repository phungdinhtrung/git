# Tutorial Git
--------------------------------------------------------------

## 1	Download and installl Git: https://git-scm.com
--------------------------------------------------------------

## 2	Local Repository
### 2.1	Git init
        Khởi tạo Local repository
### 2.2 Git config
	$ git config --global user.name "John Doe"
	$ git config --global user.email johndoe@example.com
### 2.3	Git status
### 2.4	Git add: add file to staged area
        - Add one file: git add <file>
        - Add multi file: git add . | git add *
### 2.5	Git checkout: restore file
        Sử dụng để khôi phục file về trạng thái trước khi chỉnh sửa.
        Lưu ý: file restore phải không nằm trong vùng Staged (trước đó chưa git add). Nếu đã <git add> vào vùng staged area thì phải remove ra khỏi vùng bằng lệnh git restore --staged <file>.
### 2.6	Git commit: add file from staged area to local repo
### 2.7	Git commit –amend: merge with commit before
### 2.8	Git log: view list commit
### 2.9	Git restore –staged file-name: remove file in staged area
### 3.10 Git branch
#### Git branch: view list branch name (*: active branch).
	Sử dụng để liệt kê danh sách branch.
#### Git brach name-branch: create new branch.
#### Git branch -m name-branch: rename branch.
#### Git checkout name-branch: switch branch.
	Sử dụng để chuyển đổi qua lại đến nhánh làm việc khác.
#### Git merge name-branch-merge
	Sử dụng để gộp hai nhánh lại với nhau.
#### Git branch --merged: view merged branchs with current branch (* branch)
	Sử dụng để xem nhánh nào đã gộp với nhánh hiện tại (nhánh có dấu *).
#### Git branch --no-merged: view no merged branchs with current branch (* branch)
	Sử dụng để xem nhánh nào chưa gộp với nhánh hiện tại (nhánh có dấu *).
#### Git branch -d name-branch: delete merged a branch
	Xóa một nhánh đã được gộp.
#### Git branch -D name-branch: delete no-merged a branch
	Xóa nhánh chưa gộp

--------------------------------------------------------------
## 3    Remote repository
### 3.1 Clone: clone remote to local
### 3.2 Git remote -v: view info remote repository (remote-name, remote link)
### 3.3 Git pull remote-name local-name
	Sử dụng để cập nhật các thay đổi trên Remote repo xuống Local repo.
### 3.4 Git push remote-name local-name
	Sử dụng để cập nhật các thay đổi dưới Local repo lên Remote repo.








