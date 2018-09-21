# file-backup
Makes rotating [file].0, [file].1 ... backups in the same directory (node.js)
<a name="file_backup"></a>

## file_backup(file, levels, [callback]) ⇒ <code>Promise</code>
Makes rotating [file].0, [file].1 ... backups in the same directory

**Kind**: global function  
**Returns**: <code>Promise</code> - Resolves on success, rejects on some fs-level error  

| Param | Type | Description |
| --- | --- | --- |
| file | <code>string</code> | The path to the file to back up |
| levels | <code>number</code> | The number of backups to keep |
| [callback] | <code>function</code> | Standard error-first, if that's how you roll |

