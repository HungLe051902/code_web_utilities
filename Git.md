**CHÚ Ý**: Làm việc với git bash phải để ý cả từng dấu ';' và dấu ' '

## Git bash
Command | Meaning
--- | ---
git cherry-pick <commit_id> | Lấy commit từ nhánh khác sang nhánh hiện tại 
git rebase | lấy các commit của nhánh feature để đặt xuống cuối các commit của nhánh master
git config --global alias.adog 'log --all --decorate --oneline --graph' | Đặt alias để viết nhanh hơn
git config --global alias.sus '!f() { git push -u origin \"$1\"; }; f' | Set upstream local branch 
git checkout <fileName> or git restore <fileName> | undo changes <fileName>

## Git config
**git config --global --edit**: sửa file .gitconfig
