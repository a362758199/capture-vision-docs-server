---
layout: default-layout
title: class CTextureRemovedBinaryImageUnit - Dynamsoft Core Module C++ Edition API Reference
description: This page shows the C++ edition of the class CTextureRemovedBinaryImageUnit in Dynamsoft Core Module.
keywords: texture removed binary image, c++
needAutoGenerateSidebar: true
---

# CTextureRemovedBinaryImageUnit

The CTextureRemovedBinaryImageUnit class represents an intermediate result unit that stores texture-removed binary image data.

## Definition

*Namespace:* dynamsoft::intermediate_results

*Assembly:* DynamsoftCore

```cpp
class CTextureRemovedBinaryImageUnit : public CIntermediateResultUnit 
```

## Methods Summary

| Method               | Description |
|----------------------|-------------|
| [`GetImageData`](#getimagedata) | Gets the image data of the texture-removed binary image. |

### GetImageData

Gets the image data of the texture-removed binary image.

```cpp
virtual const CImageData* GetImageData() const
```

**Return value**

Returns a const pointer to CImageData object that represents the texture-removed binary image. You don't need to release the memory pointed to by the returned pointer.
