# CoffeeMaker
This is part of a project to manage a coffee maker at home from a Android mobile phone. It's made up of an Android app written in Kotlin as the front-end, Firebase service as the back-end and Raspberry PI 3 as a single board computer with a script written in Javascript running on Node.JS and integrated to a coffee maker with water level sensors.

The coffee maker can be turned on/off by the Android app. Nonetheless, it can only be kept turned on maximum of 1 hour. If such an amount of time has passed, it automatically turns off and it rests up by 5 minutes in order to be available of turning on again.

Also, there is a couple of float ball liquid sensors in the cold water tank monitoring the water levels. If there is not enough water, the coffee maker cannot be turned on by the Android app. So then, it shows an error message on this issue.

## Project arquitecture

![Project arquitecture](https://raw.githubusercontent.com/ivanph1017/AssetsRepo/master/CoffeeMaker/arquitectura%20coffee%20maker.png)

-	[CoffeeMakerJS project](https://github.com/ivanph1017/CoffeeMakerJS)
-	[CoffeeMakerKotlin project](https://github.com/ivanph1017/CoffeeMakerKotlin)

<div style="width:90%;margin:auto;">
    <img style="margin:20px;" src="https://raw.githubusercontent.com/ivanph1017/AssetsRepo/master/CoffeeMaker/intro.gif" alt="Intro" height="480" width="288"/>
    <span>
        <img style="margin:20px;"
        src="https://raw.githubusercontent.com/ivanph1017/AssetsRepo/master/CoffeeMaker/waterFilling.gif" alt="Water filling" height="480" width="288"/>
    </span>
    <span>
        <img style="margin:20px;"
        src="https://raw.githubusercontent.com/ivanph1017/AssetsRepo/master/CoffeeMaker/preparingCoffee.gif" alt="Preparing coffee" height="480" width="288"/>
    </span>
</div>

<div style="width:90%;margin:auto;">
    <img style="margin:20px;" src="https://raw.githubusercontent.com/ivanph1017/AssetsRepo/master/CoffeeMaker/coffeeReady.gif" alt="Coffee ready" height="480" width="288"/>
    <span>
        <img style="margin:20px;"
        src="https://raw.githubusercontent.com/ivanph1017/AssetsRepo/master/CoffeeMaker/coffeeMakerResting.gif" alt="Coffee ready" height="480" width="288"/>
  </span>
</div>

