<!-- markdownlint-disable -->

<a href="https://github.com/khulnasoft/docknet/blob/main/backend/src/docknet/utils/readyapi_utils.py#L0"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

# <kbd>module</kbd> `docknet.utils.readyapi_utils`
Collection of utilities for ReadyAPI apps. 


---

<a href="https://github.com/khulnasoft/docknet/blob/main/backend/src/docknet/utils/readyapi_utils.py#L14"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `schedule_call`

```python
schedule_call(func: Callable, interval: timedelta) → None
```

Schedule a function to be called in regular intervals. 



**Args:**
 
 - <b>`func`</b> (Callable):  The function to be called regularly 
 - <b>`interval`</b> (timedelta):  The amount of time to wait between function calls 


---

<a href="https://github.com/khulnasoft/docknet/blob/main/backend/src/docknet/utils/readyapi_utils.py#L33"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `as_form`

```python
as_form(cls: Type[BaseModel]) → Any
```

Adds an as_form class method to decorated models. 

The as_form class method can be used with ReadyAPI endpoints 


---

<a href="https://github.com/khulnasoft/docknet/blob/main/backend/src/docknet/utils/readyapi_utils.py#L57"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `patch_readyapi`

```python
patch_readyapi(app: ReadyAPI) → None
```

Patch function to allow relative url resolution. 

This patch is required to make readyapi fully functional with a relative url path. This code snippet can be copy-pasted to any Readyapi application. 


---

<a href="https://github.com/khulnasoft/docknet/blob/main/backend/src/docknet/utils/readyapi_utils.py#L121"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `add_timing_info`

```python
add_timing_info(app: ReadyAPI) → None
```








---

_This file was automatically generated via [docsai](https://github.com/khulnasoft/docsai)._