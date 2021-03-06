# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="0.0.15"></a>
## [0.0.15](https://github.com/2muchcoffeecom/ng2-restangular/compare/v0.0.14...v0.0.15) (2016-11-08)



<a name="0.0.14"></a>
## [0.0.14](https://github.com/2muchcoffeecom/ng2-restangular/compare/v0.0.12...v0.0.14) (2016-11-08)



<a name="0.0.12"></a>
## [0.0.12](https://github.com/2muchcoffeecom/ng2-restangular/compare/v0.0.11...v0.0.12) (2016-11-08)



<a name="0.0.11"></a>
## [0.0.11](https://github.com/2muchcoffeecom/ng2-restangular/compare/v0.0.9...v0.0.11) (2016-11-08)



<a name="0.0.9"></a>
## [0.0.9](https://github.com/2muchcoffeecom/ng2-restangular/compare/v0.0.8...v0.0.9) (2016-11-08)



<a name="0.0.8"></a>
## [0.0.8](https://github.com/2muchcoffeecom/ng2-restangular/compare/v0.0.7...v0.0.8) (2016-11-08)



<a name="0.0.7"></a>
## 0.0.7 (2016-11-08)



<a name="0.5.2"></a>
## [0.5.2](https://github.com/mattlewis92/angular-resizable-element/compare/v0.5.1...v0.5.2) (2016-11-05)


### Bug Fixes

