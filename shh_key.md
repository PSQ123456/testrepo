## create SSH key
`
ssh-keygen -t rsa -C "yourmail@example.com"
`
之后要求输入路径和密码，默认回车，产生文件在
`
~/.ssh/
`

验证是否成功
`
ssh -T git@github.com
`

