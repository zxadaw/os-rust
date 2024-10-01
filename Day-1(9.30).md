### 在电脑上构建了基本的开发环境，了解了在做exercise过程中必须的一些命令行指令，包括git指令和rust指令

```rust
呈现完成情况：cargo run list
接下里的一个错误位置：cargo run watch
编译并运行：cargo build/run
(也可以用rustlings）

git提交：git commit -m "说明文字"
提交到github： git push
给出需要提交的文件： git add *

```

### 遇到的问题以及解决方案

使用rust-analyzer时候遇到

Failed spawning proc-macro server for workspace `/home/zsq/rust-rustlings-2024-autumn-zxadaw/rust-project.json`: no sysroot

![ad6890ceeaa87d1eb301896ed435961f.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/9e11a817-bd2d-4b27-9b8c-b9fb50e72b85/7bc65a77-b78f-4b26-bb72-b64e87632683/ad6890ceeaa87d1eb301896ed435961f.png)

最后在rust-project.json中添加了sysroot的路径解决

### exercise

完成了struct1.rs
