**CHÚ Ý**: Làm việc với git bash phải để ý cả từng dấu ';' và dấu ' '

## Git bash
Command | Meaning
--- | ---
git cherry-pick <commit_id> | Lấy commit từ nhánh khác sang nhánh hiện tại 
git rebase | lấy các commit của nhánh feature để đặt xuống cuối các commit của nhánh master
git config --global --edit | Mở file config để sửa
git config --global alias.adog 'log --all --decorate --oneline --graph' | Đặt alias để viết nhanh hơn
git config --global alias.sus '!f() { git checkout -b \"$1\"; git push -u origin \"$1\"; }; f' | Create and Set upstream local branch 
git config --global alias.cm 'commit -m' | .
git checkout <fileName> or git restore <fileName> | undo changes <fileName>
git checkout <commit_hash> => git switch -c <branch_name> | Nhảy về thời điểm commit cũ và tạo nhánh mới từ thời điểm đó
git reset --hard 0d1d7fc32 | Hard delete unpublished commits
git branch -vv | Kiểm tra origin branch
git revert  | Undo published commits with new commits

## Git config
**git config --global --edit**: sửa file .gitconfig
