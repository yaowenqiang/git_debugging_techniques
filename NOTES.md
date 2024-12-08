git bisect # git binary search of the commit history
git blame
git grep


git bisect start

git bisect good <good-commit>

git bisect bad <bad-commit>


git bisect good

git bisect bad

git bisect reset

git bisect run


https://git-scm.com/docs/git-bisect


git bisect run ls index.html


git blame filename

git blame -L line-range filename

git blame -L 76,82 filename

https://git-scm.com/docs/git-blame

git grep [options] pattern


git grep 'error'

git grep 'error'  -- '*.js'

git grep 'error'  -n

git grep 'error'  --line-numbers

git grep '[0-9]*error'  

git grep '[0-9]*error'   --branch-name

git grep --foramt '%f:%l:%O'  'error'

https://git-scm.com/docs/git-grep

















