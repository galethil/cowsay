# cowsay

Place this into your .bash_profile or .bashrc file.

Usage e.g. `cowsay Heloooo` or using pipe `ls | cowsay`

```bash
cowsay() {
  if [[ "$1" == "" ]]; then
    cat
  else
    echo $@
  fi
  echo "        \   ^__^"
  echo "         \  (oo)\_______"
  echo "            (__)\       )\/\\"
  echo "                ||----w |"
  echo "                ||     ||"
}
```
