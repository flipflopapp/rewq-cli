# rewq-cli
A command line tool for quickly opening URLs.

Let me just explain it with a few examples.


## Usecase 1 : Quickly open a longish link

Suppose, you go to a STANDUP everyday to a link - https://meet.google.com/gar-feil-dtd?authuser=2

You could bookmark it. Or even faster, you could go to command line and type,

```
$ rewq standup 
```
 ... boom the link opens on browser

ofcourse you had configured it earlier,

```
$ rewq standup  https://meet.google.com/gar-feil-dtd?authuser=2
```

or even faster, way to open the link would be, just type… around 11 AM

```
rewq 
```

…. becasuse you had configured it with time,

```
rewq stantup LINK around 11:00 AM
```


## Usecase 2: Quickly open a list of links

Suppose you instead wanted to make a list of youtube (and non-youtube) videos for exercises.

Workout 1 - Exercises
https://www.youtube.com/playlist?list=PLoy7IsGb6mC0TJbFGcTvHWaiOUu7b3Ill

Workout 2 - Dip station
https://www.youtube.com/playlist?list=PLoy7IsGb6mC2_fgATd8TV3uQayi9-qsML

Workuot 3 - Kettlebells
https://www.youtube.com/playlist?list=PLoy7IsGb6mC1x05KfrmpfsdMlff_fDtQd

Then you could type, 

```
$ rewq workouts
```
And it dumps the list and allows you to pick 1, 2, or 3.

Ofcourse you had to configure it,

```
$ rewq workouts add Exercises https://www.youtube.com/playlist?list=PLoy7IsGb6mC0TJbFGcTvHWaiOUu7b3Ill
$ rewq workouts add Dip-Station LINK2
```
etc... Or all at one go,
```
$ rewq workouts Name1 LINK1, Name2 Link2, Name3 Link3
```

I guess you get the idea. 

You could use it for jupyter notebooks, company links, or I don't know what but other things also.


## Finally your feedback

To test it out, I built web version https://rewq.app . 

It allows just one list, or one shortcut, or open one random link from the list from your browser localstorage. 

Should I build this tool properly?

Let me know if you can use it at flipflopapps@gmail.com 


## WHY REWQ

I will just demo this.

1. Click on browser URL
2. Put your left index fingure on R.
3. Make an tilted angle to slide your finger in left direction.
4. Slide your finger in left direction, typing out R-E-W-Q one by one, until TAB.
5. If its your first time opening https://rewq.app ; you will have to type .app now . But for the next time auto-complete would also know it.

REWQ is meaningless, except for its really convenient to type-it (rather swipe-it) with one finger. 

## Why am I posting this

I have an undiagnosed OCD around making tiny-apps. I last made https://halfchess.com and have a list of next ideas I want to build. Apprently, I am unable to sleep if I dont build stuff and I am not sure if I should build stuff. **Because I want people to use what I built.**

So, do write to me if you need this and I will make it for FREE and sleep.


