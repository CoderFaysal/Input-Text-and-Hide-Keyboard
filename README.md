# Input Text and Hide Keyboard


## Button Click to Hide Keyboard


```
InputMethodManager manager = (InputMethodManager) getSystemService(INPUT_METHOD_SERVICE);
manager.hideSoftInputFromWindow(view.getWindowToken(), 0);
```
