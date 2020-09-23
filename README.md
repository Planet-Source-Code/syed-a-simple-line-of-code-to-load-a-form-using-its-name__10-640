<div align="center">

## A simple line of code to load a form using its name\.


</div>

### Description

This code is helpful if you want to load a form by passing its name as parameter.

rating is expected ;-)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Syed](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/syed.md)
**Level**          |Intermediate
**User Rating**    |4.5 (76 globes from 17 users)
**Compatibility**  |VB\.NET
**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__10-3.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/syed-a-simple-line-of-code-to-load-a-form-using-its-name__10-640/archive/master.zip)





### Source Code

```
Private Sub showForm(ByVal frmName As String)
Dim frm As Form
frm = AppDomain.CurrentDomain.CreateInstanceAndUnwrap(Me.GetType.Assembly.GetName.Name, System.String.Concat(Me.GetType.Assembly.GetName.Name, ".", frmName))
    frm.Show()
End Sub
```

