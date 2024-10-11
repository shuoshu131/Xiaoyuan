# Xiaoyuan

采用抓包方式获取题目和答案, 通过 adb 模拟滑动操作

## 环境配置 :hammer_and_wrench:

1. 雷电9模拟器（安装有Lsposed）
2. python3
3. 打开模拟器adb选项

## 使用 :hammer_and_wrench:

1. 安装依赖
2. 配置模拟器
   magisk + Lsposed + trust me already
3. 配置 adb

- 打开开发者选项中的 usb 调试

```shell
adb devices
```

4. 配置安卓代理WIFI设置代理为电脑内网ip 和端口(8080)
5. 运行

```shell
python main.py -H <host> -P <port>
```

###### 代码借鉴于项目[cr4n5/XiaoYuanKouSuan: 小猿口算\_已达到0.01s ( 0.00s response 错误 ) (github.com)](https://github.com/cr4n5/XiaoYuanKouSuan)

```
