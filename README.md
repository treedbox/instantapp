# instantapp for Treedbox
Basic InstantApp in HTML5 is a Progressive Web App - PWA that works offline.

By: [Jonimar Marques Policarpo](http://treedbox.com) at [Treedbox](http://treedbox.com)

## Online Demo:
https://treedbox.github.io/instantapp/

## How it Works?
1 - By Mobile, access: https://treedbox.github.io/instantapp/ on [Google Chrome](https://play.google.com/store/apps/details?id=com.android.chrome) > Options > **Add to Home Screen** > Add;

2 - Turn off Wi-Fi;

3 - Click on the App on your Home Screen;

Service Workers allow you to create Web Apps to work, like instantApp, without need installation.

Also allow Work offline by caching:
```
//cache files
var cacheFiles = [
	'./',
	'./index.html',
	'./css/style.css',
	'./app.js',
	'./sw.js',
	'./images/logo.svg',
	'./images/treedbox-ani-black.svg',
	'./images/treedbox-ani-white.svg',
	'./images/icons/36.png',
	'./images/icons/48.png',
  ...
];
```
## Documentation
https://developers.google.com/web/fundamentals/getting-started/primers/service-workers

https://serviceworke.rs/


## Contact
Twitter: [@treedbox](http://twitter.com/treedbox)

E-mail: [treedbox@gmail.com](mailto:treedbox@gmail.com)

## License
[MIT](LICENSE.md) © [TreedBox](https://github.com/treedbox)
