# Toaster.js
A mini toaster library made for browser javascript

## Importing

To use the toaster.js browser library you just need to import the following link to your web application by doing
```HTML
<script src="https://cdn.jsdelivr.net/gh/goldenboys2011/toaster.js@main/min-toaster.js"></script>
```
## Usage

to use a toaster from toaster.js you just call it by doing 
```JS
toaster.type(parameters)
```

### Type
Type is (well obviously) the type of the toster. 
The type can be one of the following:

Type|
-----|
succes|
error|
info|
warn|

e.x
```JS
toaster.success()
```

### Parameters
 The allowed parameters are the following:
 
 Parameter | Type | Description
 ----------|-------|------------|
 title|``string``|The title of the toaster apearing on the top of the toaster
 body|``string``|The inner text of the toaster
 opts|``Obj``|Toaster [Option](#options)

 e.x
 ```JS
toaster.success("Action Succes", "Your action was succesfull", {duration: 5000})
```

### Options

 Option| Type | Description | Default|
 ------|-------|-----------|---------|
 duration|``int``/``ms``|The duration of the toaster before it disapears| 3000
 
