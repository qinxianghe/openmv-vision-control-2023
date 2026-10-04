# OpenMV Vision Control — 2023

Historical OpenMV/MicroPython source associated with the 2023 National Undergraduate Electronic Design Contest, problem E, as stated in the original repository note.

The scripts use camera/image processing, board APIs, UART communication, and servo-control scaffolding. They target OpenMV hardware rather than desktop Python.

```text
firmware/openmv/main.py    Original 总程序.py
firmware/openmv/task_1.py  Original 第一个 task script (第一题1.1.py)
firmware/openmv/task_2.py  Original 第2题(1).py
firmware/openmv/task_3.py  Original 第三题写死了.py
docs/                     Original note, source mapping, validation
```

## Reproduction status

Use an appropriate OpenMV board, MicroPython firmware, camera configuration, wiring, and serial-connected device. Some scripts import an external `PID` module that is not included. Desktop Python cannot supply the `sensor`, `image`, or `pyb` hardware APIs.

Source bytes are preserved while filenames are made easier to navigate. No hardware run, contest result, award, or individual contribution claim was added. See [original note](docs/original-notes.zh-CN.md), [mapping](docs/catalog.md), and [validation](docs/validation.md).
