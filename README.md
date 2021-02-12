# bottom-bash

A bottom encoder and decoder implementation in pure Bash.

## Usage

```sh
# Encode and decode in one pipeline.
echo "Hello, 世界!" | ./bottom | ./bottom d
# Encode to file.
echo "Hello, world!" | ./bottom > /tmp/bottom_out
# Decode the file.
./bottom d < /tmp/bottom_out
```
