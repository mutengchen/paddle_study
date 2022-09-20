arm安装paddle
https://paddleinference.paddlepaddle.org.cn/user_guides/download_lib.html#python


pip install xx.whl

#安装jutepyter
pip3 install jupyter

#生成jupyter配置文件
jupyter notebook --generate-config 

#修改配置：
c.NotebookApp.ip = '0.0.0.0' # listen on all IPs 运行所有设备登录
c.NotebookApp.token = ''     # disable authentication 免密码登录
c.NotebookApp.allow_origin = '*' # allow access from anywhere
c.NotebookApp.disable_check_xsrf = True # allow cross-site requests
c.NotebookApp.port = 8888 