# Modal

## Dynamic Classes
```
body: 			cd-hide-overflow
cd-modal-wrapper: 	cd-show, cd-hide
```


## Structure
```
<div class="cd-modal-wrapper">
	<div class="cd-modal">
		content
	</div>
</div>
```


## Open Modal
- Remove class `cd-hide` next to wrapper class `cd-modal-wrapper`.
- Add class `cd-show` next to wrapper class `cd-modal-wrapper`.
- To hide scroll, add class `cd-hide-overflow` to the body.


## Close Modal
- Remove class `cd-show` next to wrapper class `cd-modal-wrapper`.
- Add class `cd-hide` next to wrapper class `cd-modal-wrapper`.
- To show scroll, remove class `cd-hide-overflow` from the body.
