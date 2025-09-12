```python
input_str = input().strip()
if input_str.endswith("kg"):
    kg = float(input_str[:-2])
   .endswith("kg"):
    kg = float(input_str[:-2])
    pounds pounds = kg * 2.2046
    print(f"对应的英制重量为{pounds:. = kg * 2.2046
    print(f"对应的英制重量为{pounds:.3f}磅")
elif input_str.endswith("pd"):
    pd = float(input_str[:-2])
    kg = pd * 0.4535
    print(f"对应的公3f}磅")
elif input_str.endswith("pd"):
    pd = float(input_str[:-2])
    kg = pd * 0.4535
    print(f"对应制重量为{kg:.3f}公斤")
