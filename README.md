# stark-kettle-cli

Platform engineer · Rust and Tower

留着备查的示例

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

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## License

MIT
