# nerd-fonts simple patcher

```sh
for i in build/*.ttf
do
  python font-patcher --fontawesome --octicons --pomicons --powerline --powerlineextra --outputdir build2 --quiet $i
done
```
