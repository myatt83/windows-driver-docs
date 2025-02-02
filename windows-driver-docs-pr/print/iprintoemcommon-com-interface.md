---
title: IPrintOemCommon COM Interface
description: IPrintOemCommon COM Interface
ms.date: 01/27/2023
---

# IPrintOemCommon COM Interface

[!include[Print Support Apps](../includes/print-support-apps.md)]

The `IPrintOemCommon` COM interface enables a plug-in to specify or get device information. This interface provides functionality that is common between the user interface and rendering plug-ins.

The following table lists and describes all the methods that the `IPrintOemCommon` interface defines.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Method</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>IPrintOemCommon::DevMode</strong></p></td>
<td><p>Performs operations on private DEVMODEW members.</p></td>
</tr>
<tr class="even">
<td><p><strong>IPrintOemCommon::GetInfo</strong></p></td>
<td><p>Returns a plug-in's identification information.</p></td>
</tr>
</tbody>
</table>

For information about how these methods are implemented for UI plug-ins, see [IPrintOemUI COM Interface](iprintoemui-com-interface.md).
