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
### 2.9	Git restore –staged <file>: remove file in staged area
### 3.10 Git branch
#### 3.10.1 Git branch: view list branch name (*: active branch).
	Sử dụng để liệt kê danh sách branch.
#### 3.10.2 Git brach <name-branch>: create new branch.
#### 3.10.3 Git branch -m <name-branch>: rename branch.
#### 3.10.4 Git checkout <name-branch>: switch branch.
	Sử dụng để chuyển đổi qua lại đến nhánh làm việc khác.
#### 3.10.5 Git merge <name-branch-merge>
	Sử dụng để gộp hai nhánh lại với nhau.
#### 3.10.6 Git branch --merged: view merged branchs with current branch (* branch)
	Sử dụng để xem nhánh nào đã gộp với nhánh hiện tại (nhánh có dấu *).
#### 3.10.7 Git branch --no-merged: view no merged branchs with current branch (* branch)
	Sử dụng để xem nhánh nào chưa gộp với nhánh hiện tại (nhánh có dấu *).
#### 3.10.8 Git branch -d <name-branch>: delete merged a branch
	Xóa một nhánh đã được gộp.
#### 3.10.9 Git branch -D <name-branch>: delete no-merged a branch
	Xóa nhánh chưa gộp

--------------------------------------------------------------
## 3    Remote repository
### 3.1 Clone: clone remote to local
### 3.2 Git remote -v: view info remote repository (remote-name, remote link)
### 3.3 Git pull <remote-name> <local-name>
	Sử dụng để cập nhật các thay đổi trên Remote repo xuống Local repo.
### 3.4 Git push <remote-name> <local-name>
	Sử dụng để cập nhật các thay đổi dưới Local repo lên Remote repo.








