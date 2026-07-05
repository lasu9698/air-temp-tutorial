

## Air Temperature
Let's write a program to show air temperature on your Micro:bit


## Step 1
First, we need to set up the basic ``||basic: forever||`` block. It is a loop that allows us to display for an infinite amount of time

```blocks
basic.forever(function () {
   
})
```

## Step 2
Go to Basic ``||basic: show number||`` and put it inside basic ``||basic: forever||``


This displays a number on your Micro:bit
```blocks
basic.forever(function () {
    basic.showNumber()
})
```

## Step 3
Go to Input ``||input: temperature (C)||`` and drag it in to replace 0 in basic ``||basic: show number||``
```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})
```

## Congratulations, you did it!
Download the program to your Micro:bit and test it out!





