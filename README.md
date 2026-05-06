# ChaoAIStudioToAPI

基于 ChaoAIStudioToAPI 二次开发，专为低配置服务器优化的 API 转换工具。

---

## ✨ 项目特点
- **低资源占用**：适配 4核4G（4h4g）服务器，可长期稳定运行
- **多账号支持**：支持同时登录 3 个账号并发调用
- **稳定性优化**：修复原项目在低配置环境下的资源占用过高、易崩溃等问题

---

## 🚀 快速部署
### 环境要求
- 服务器配置：最低 4核4G 内存
- 系统：Linux / Windows / macOS 均可
- 依赖：Node.js / Python（根据原项目环境调整）

### 部署步骤
1. 克隆本仓库
```bash
git clone https://github.com/hechaohc/ChaoAIStudioToAPI.git
cd ChaoAIStudioToAPI
 
 
2. 安装依赖
  
bash
    

# 按原项目的安装命令填写，例如：
npm install
# 或
pip install -r requirements.txt
     
     
3. 配置多账号
在配置文件中填写 3 个账号的信息，格式示例：
      
plaintext
        

ACCOUNT_1=账号1:密码
ACCOUNT_2=账号2:密码
ACCOUNT_3=账号3:密码
         
         
4. 启动服务
          
bash
            

# 按原项目的启动命令填写，例如：
node index.js
 # 或
python main.py
             
             
              
              
📌 使用说明
               
- 服务启动后，默认端口为  7860 ，可在配置文件中修改
               
- API 调用格式与原项目保持一致，兼容现有调用方式
               
- 3个账号会自动轮询负载，提升调用稳定性
                
                 
                 
📝 更新日志
                  
- 优化项目资源占用，适配 4h4g 服务器稳定运行
                  
- 新增多账号并发支持，最多可同时登录 3 个账号
                  
- 修复原项目已知的稳定性问题
                   
                    
                    
❤️ 致谢
                     
本项目基于 [https://github.com/iBUHub/AIStudioToAPI] 二次开发，感谢原作者的开源贡献。
