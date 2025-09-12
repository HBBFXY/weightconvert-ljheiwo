import sys
def main():
    input_line = sys.stdin.read().strip()
    if input_line.endswith("kg"):
        num = float(input_line[:-2])
        pounds = num * 2.2046
        print(f"对应的英制重量为{pounds:.3f}磅")
    elif input_line.endswith("pd"):
        num = float(input_line[:-2])
        kg = num * 0.4535
        print(f"对应的公制重量为{kg:.3f}公斤")
if __name__ == "__main__":
    main()
