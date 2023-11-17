<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-1QPWPDVQ5F"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-1QPWPDVQ5F');
</script>
# My Android Auto app isn't working
## Your ultimate guide for Android Auto debuging       						[FR](./repare.txt)

This blog focus mainly the debuging process, for pairing process, please use [google android auto guide](https://support.google.com/androidauto/answer/6348029?hl=en).

I drive everyday, and most of time, I don't need android auto. But from time to time, I do need android auto for navigation.
Unfortunately, android auto is not alway stable. During last year, I've spent a few month debuging and testing why it's not working.
After buying two Pixel Phones and tring a lots of times with different app combinations, I've found that the problem is linked to Google play service.
As Google Play Service  is a service you can not disable, it's not possible to develop another app to make android auto working.

But I've finally found an option to make android auto working, which is made possible  by Auto Companion App [Auto Companion](https://play.google.com/store/apps/details?id=com.ingenika.autocompanion).

After running Auto Companion App, disconnect your phone from car, reconnect it to the car, normally, should solve the problem.

If above step is not working, you can try to restart your head unit and try again.

Sometimes, with big version upgrade from Android auto, this approach is not working, you can try forget the bluetooth device on your car, and pair the phone again.

If this step is not working, uninstall the update of android auto app, repeat the previous procedures again. 
  1.  Clear android auto ***cache*** and ***storage***
  2.  Clear google search app ***cache*** and  ***storage***
  3.  Clear ggoogle play service ***cache*** and ***storage***
  4.  You may need also clear google maps ***cache*** and ***storage***

after these step, start over pairing process with your car head unit

And if you are confortable at disable google play service update. There is an option to make android auto working, without to run auto companion app very often:

Find a version of google play service that is working, disable google play store. So, because google play service is parked at that version, it will not be upgraded and not causing problems with android auto.

Here is a video of using Auto Companion Pro App, which is an improved version of Auto Companion App on [youtube](https://www.youtube.com/@kluane)

If these steps are helpfull for you, please consider purchase [Auto Companion Pro](https://play.google.com/store/apps/details?id=com.ingenika.autocompanionpro) App which can much improve your android auto debuging process. Normally you need to click back and forth a lot to found these setting and make change, with Auto Companion Pro, it's a one stop for android auto debuging. Especially when you are in a rush, or in a emergency, time can save life.

