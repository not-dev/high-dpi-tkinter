<!-- ![](./res/) -->

# High-DPI-Tkinter

Sharpen blurry Tkinter scaling on Windows 10 high DPI displays

## Installation

Install using pip

```sh
pip install hdpitkinter
```

## Usage

Replace tkinter.Tk() to hdpitkinter.HdpiTk()

```python
# from tkinter import Tk
from hdpitkinter import HdpiTk

# root = Tk()
root = HdpiTk()
# After that use like Tk instance
root.mainloop()
```

## License

MIT License

## Citation

Packaged by citing <https://stackoverflow.com/questions/41315873/attempting-to-resolve-blurred-tkinter-text-scaling-on-windows-10-high-dpi-disp>
