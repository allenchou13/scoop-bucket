# Scoop Bucket

为了方便使用Scoop，建立git仓库作为Scoop Bucket使用。

## 配置 Scoop 使用此 Bucket

```
scoop bucket add mybucket https://github.com/allenchou13/scoop-bucket.git
```

## 使用示例
```
> scoop search hello
'mybucket' bucket:
    hello (1.0)
    
> scoop install hello
Installing 'hello' (1.0) [64bit]

hello.ps1 (49 B) [============================================] 100%
WARN  Warning: No hash in manifest. SHA256 for 'hello.ps1' is:
    87de64f8d0391f83b95e4738494d2a565f05392735ffe297899b3c1d5492d7d0
Linking ~\scoop\apps\hello\current => ~\scoop\apps\hello\1.0
Creating shim for 'hello'.
'hello' (1.0) was installed successfully!


> hello
Hello, zhouyue!

```
