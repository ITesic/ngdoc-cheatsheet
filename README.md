# ngdoc Cheatsheet
Cheatsheet for AngularJS documentation (ngdoc)

## ngdoc specific tags

* `@ngdoc` 	specifies the type of thing being documented. See below for more detail.
* `@scope` 	specifies that the documented directive will create a new scope
* `@priority` 	specifies the documented directive's priority
* `@animations` 	specifies the animations that the documented directive supports
* `@methodOf type` 	links a method to the object/service where it is defined
* `@propertyOf type `	links a property to the object/service where it is defined
* `@eventOf type` 	links a method to the object/service where it is defined
* `@eventType emit | broadcast`	specifies whether the event is emitted or broadcast

## Possible values for @ngdoc tag

 * `@ngdoc directive`
 * `@ngdoc event`
 * `@ngdoc filter`
 * `@ngdoc function`
 * `@ngdoc inputType`
 * `@ngdoc interface`
 * `@ngdoc method`
 * `@ngdoc object`
 * `@ngdoc overview`
 * `@ngdoc property`
 * `@ngdoc service`
 
## Links

* {@link ng.directive:form `form`}
* {@link ng.directive:form form}
* {@link ng.directive:form.FormController FormController}
* {@link ng.directive:input input element}
* {@link ng.directive:input.checkbox checkbox}
* {@link ng.directive:ngAnimate ngAnimate}
* {@link ng.directive:ngAnimate#Description common ng directives}
* {@link ng.directive:ngApp ngApp}
* {@link ng.directive:ngIf#animations ngIf}
* {@link ng.directive:script inlined templates}
