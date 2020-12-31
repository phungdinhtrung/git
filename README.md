# Tutorial Git
## 1	Download and installl Git: https://git-scm.com
--------------------------------------------------------------
## 2	Local Repository
### 2.1	Git init
        Khởi tạo Local repository
### 2.2	Git status
### 2.3	Git add: add file to staged area
        - Add one file: git add <file>
        - Add multi file: git add . | git add *
### 2.4	Git checkout: restore file
        Sử dụng để khôi phục file về trạng thái trước khi chỉnh sửa.
        Lưu ý: file khởi restore phải không đang trong vùng Staged (trước đó chưa git add). Nếu đã <git add> vào vùng staged area thì phải remove ra khỏi vùng bằng lệnh git restore --staged <file>.
### 2.5	Git commit: add file from staged area to local repo
### 2.6	Git commit –amend: merge with commit before
### 2.7	Git log: view list commit
### 2.8	Git restore –staged <file>: remove file in staged area
--------------------------------------------------------------
## 3    Remote repository
### 3.1 Clone: clone remote to local
### 3.2 Git remote -v: view info remote repository (remote-name, remote link)
### 3.3 Git pull <remote-name> <local-name>
	Sử dụng để cập nhật các thay đổi trên Remote repo xuống Local repo.
### 3.4 Git push <remote-name> <local-name>
	Sử dụng để cập nhật các thay đổi dưới Local repo lên Remote repo.
### 3.5 Git branch: view list branch name (*: active branch).
	Sử dụng để liệt kê danh sách branch.
### 3.6 Git brach <name-branch>: create new branch.
### 3.7 






