# Github guideline

## Đẩy 1 project có sẵn lên github

1. Tạo 1 repository trên github.com
2. Clone repository đó về máy
3. Copy files từ project có sẵn sang folder vừa clone về
4. Đổi github account bằng lệnh:
```sh
git-acc thaobuihb
```
5. Đổi remote url sang account thaobuihb bằng lệnh:
```sh
git remote set-url origin git@github.com-thaobuihb:thaobuihb/Counter.git
```
6. Add các thay đổi vào git bằng lệnh:
```sh
git add .
```
7. Commit:
```sh
git commit -m "nội dung của pull request"
```
8. Đẩy lên:
```sh
git push
```

## Todo
- Tạo branch
- Tạo pull request
- Merge pull request
