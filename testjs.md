### API

A mock program module, using the @module tag sets the overall 
title at the initial level setting.

* **author** `muji`
* **version** `1.1.0`
* **since** `1.0`
* **license** `MIT`

#### See Also

* [mkapi](https://github.com/mkdoc/mkapi "mkapi")
* [commonmark](https://github.com/jgm/commonmark.js "commonmark")

#### Component

Mock class, you can add an extended description of the class behaviour here.

##### Component : EventEmitter : Object

```javascript
new Component(opts)
```

An abstract component.

* **author** `muji`
* **version** `1.1.0`
* **since** `1.0`

* `opts` Component options.

###### Options

* `enabled` Whether the component is initially enabled.

##### .foo

```javascript
Component.prototype.foo([opts], cb)
```

Do foo thing with bar.

* **author** `muji`
* **version** `1.1.0`
* **since** `1.0`

* `opts` Object An options arguments.
* `cb` Function Callback function.

###### Options

* `noop` Boolean Dry run.

###### Throws

* `Error` JSON parse error.
* `Error` File create error.

##### create

```javascript
create()
```

Create a new component.

##### BAZ

```javascript
BAZ = baz;
```

Sets the BAZ variable.

* **author** `muji`
* **version** `1.1.0`
* **since** `1.0`

##### QUX

```javascript
QUX
```

Sets the QUX variable.

