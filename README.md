# BIM 360 Example

Login to app.matatika.com and copy the 'AutoDesk Forge BIM 360' pipeline environment to a local `.env`

```
meltano install

meltano run --no-state-update tap-autodesk-bim-360 target-mssql
```
