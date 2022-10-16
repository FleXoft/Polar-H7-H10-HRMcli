# Polar-H7-H10-HRMcli
Bluetooth Low Energy BLE cli mockup on macOS (Swift) with Polar H7 / H10 Heart Rate Monitor

I've been planning this ever since I successfully managed to put together the sceleton of the graphical version, to see how BLE / CoreBluetooth could be done through a pure simple cli interface in Swift.

Now I finally have some spare time to try and here is the result. Almost all the code from the original version could be reused.

To compile:

```
swiftc Polar-H7-H10-HRMcli.swift
or
swiftc -sdk `xcrun --show-sdk-path` Polar-H7-H10-HRMcli.swift
```

To use:

```
./Polar-H7-H10-HRMcli start
```
