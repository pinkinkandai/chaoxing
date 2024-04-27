
            加了个界面
            加了一点功能，可以将账号保存在本地，选择账号登录，
            可以看到所有的课程，选择你想刷的课程
            <img width="669" alt="屏幕截图 2024-04-27 010005" src="https://github.com/pinkinkandai/chaoxing/assets/123379680/407394f7-b9ce-448f-a439-39b6b3da95a0">

:muscle: 本项目的最终目的是通过开源消灭所谓的付费刷课平台，希望有能力的朋友都可以为这个项目提交代码，支持本项目的良性发展    

:star: 觉得有帮助的朋友可以给个Star

## :point_up: 更新通知  
20231114更新通知： 3.0大版本更新，修复403报错，优化代码结构

## :books: 使用方法

### 源码运行
1. `git clone --depth=1 https://github.com/Samueli924/chaoxing` 项目至本地
2. `cd chaoxing`
3. `pip install -r requirements.txt`
4. (可选直接运行) `python main.py`
5. (可选配置文件运行)复制config_template.ini文件为config.ini文件，修改文件内的账号密码内容, 执行 `python main.py -c config.ini`
6. (可选命令行运行)`python main.py -u 手机号 -p 密码 -l 课程ID1,课程ID2,课程ID3...(可选)`

### 打包文件运行
1. 从最新[Releases](https://github.com/Samueli924/chaoxing/releases)中下载exe文件
2. (可选直接运行) 双击运行即可
3. (可选配置文件运行)下载config_template.ini文件保存为config.ini文件，修改文件内的账号密码内容, 执行 `./chaoxing.exe -c config.ini`
4. (可选命令行运行)`./chaoxing.exe -u "手机号" -p "密码" -l 课程ID1,课程ID2,课程ID3...(可选)`

## :heart: CONTRIBUTORS  
### :one:感谢[huajijam](https://github.com/huajijam)对chaoxing项目的贡献! [PR #73](https://github.com/Samueli924/chaoxing/pull/73)
### :two:感谢[ljy0309](https://github.com/lyj0309)修复Attachments BUG! [PR #70](https://github.com/Samueli924/chaoxing/pull/70)
### :three:感谢[Shanxuns](https://github.com/Shanxuns)修正查找任务点的正则表达式内容 [Pull #33](https://github.com/Samueli924/chaoxing/pull/33)  
### :four:感谢[B1gM8c](https://github.com/B1gM8c)修复登录密码加密BUG[Pull #118](https://github.com/Samueli924/chaoxing/pull/118)  
### :five:感谢[RyaoChengfeng](https://github.com/RyaoChengfeng)添加Docker运行支持[Pull #125](https://github.com/Samueli924/chaoxing/pull/125)  
### :six:感谢[a81608882](https://github.com/a81608882)修复403报错BUG[Pull #142](https://github.com/Samueli924/chaoxing/pull/142)
### :seven:感谢[yhm97](https://github.com/yhm97)修复音频格式导致的403BUG[Pull #187](https://github.com/Samueli924/chaoxing/pull/187) 
### :eight:感谢[evibhm](https://github.com/evibhm)修复Docker运行的DNS问题、优化Docker映像大小[Pull #232](https://github.com/Samueli924/chaoxing/pull/232)
### 对于代码有任何问题或建议欢迎Pull&Request

## :warning: 免责声明  
- 本代码遵循 [GPL-3.0 License](https://github.com/Samueli924/chaoxing/blob/main/LICENSE)协议，允许**开源/免费使用和引用/修改/衍生代码的开源/免费使用**，不允许**修改和衍生的代码作为闭源的商业软件发布和销售**，禁止**使用本代码盈利**，以此代码为基础的程序**必须**同样遵守[GPL-3.0 License](https://github.com/Samueli924/chaoxing/blob/main/LICENSE)协议  
- 本代码仅用于**学习讨论**，禁止**用于盈利**  
- 他人或组织使用本代码进行的任何**违法行为**与本人无关  
