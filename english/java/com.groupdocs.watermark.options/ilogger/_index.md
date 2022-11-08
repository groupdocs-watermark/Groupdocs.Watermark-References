---
title: ILogger
second_title: GroupDocs.Watermark for Java API Reference
description: Defines the interface of a logger that is used for logging events and errors during watermarking.
type: docs
weight: 79
url: /java/com.groupdocs.watermark.options/ilogger/
---```
public interface ILogger
```

Defines the interface of a logger that is used for logging events and errors during watermarking.
## Methods

| Method | Description |
| --- | --- |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Logs an error that occurred during watermarking. |
| [trace(String message)](#trace-java.lang.String-) | Logs an event occurred during watermarking. |
| [warning(String message)](#warning-java.lang.String-) | Logs a warning that occurred during watermarking. |
### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public abstract void error(String message, Exception exception)
```


Logs an error that occurred during watermarking.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message. |
| exception | java.lang.Exception | The instance of occured exception. |

### trace(String message) {#trace-java.lang.String-}
```
public abstract void trace(String message)
```


Logs an event occurred during watermarking.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The event message. |

### warning(String message) {#warning-java.lang.String-}
```
public abstract void warning(String message)
```


Logs a warning that occurred during watermarking.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The warning message. |

