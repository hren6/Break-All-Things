# Break-All-Things

I want to break and then repaire them. I expect to succeed at the first part


Specifically, I want to create a merge conflict.


--shell

git config --global diff.tool vscode

git config --global diff.tool.vscode.cm'code --wait --diff "$LOCAL" "$REAMOTE"'

git config --global diff.tool.prompt false

git config --global merge.tool vscode

git config --global mergetool.vscode.cmd'code --wait --diff "$LOCAL" "$REAMOTE"'
