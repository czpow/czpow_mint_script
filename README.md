1.下载Node.js 
下载链接：https://nodejs.org/en/download

2.项目
安装完成nodejs后，

第二步
点击页面的Add file 选择 Upload files，下载并解压文件 注意复制路径
<img width="937" alt="image" src="https://github.com/czpow/czpow_mint_script/assets/157109154/58d8708a-0e6e-4d47-8dd0-1c2863ebb96b">

第三步
WEIN+R打开CMD 命令行
![image](https://github.com/czpow/czpow_mint_script/assets/157109154/33654464-da8f-4795-81e0-78bda4c1737c)

![image](https://github.com/czpow/czpow_mint_script/assets/157109154/47c48487-d575-4e47-a010-64cc5463370b)


项目根目录使用：
npm install 
<img width="925" alt="image" src="https://github.com/czpow/czpow_mint_script/assets/157109154/b9bc735f-4d1f-402d-a933-18a93fd11d11">

等待安装依赖成功之后
在server.js中 （js可用文本打开编辑保存）填写私钥、RPC节点、上级地址等数据
![image](https://github.com/czpow/czpow_mint_script/assets/157109154/a0a2eec6-b791-4224-b49a-92950787fd67)

cmd进入目录后输入：node server.js 回车，即可运行
![image](https://github.com/czpow/czpow_mint_script/assets/157109154/dc1fbe89-2bb5-43af-be57-c3f6483d5105)

注：
运行后可使用 ctrl + c 中断运行

单个地址参数演示
<img width="608" alt="image" src="https://github.com/czpow/czpow_mint_script/assets/157109154/c678c4a1-43c8-489e-8f9d-db6a1c421afc">
多个地址参数演示
<img width="647" alt="image" src="https://github.com/czpow/czpow_mint_script/assets/157109154/4452839f-fbe2-40f4-ae0b-db0e6b41e714">

