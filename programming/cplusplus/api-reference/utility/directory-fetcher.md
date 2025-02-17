---
layout: default-layout
title: class CDirectoryFetcher - Dynamsoft Utility Module C++ Edition API Reference
description: This page shows the C++ edition of the class CDirectoryFetcher in Dynamsoft Utility Module.
keywords: directory fetcher, c++
needAutoGenerateSidebar: true
---

# CDirectoryFetcher

The CDirectoryFetcher class is a utility class that retrieves a list of files from a specified directory based on certain criteria. It inherits from the CProactiveImageSourceAdapter class.

## Definition

*Namespace:* dynamsoft::utility

*Assembly:* DynamsoftUtility

```cpp
class CDirectoryFetcher : public CProactiveImageSourceAdapter
```

## Methods Summary

| Method | Description |
|--------|-------------|
| [`SetDirectory`](#setdirectory) | Sets the directory path and filter for the file search. |
| [`SetPDFReadingParameter`](#setpdfreadingparameter) | Sets the parameters for reading PDF files. |

### SetDirectory

Sets the directory path and filter for the file search.

```cpp
int SetDirectory(const char *path, const char *filter, bool recursive)
```

**Parameters**

`[in] path` The path of the directory to search.

`[in] filter` A string that specifies file extensions. For example: "*.BMP;*.JPG;*.GIF", or "*.*", etc.

`[in] recursive` Specifies whether to load files recursively.

**Return value**

Returns an integer value that represents the success or failure of the operation.

### SetPDFReadingParameter

Sets the parameters for reading PDF files.

```cpp
int SetPDFReadingParameter(const CPDFReadingParameter& para)
```

**Parameters**

`[in] para` The parameter object for reading PDF files.

**Return value**

Returns an integer value that represents the success or failure of the operation.
