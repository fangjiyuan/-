# 唱的好听
根据歌词搜索歌曲片断

# 使用方法
需要安装的依赖

pip3 install pymusic-dl

建议手动安装获取最新更新

$ git clone https://github.com/0xHJK/music-dl.git

$ cd music-dl

$ python3 setup.py install


pip3 install pydub

然后修改主程序里的对应内容

keyword = '一件黑色毛衣'#请输入关键词

source = ['kugou','netease'] #暂时只写了酷狗和网易

ourdir = '/home/fangjiyuan/github_file/LRC/'#需要自定义输出文件夹

number = 10 #一次查询返回的歌曲条数

# 演示视频:
https://user-images.githubusercontent.com/36502693/174580645-7a95f5b7-4d3e-49de-9ded-98dd1face1d3.mp4



#感谢music-dl项目
https://github.com/0xHJK/music-dl

