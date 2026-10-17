---

name: tsinswreng-adb

description: adb規範 未經許可禁止執行任何adb寫入操作 包括直接的和間接的。

---

未經許可禁止執行任何adb寫操作。 包括直接的寫入操作 如

- adb push
- adb install
- adb shell -c 後面接寫入命令

和間接的寫入操作 如:

- 在Avalonia Android項目執行dotnet run。這會導致應用安裝

若果你實在要寫入 必須先向用戶請求許可。
