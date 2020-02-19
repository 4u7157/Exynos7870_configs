## These are Exynos7870 Android Oreo (8.0.0 - 8.1.0) configs from 2018 December security patch 2nd build (RL2)

```
a3y17lte - A320Y - A320YDXU3CRL3 (CRL1 and CRL3 defconfigs were same. That means CRL1=CRL2=CRL3)
a6lte - A600F - A600FJXU3ARL2
j5y17lte - J530F - J530FXWU3BRL2
j6lte - J600G - J600GDXU3ARL2
j7velte - J701F - J701FDDU6BRL2
j7xelte - J710F - J710FXXU5CRL2
j7y17lte - J730F - J730FXXS3BRL2
on7xelte - G610F - G610FDXU1CRL2
on7xreflte - SM-G611MT - G611MTVJS2BRL2
```
I got them by using simple but powerful tool ```extract-ikconfig```

TODO:

M105 any public release has 3.18.91 (P kernel). After asking for BRL2 build which was in version.test.xml, 1 hour later they responded with: ```As we checked, requested model's sw version is just for development.
According to our policy, we are not able to publish opensource software for any unofficial SW version, which includes Beta test version, too.``` I figured it may be possible if we rebase to new defconfig that has the 3.18.91.