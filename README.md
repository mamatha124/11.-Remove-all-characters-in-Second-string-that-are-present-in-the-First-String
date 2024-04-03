# 11.-Remove-all-characters-in-Second-string-that-are-present-in-the-First-String in python
a = input().strip()
b = input().strip()
result = ""
for char in b:
    if char not in a:
        result += char
print(result)
