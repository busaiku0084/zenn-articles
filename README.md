# zenn-articles

## ファイル名の生成方法
```bash
echo "$(date +%Y%m%d)-$(LC_CTYPE=C tr -dc 'a-z0-9' < /dev/urandom | fold -w 8 | head -n 1)"
```
