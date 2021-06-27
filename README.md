# ReplaceFileExtension for your desired

```
ls -Filter *.zip | ForEach-Object {$_ | Rename-Item -NewName $_.Name.Replace('zip', 'cbz')}
```
