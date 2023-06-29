# 专注时钟
import time

# 设置专注时间和休息时间（单位为秒）
focus_time = 25 * 60
break_time = 5 * 60

# 定义一个函数，用于显示倒计时
def countdown(seconds):
    while seconds > 0:
        # 将秒数转换为分和秒
        minutes, seconds = divmod(seconds, 60)
        # 格式化输出
        print(f"{minutes:02d}:{seconds:02d}", end="\r")
        # 每隔一秒更新一次
        time.sleep(1)
        seconds -= 1

# 开始专注时钟
print("开始专注！")
countdown(focus_time)
print("专注结束，休息一下！")
countdown(break_time)
print("休息结束，继续专注！")
