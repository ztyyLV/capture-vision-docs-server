---
layout: default-layout
title: class CContoursUnit - Dynamsoft Core Module C++ Edition API Reference
description: This page shows the C++ edition of the class CContoursUnit in Dynamsoft Core Module.
keywords: contours, c++
needAutoGenerateSidebar: true
---

# CContoursUnit

The CContoursUnit class represents a unit that contains contours as intermediate results. It is derived from the CIntermediateResultUnit class.

## Definition

*Namespace:* dynamsoft::intermediate_results

*Assembly:* DynamsoftCore

```cpp
class CContoursUnit : public CIntermediateResultUnit
```

## Methods Summary

| Method                    | Description |
|---------------------------|---------------------------------------------|
| [`GetContours`](#getcontours) | Gets the contour at the specified index.  |

### GetContours

Gets the contour at the specified index.

```cpp
virtual int GetContours(int* count, const CContour** contours, const CVector4** hierarchies) const;
```

**Parameters**

`[out] count` The count of contours in the unit.

`[out] contours` The contours of the unit.

`[out] hierarchies` The hierarchies of the contours in the unit.

**Return value**

Returns 0 if successful, or an error code if the contour could not be retrieved.
