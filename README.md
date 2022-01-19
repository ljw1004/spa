# Simple spa chemicals

This web-app helps you record your bromine spa chemical levels.
* Use it now (iPhone): https://ljw1004.github.io/spa/

![IMG_8174](https://user-images.githubusercontent.com/3316258/150050604-0afd4dcb-8d57-45d0-83ab-2677afd6f052.PNG)

* You can also add it to your home screen: click on the "share" button...

![IMG_8171](https://user-images.githubusercontent.com/3316258/150050762-7c4dc73b-3b18-4049-8a5d-1ae7547b7af5.PNG)

![IMG_8173](https://user-images.githubusercontent.com/3316258/150050745-e4e5b642-4a7d-4baa-92e2-8dde18425e30.PNG)

## What this does

If you have a bromine-based spa (hot tub), you have to measure and adjust the chemical levels. I wrote this web-app because the other apps made it all too complicated...
1. **I want to know the previous reading, to make this reading easier.**
   * Example: if last week it was 150ppm alkalinity, then today it'll probable be about the same. I can rapidly drop in 12 drops of testing chemical, and then be slower and swirl more carefully for the next few drops.
2. **I want to quickly record the reading.** I don't want to click through multiple screens. And if my [Taylor testing kit](https://www.amazon.com/Taylor-Swimming-Chlorine-Alkalinity-Hardness/dp/B001DNXK78) only gives ppm readings to the nearest 10, there's no point letting me record with higher precision.
5. **I want to know what is the ideal.** That way I can decide how to adjust it.
   * This app shows acceptable and ideal ranges for a residential permanent bromine spa, according to the Association of Pool and Spa Professionals
6. **I want to use my choice of chemicals.**
   * Example: if my alkalinity is 50ppm below ideal, then I'll simply add 20 tablespoons of [SpaGuard Balancer](https://www.amazon.com/SpaGuard-Total-Alkalinity-Increaser-Pack/dp/B01MD2BXWO) like it says on the label. (Other apps merely tell me to add 11oz sodium bicarbonate, without explaining why, and that doesn't help).
7. **I want to know Saturation Index.** This tells me whether the overall water balance is corrosive to my pipes, or will deposit scale, or if it's just right.
8. **I don't want to create a login and password.** I don't want my email sold to mailing lists.
   * This web-app only saves data locally, in the browser cache on your device.
9. **I have no need to keep history.** Who cares what were my chemical levels 5 months ago? They were all within the ideal range, of course. Why do I need an app to tell me that I haven't measured the water for a week, or that I need to shock? I can figure those things out better myself. The only history I care about is the previous reading, to make it easier to count drops.

## Known issues
* I've only tested this on iPhone. I bet there are glitches on Android and Firefox, but I don't own those devices to test.
* I've hard-coded the "acceptable / ideal" values for a residential bromine permanent spa, since I don't know what spa maintenance is like for others. I'd like to (1) allow you to customize the ideal levels, (2) offer the standard ideal levels suggested by the Association of Pool and Spa Professionals for different kinds of spa.
* This app is heavily centered towards [Taylor testing kit](https://www.amazon.com/Taylor-Swimming-Chlorine-Alkalinity-Hardness/dp/B001DNXK78) and [SpaGuard checmicals](https://www.amazon.com/s?k=SpaGuard&ref=bl_dp_s_web_3041629011) since they're what I use. I also use a variety of testing strips. I don't know if other people use measurements or chemicals that just don't relate to what this app offers.
* This web-app doesn't let you view past readings. I know they're not very useful. But it'd be nice nonetheless to be able to export them, or view them on desktop.
* I'd be delighted to accept contributions!
