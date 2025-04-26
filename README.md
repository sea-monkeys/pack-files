# pack-files

```bash
go build
cp pack-files /usr/local/bin
rm pack-files
```


```bash
pack-files -dir=$INPUT_DIR \
-include=$INCLUDE_EXTS \
-exclude=$EXCLUDE_EXTS \
-structure=$STRUCTURE_FILE \
-content=$CONTENT_FILE \
-summary=$SUMMARY_FILE
```


```bash
pack-files -dir=. \
-include="html,ts,md" \
-exclude="" \
-structure=./pack.tree.txt \
-content=./pack.content.txt \
-summary=./pack.summary.txt
```