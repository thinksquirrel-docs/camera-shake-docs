Camera Shake {#camerashake}
===

## Overview
The Camera Shake component is the main component of Camera Shake. It can shake
multiple cameras, based on either their transform or camera matrix.

@sa [CameraShake](@ref Thinksquirrel.CShake.CameraShake)

![1]

## Properties

- **Cameras** - The cameras to shake. This will default to a camera component on the same game object. If none is present it will try to find the main camera.
- **Shake Type** - The type of shake to perform (camera matrix or local position). Defaults to shaking the camera matrix.
- **Number Of Shakes** - The maximum number of shakes to perform.
- **Shake Amount** - The amount to shake in each direction.
- **Rotation Amount** - The amount to rotate in each axis.
- **Distance** - The initial distance for the first shake.
- **Speed** - The speed multiplier for the shake.
- **Decay** - The decay speed (between 0 and 1). Higher values will stop shaking sooner.
- **Ui Shake Modifier** - The modifier applied to speed in order to shake the UI.
- **Multiply By Time Scale** - If true, multiplies the shake speed by the time scale.

<br>

---
<table width=80% align=center><tr>
<td width=33% align=left><< @ref components</td>
<td width=34% align=center>@ref components</td>
<td width=33% align=right><a href=namespaces.html><b>API Documentation</b></a> >></td>
</tr></table>

[1]:@ref camerashake.png
