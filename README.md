# Photo Gallery app 
I followed the tutorial from Ionic Framework website for Angular: https://ionicframework.com/docs/angular/your-first-app

## My notes on the setup needed:
* npm install -g @ionic/cli native-run cordova-res
* ionic start photo-gallery tabs --type=angular --capacitor
* npm install @ionic/pwa-elements

##
* ionic serve

## To deploy on android:
(install android studio, setup SDK, environment variables (see Ionic website))
* ionic capacitor add android
* // edit capacitor.config.json > appID
* ionic build
* ionic cap copy
* ionic cap sync

## Using Live Reload:
ionic cap run android -l --external
* run app on android studio


##
* Node: v14.15.3
* npm: 6.14.10
* @ionic/cli: 6.12.3
* @ionic/pwa-elements: 6.12.3
* cordova-res: 6.14.10
* native-run: 6.14.10
