# Hashes for streets & zones in GTA V

This is useful for renaming street or area names.

## Snippets for FiveM (Lua):

**Renaming a street:**
```lua
-- 0x7999837 = Route 68; rename to route 66
AddTextEntryByHash(0x7999837, "Route 66")
```

**Renaming a zone (area):**
```lua
-- AIRP = Los Santos International Airport; rename to LAX Airport
AddTextEntryByHash(`AIRP`, "LAX Airport")
```
