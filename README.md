<div align="center">

## Oppisite Colour2 \(HEX\)


</div>

### Description

Grab the opposite 6 character HEX color.

This sums up David Weirs Color invert script with just one line of code.

See his original code at http://www.pscode.com/vb/scripts/showcode.asp?txtCodeId=7176&lngWId=4

Be careful when comming close to middle gray scale (808080). opposites are same.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Lewis E\. Moten III](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/lewis-e-moten-iii.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__4-15.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/lewis-e-moten-iii-oppisite-colour2-hex__4-7356/archive/master.zip)





### Source Code

Invert = Right("000000" & Hex(16777215 - CLng("&h" & Color)), 6)

