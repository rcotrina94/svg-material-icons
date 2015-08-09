# svg-material-icons
SVG Material Icons for Material Angular

#### Example code

```javascript
var app = angular.module('MyModule', ['ngMaterial']);
app.config(function($mdIconProvider /*, ... */){
	$mdIconProvider
		.iconSet("action", "assets/libs/svg-material-icons/action.svg", 48)
		.iconSet("alert", "assets/libs/svg-material-icons/alert.svg", 48)
		.iconSet("av", "assets/libs/svg-material-icons/av.svg", 48)
		.iconSet("communication", "assets/libs/svg-material-icons/communication.svg", 48)
		.iconSet("content", "assets/libs/svg-material-icons/content.svg", 48)
		.iconSet("device", "assets/libs/svg-material-icons/device.svg", 48)
		.iconSet("editor", "assets/libs/svg-material-icons/editor.svg", 48)
		.iconSet("file", "assets/libs/svg-material-icons/file.svg", 48)
		.iconSet("hardware", "assets/libs/svg-material-icons/hardware.svg", 48)
		.iconSet("image", "assets/libs/svg-material-icons/image.svg", 48)
		.iconSet("maps", "assets/libs/svg-material-icons/maps.svg", 48)
		.iconSet("navigation", "assets/libs/svg-material-icons/navigation.svg", 48)
		.iconSet("notification", "assets/libs/svg-material-icons/notification.svg", 48)
		.iconSet("social", "assets/libs/svg-material-icons/social.svg", 48)
		.iconSet("toggle", "assets/libs/svg-material-icons/toggle.svg", 48);
	// ...
});
```
