# fair-timber-tool

Coffee → code → repeat. Mostly PostgreSQL these days.

日常脚本的集中地

## 用法

```bash
cat data.txt | ./run.sh
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 备注

就是给自己省点事，没做太多抽象。

## 安装

```bash
git clone https://github.com/USER/fair-timber-tool.git
cd fair-timber-tool
chmod +x run.sh
```

## License

MIT
