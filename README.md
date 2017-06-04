ng-wheel
========

AngularJS `ng-wheel` directive. Used to listen for `mousewheel` events on an element.

### Setup & Usage

#### 1. Load it into your Angular module

```javascript
angular.module("app", [
  // (...)
  "ngWheel"
]);
```

#### 2. Add directive to an element

```html
  <div ng-wheel="mouseWheelHandler($event)"></div>
```
