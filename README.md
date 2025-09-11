# 获取用户输入的重量及单位
weight_input = input()
# 提取数值部分（转换为浮点数）
weight = float(weight_input[:-2])
# 提取单位部分
unit = weight_input[-2:]
if unit == "kg":
    # 公斤转磅，1 公斤 = 2.2046 磅
    pound = weight * 2.2046
    # 保留 3 位小数并输出
    print(f"对应的英制重量为{pound:.3f}磅")
elif unit == "pd":
    # 磅转公斤，1 磅 = 1/2.2046 公斤
    kilogram = weight / 2.2046
    # 保留 3 位小数并输出
    print(f"对应的公制重量为{kilogram:.3f}公斤")
