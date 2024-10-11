# Xiaoyuan

小猿口算, 采用抓包方式获取题目和答案, 通过 adb 模拟滑动操作

## 目录

- [环境配置 :hammer_and_wrench:](#环境配置-hammer_and_wrench)
- [使用 :hammer_and_wrench:](#使用-hammer_and_wrench)

## 环境配置 :hammer_and_wrench:

1. root 的安卓设备(lsposed 等) :iphone:
2. python3 :snake:
3. adb :electric_plug:

## 使用 :hammer_and_wrench:

1. 安装依赖

```shell
pip install -r requirements.txt
```

2. 配置 root 设备

采用 trust me already 禁用 app ssl

3. 配置 adb

- 打开开发者选项中的 usb 调试

```shell
adb devices
```

4. 配置安卓代理

WIFI 设置代理为电脑 ip 和端口(8080)

5. 运行

```shell
python main.py -H <host> -P <port>
```

例如：

```shell
python main.py -H 0.0.0.0 -P 8080
```
