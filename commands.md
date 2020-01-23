# hello-world

file (unstaged)
git add (doc is staged)
git commit
git push (fetch+merge)

commit, tree, blob (binary large object)
git show -s --pretty=raw ___ (the name of a commit)
git ls-tree ___ (the name of a tree)
git show ___(the name of a blob)

(been commited):
git --soft HEAD^
git --mixed HEAD^
git --hard HEAD^ !irreversible!