* **aot:** aot compatibility ([9236e02](https://github.com/mattlewis92/angular-resizable-element/commit/9236e02))



<a name="0.5.1"></a>
## [0.5.1](https://github.com/mattlewis92/angular-resizable-element/compare/v0.5.0...v0.5.1) (2016-11-03)


### Bug Fixes

* dont change the cursor when resizing an element ([697c52c](https://github.com/mattlewis92/angular-resizable-element/commit/697c52c)), closes [#24](https://github.com/mattlewis92/angular-resizable-element/issues/24)



<a name="0.5.0"></a>
# [0.5.0](https://github.com/mattlewis92/angular-resizable-element/compare/v0.4.1...v0.5.0) (2016-10-29)


### Bug Fixes

* fix resizing via a drag handle ([5f7f468](https://github.com/mattlewis92/angular-resizable-element/commit/5f7f468))
* prevent text from being selected when resizing an element ([5571069](https://github.com/mattlewis92/angular-resizable-element/commit/5571069)), closes [#22](https://github.com/mattlewis92/angular-resizable-element/issues/22)


### Features

* rename the library from angular2-resizable to angular-resizable-element ([927235e](https://github.com/mattlewis92/angular-resizable-element/commit/927235e)), closes [#21](https://github.com/mattlewis92/angular-resizable-element/issues/21)
* rename the resize output to resizing ([9597986](https://github.com/mattlewis92/angular-resizable-element/commit/9597986)), closes [#20](https://github.com/mattlewis92/angular-resizable-element/issues/20)


### BREAKING CHANGES

* The library has been renamed to `angular-resizable-element`.

The UMD entry point has changed to
```
node_modules/angular-resizable-element/dist/umd/angular-resizable-element.js
```
* Before
```
(resize)="onResize($event)"
```

After:
```
(resizing)="onResizing($event)"
```



<a name="0.4.1"></a>
## [0.4.1](https://github.com/mattlewis92/angular-resizable-element/compare/v0.4.0...v0.4.1) (2016-09-28)


### Bug Fixes

* **typings:** dont include reference to core-js ([68dc84f](https://github.com/mattlewis92/angular-resizable-element/commit/68dc84f))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/mattlewis92/angular-resizable-element/compare/v0.3.3...v0.4.0) (2016-09-25)


### Features

* **build:** support offline template compilation ([f3fe12a](https://github.com/mattlewis92/angular-resizable-element/commit/f3fe12a))


### BREAKING CHANGES

* build: For System.js users the path to the UMD files has changed:

Before:
```
node_modules/angular2-resizable/angular2-resizable.js
```

After:
```
node_modules/angular2-resizable/dist/umd/angular2-resizable.js
```



<a name="0.3.3"></a>
## [0.3.3](https://github.com/mattlewis92/angular-resizable-element/compare/v0.3.2...v0.3.3) (2016-09-13)


### Bug Fixes

* **peerDependencies:** allow any versions of angular post RC5 ([cbe088f](https://github.com/mattlewis92/angular-resizable-element/commit/cbe088f))



<a name="0.3.2"></a>
## [0.3.2](https://github.com/mattlewis92/angular-resizable-element/compare/v0.3.1...v0.3.2) (2016-09-03)


### Features

* **angular:** support RC6 ([d5b18cc](https://github.com/mattlewis92/angular-resizable-element/commit/d5b18cc))



<a name="0.3.1"></a>
## [0.3.1](https://github.com/mattlewis92/angular-resizable-element/compare/v0.3.0...v0.3.1) (2016-08-25)


### Bug Fixes

* **rxjs:** use correct rxjs operator imports in dist ([858b3f8](https://github.com/mattlewis92/angular-resizable-element/commit/858b3f8)), closes [#16](https://github.com/mattlewis92/angular-resizable-element/issues/16)



<a name="0.3.0"></a>
# [0.3.0](https://github.com/mattlewis92/angular-resizable-element/compare/v0.2.1...v0.3.0) (2016-08-12)


### Features

* **events:** rename all outputs to drop the on prefix ([9c76aac](https://github.com/mattlewis92/angular-resizable-element/commit/9c76aac))
* directive selectors are now camel case instead of dash case ([ffad2ca](https://github.com/mattlewis92/angular-resizable-element/commit/ffad2ca))
* upgrade to angular RC5 ([9557c0a](https://github.com/mattlewis92/angular-resizable-element/commit/9557c0a))


### BREAKING CHANGES

* `mwl-resizable` is now `mwlResizable` and `mwl-resize-handle` is now `mwlResizeHandle`
* Angular RC5 is now required

The Resizable and ResizeHandle directives are now no longer exported. Instead you must use the ResizableModule. See the readme or the demo app for an example of how to do this.
* events: The `onResizeStart` output has been renamed to `resizeStart`

The `onResize` output has been renamed to `resize`

The `onResizeEnd` output has been renamed to `resizeEnd`



<a name="0.2.1"></a>
## [0.2.1](https://github.com/mattlewis92/angular-resizable-element/compare/v0.2.0...v0.2.1) (2016-07-15)


### Bug Fixes

* **demo:** fix broken demo ([0a5bf11](https://github.com/mattlewis92/angular-resizable-element/commit/0a5bf11))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/mattlewis92/angular-resizable-element/compare/v0.1.0...v0.2.0) (2016-07-15)


### Bug Fixes

* create a clone of the ghost element instead of applying styling to the host ([fa73345](https://github.com/mattlewis92/angular-resizable-element/commit/fa73345)), closes [#15](https://github.com/mattlewis92/angular-resizable-element/issues/15)
* only resize when the cursor is within the bounding rectangle ([dedc3bb](https://github.com/mattlewis92/angular-resizable-element/commit/dedc3bb))


### BREAKING CHANGES

* `enableResizeStyling` has been renamed to `enableGhostResize`



<a name="0.1.0"></a>
# [0.1.0](https://github.com/mattlewis92/angular-resizable-element/compare/v0.0.3...v0.1.0) (2016-06-26)


### Bug Fixes

* **mousedrag:** cancel the previous mousedrag observable when starting a new drag ([149c1a4](https://github.com/mattlewis92/angular-resizable-element/commit/149c1a4)), closes [#9](https://github.com/mattlewis92/angular-resizable-element/issues/9)
* **onResizeEnd:** call with co-ordinates of last valid resize rather than where the mouse up event w ([eb314fd](https://github.com/mattlewis92/angular-resizable-element/commit/eb314fd))
* **onResizeStart:** ensure the starting rectangle is a POJO rather than a bounding rectangle ([81fe0b4](https://github.com/mattlewis92/angular-resizable-element/commit/81fe0b4))
* cancel mousedrag event when either a mouseup or mousedown event fires ([c76be59](https://github.com/mattlewis92/angular-resizable-element/commit/c76be59))
* disable dragging effects on resizable elements on webkit browsers ([59078e2](https://github.com/mattlewis92/angular-resizable-element/commit/59078e2))
* renamed directive selector from mwl-resizeable to mwl-resizable ([c60b3f5](https://github.com/mattlewis92/angular-resizable-element/commit/c60b3f5))


### Features

* **disableResize:** support completely disabling resizing an element ([9f9c54a](https://github.com/mattlewis92/angular-resizable-element/commit/9f9c54a)), closes [#13](https://github.com/mattlewis92/angular-resizable-element/issues/13)
* expose the amount each edge was resized on resize events ([d664038](https://github.com/mattlewis92/angular-resizable-element/commit/d664038)), closes [#11](https://github.com/mattlewis92/angular-resizable-element/issues/11)
* **enableResizeStyling:** make temporary resizing of the element opt-in by default so users can con ([4c59b05](https://github.com/mattlewis92/angular-resizable-element/commit/4c59b05)), closes [#5](https://github.com/mattlewis92/angular-resizable-element/issues/5)
* **resizeEdges:** allow the resize edges to be customised ([60c2e08](https://github.com/mattlewis92/angular-resizable-element/commit/60c2e08)), closes [#8](https://github.com/mattlewis92/angular-resizable-element/issues/8)
* **resizeHandles:** add support for nesting resize handles inside the element ([1af705a](https://github.com/mattlewis92/angular-resizable-element/commit/1af705a)), closes [#10](https://github.com/mattlewis92/angular-resizable-element/issues/10)
* **resizeSnapGrid:** allow resizing to fit to a snap grid ([74424ba](https://github.com/mattlewis92/angular-resizable-element/commit/74424ba)), closes [#3](https://github.com/mattlewis92/angular-resizable-element/issues/3)
* **validate:** provide a way for resize events to be validated ([4da938d](https://github.com/mattlewis92/angular-resizable-element/commit/4da938d)), closes [#12](https://github.com/mattlewis92/angular-resizable-element/issues/12)


### BREAKING CHANGES

* enableResizeStyling: the element will no longer have its styles changed by default when dragging and
resizing. You can now re-enable it by setting `[enableResizeStyling]="true"` on the element.
* the `$event.edges` object values now contain numbers instead of booleans
* - rename the directive from mwl-resizeable to mwl-resizable
* resizeEdges: by default the element is no longer resizable.

You must specify `[resizeEdges]={top: true, bottom: true, left: true, right: true}` to get the old behaviour back



<a name="0.0.3"></a>
## [0.0.3](https://github.com/mattlewis92/angular-resizable-element/compare/v0.0.2...v0.0.3) (2016-06-13)


### Bug Fixes

* import missing rxjs operators ([300ac10](https://github.com/mattlewis92/angular-resizable-element/commit/300ac10))



<a name="0.0.2"></a>
## [0.0.2](https://github.com/mattlewis92/angular-resizable-element/compare/v0.0.1...v0.0.2) (2016-06-13)


### Bug Fixes

* **types:** export Edges and BoundingRectangle types ([fe49114](https://github.com/mattlewis92/angular-resizable-element/commit/fe49114))
* dont bundle rxjs with the library ([7b1280e](https://github.com/mattlewis92/angular-resizable-element/commit/7b1280e))



<a name="0.0.1"></a>
## 0.0.1 (2016-06-13)


### Bug Fixes

* allow the element to be resized multiple times ([bf497d2](https://github.com/mattlewis92/angular-resizable-element/commit/bf497d2))
* **drag:** disable user dragging ([053fb0e](https://github.com/mattlewis92/angular-resizable-element/commit/053fb0e))
* reset element styles on mousedown if there was a previous uncancelled resize ([a8e5cd3](https://github.com/mattlewis92/angular-resizable-element/commit/a8e5cd3))
* **outputs:** make outputs sync to prevent ui flicker ([032ea5a](https://github.com/mattlewis92/angular-resizable-element/commit/032ea5a))
* **typescript:** add missing types ([e722a86](https://github.com/mattlewis92/angular-resizable-element/commit/e722a86))


### Features

* improve transforms, add resize events ([0959a12](https://github.com/mattlewis92/angular-resizable-element/commit/0959a12))
* initial WIP resizable implementation ([22af52f](https://github.com/mattlewis92/angular-resizable-element/commit/22af52f))
* show the cursor when mousing over the edge of the element ([f440c87](https://github.com/mattlewis92/angular-resizable-element/commit/f440c87))
* support resizing from corners ([bac87e3](https://github.com/mattlewis92/angular-resizable-element/commit/bac87e3)), closes [#4](https://github.com/mattlewis92/angular-resizable-element/issues/4)
