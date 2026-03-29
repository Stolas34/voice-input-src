```bash
claude \
  --dangerously-skip-permissions \
  --output-format=stream-json \
  --verbose \
  -p "请帮忙实现一个语音输入法，按住 Fn 键录制音频，松开后把转录的文字注入输入框中，如果能流式转录那就更好了"
```
