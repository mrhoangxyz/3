# 3
3
def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32

celsius = float(input("Nhập nhiệt độ Celsius: "))
fahrenheit = celsius_to_fahrenheit(celsius)
print(f"{celsius} độ Celsius bằng {fahrenheit} độ Fahrenheit")
