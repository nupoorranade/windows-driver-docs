---
title: KSPROPERTY\_CONNECTION\_STARTAT
description: KSPROPERTY\_CONNECTION\_STARTAT is an optional property that is implemented by filters that support starting when a specified event occurs.
keywords: ["KSPROPERTY_CONNECTION_STARTAT Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_CONNECTION_STARTAT
api_location:
- ks.h
api_type:
- HeaderDef
ms.date: 11/28/2017
ms.localizationpriority: medium
---

# KSPROPERTY\_CONNECTION\_STARTAT


KSPROPERTY\_CONNECTION\_STARTAT is an optional property that is implemented by filters that support starting when a specified event occurs.

## <span id="ddk_ksproperty_connection_startat_ks"></span><span id="DDK_KSPROPERTY_CONNECTION_STARTAT_KS"></span>


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
<th>Property Descriptor Type</th>
<th>Property Value Type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>Filter</p></td>
<td><p><a href="/windows-hardware/drivers/stream/ksproperty-structure" data-raw-source="[&lt;strong&gt;KSPROPERTY&lt;/strong&gt;](./ksproperty-structure.md)"><strong>KSPROPERTY</strong></a></p></td>
<td><p><a href="/windows-hardware/drivers/ddi/ks/ns-ks-ksrelativeevent" data-raw-source="[&lt;strong&gt;KSRELATIVEEVENT&lt;/strong&gt;](/windows-hardware/drivers/ddi/ks/ns-ks-ksrelativeevent)"><strong>KSRELATIVEEVENT</strong></a></p></td>
</tr>
</tbody>
</table>

 

## Remarks

This property should only be requested when the pin is in a pause state, to transition the pin into a run state.

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Ks.h (include Ks.h)</td>
</tr>
</tbody>
</table>

## See also


[**KSRELATIVEEVENT**](/windows-hardware/drivers/ddi/ks/ns-ks-ksrelativeevent)

[**KSEVENT\_ITEM**](/windows-hardware/drivers/ddi/ks/ns-ks-ksevent_item)