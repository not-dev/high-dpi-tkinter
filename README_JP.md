[英語](./README.md) / 日本語

<!-- ![](./res/) -->

# Sharp-Tkinter-Window-High-DPI

TkinterがWindows10の高DPIディスプレイでぼやける問題の対処

## インストール

pipでインストール

```sh
pip install hdpitkinter
```

## 使用方法

```python
from hdpitkinter import HdpiTk

root = HdpiTk()
root.mainloop()
```

## ライセンス

MIT License

## Citation

<https://stackoverflow.com/questions/41315873/attempting-to-resolve-blurred-tkinter-text-scaling-on-windows-10-high-dpi-disp>
