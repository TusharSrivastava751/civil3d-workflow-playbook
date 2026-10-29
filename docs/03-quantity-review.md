# 03 · Review quantities without mixing methods

For a surface comparison, identify the base (typically existing ground), comparison (the intended
proposed level), common boundary and any cut/fill factors. Keep raw geometric volumes separate
from adjusted material quantities. A finished surface and a formation surface are different bases.

Autodesk describes using the Volumes Dashboard to compare surfaces, add bounded areas and create
reports. A grid volume surface samples elevation differences on a grid; changing spacing can change
the approximation. Document method and settings before comparing results.
Sources: [volume dashboard](https://help.autodesk.com/cloudhelp/2022/ENU/Civil3D-UserGuide/files/GUID-F06475D1-BCB8-456A-AB29-E6B731DB32A8.htm),
[grid volume surface](https://help.autodesk.com/cloudhelp/2022/ENU/Civil3D-UserGuide/files/GUID-62EC28FA-E636-4134-9153-4EE3328154A1.htm).

For a cross-section schedule, the portfolio audit uses average-end-area quantities. This is a
different computation from a surface comparison. A difference does not automatically mean either
method is implemented incorrectly. First compare boundary, stations, sampled features, cut/fill
separation, datum and treatment of materials.

| Discrepancy | First investigation |
|---|---|
| All volumes differ by a similar factor | Unit conversion or applied material factors |
| One interval is different | Station spacing, local area entry or omitted section |
| Cut and fill appear reversed | Base/comparison selection or sign convention |
| Only a corner of the site differs | Boundary, missing breakline or sparse triangles |

These are investigation prompts, not automatic diagnoses. Save the original exports and record
the resolution rather than silently replacing the reported total.
