# sophia

going to remote

```git
git branch -a
```

```git
git checkout -b <name>
```

```git
git add . && git commit -m "pushing to remote" && git push <remote> <name>
```

- where remote = origin
- where name = example

- Check for branches

```git
git branch -a
```

```bash
$ git branch -a
* example
  main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main

Anthr@LAPTOP-2IH011V4 MINGW64 ~/sophia (example)
$ git add . && git commit -m "example" && git push origin example
warning: CRLF will be replaced by LF in README.md.
The file will have its original line endings in your working directory
[example 831906c] example
 1 file changed, 24 insertions(+), 1 deletion(-)
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 405 bytes | 405.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'example' on GitHub by visiting:
remote:      https://github.com/rsskga/sophia/pull/new/example
remote:
To https://github.com/rsskga/sophia.git
 * [new branch]      example -> example
```


Now on branch vandy 