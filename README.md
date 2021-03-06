Terminal script for fast creation of files and directories. Mimics the operation of **AdvancedNewFile** (Vim plugin)

## Use

```bash
ad [path file or folder]
```

## Example

```bash
ad airport/plane/
```

```
airport/
├── plane/
```
---

```bash
ad airport/plane/captain.txt
```

```
airport/
├── plane/
│   ├── captain.txt
```


## Install

```bash
ADVANCE=/usr/local/bin/ad && curl -o $ADVANCE https://raw.githubusercontent.com/tanrax/terminal-AdvancedNewFile/master/bin/advance && chmod +x $ADVANCE && unset ADVANCE
```

## Update

```bash
ADVANCE=/usr/local/bin/ad && rm $ADVANCE && curl -o $ADVANCE https://raw.githubusercontent.com/tanrax/terminal-AdvancedNewFile/master/bin/advance && chmod +x $ADVANCE && unset ADVANCE
```
