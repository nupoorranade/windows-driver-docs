---
title: KSPROPERTY\_DVDSUBPIC\_HLI
description: The KSPROPERTY\_DVDSUBPIC\_HLI property specifies the rectangle of the subpicture or screen to change, including the color or contrast.
keywords: ["KSPROPERTY_DVDSUBPIC_HLI Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_DVDSUBPIC_HLI
api_location:
- ksmedia.h
api_type:
- HeaderDef
ms.date: 11/28/2017
ms.localizationpriority: medium
---

# KSPROPERTY\_DVDSUBPIC\_HLI


The KSPROPERTY\_DVDSUBPIC\_HLI property specifies the rectangle of the subpicture or screen to change, including the color or contrast.

## <span id="ddk_ksproperty_dvdsubpic_hli_ks"></span><span id="DDK_KSPROPERTY_DVDSUBPIC_HLI_KS"></span>


### Usage Summary Table

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Get</th>
<th>Set</th>
<th>Target</th>
<th>Property descriptor type</th>
<th>Property value type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>Pin</p></td>
<td><p><a href="/windows-hardware/drivers/stream/ksproperty-structure" data-raw-source="[&lt;strong&gt;KSPROPERTY&lt;/strong&gt;](./ksproperty-structure.md)"><strong>KSPROPERTY</strong></a></p></td>
<td><p><a href="/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-_ksproperty_sphli" data-raw-source="[&lt;strong&gt;KSPROPERTY_SPHLI&lt;/strong&gt;](/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-_ksproperty_sphli)"><strong>KSPROPERTY_SPHLI</strong></a></p></td>
</tr>
</tbody>
</table>

 

The property value (operation data) is a KSPROPERTY\_SPHLI structure that describes the DVD highlight information to change.

## Remarks

The [**KSPROPERTY\_SPHLI**](/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-_ksproperty_sphli) structure describes the currently selected button from the DVD highlight information.

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Ksmedia.h (include Ksmedia.h)</td>
</tr>
</tbody>
</table>

## See also


[**KSPROPERTY\_SPHLI**](/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-_ksproperty_sphli)