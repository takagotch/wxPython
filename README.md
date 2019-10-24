### wxPython
---
https://github.com/wxWidgets/wxPython

https://wxpython.org/

```h
// include/wx/wxPython/pydrawxxx.h

#indef __pydrawxxx_h__
#define __pydrawxxx_h__

void wxPyDrawList_SetAPIPtr():

typedef bool (*wxPyDrawListOp_t)(wxDC& dc, PyObject* coords);
PyObject* wxPyDrawXXXList(wxDC& dc, wxPyDrawListOp_t doDraw,
    PyObject* pyCoords, PyObject* pyPens, PyObject* pyBrushes);
bool wxPyDrawXXXPoint(wxDC& dc, PyObject* coords);

PyObject* wxPyDrawTextList(wxDC& dc, PyObject* textList, PyObject* pyPoints,
  PyObject* foregroundList, PyObject* backgroundList);

#endif
```

```
```

```
```


