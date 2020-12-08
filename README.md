# nc3ctf2020-Writeups
Writeups of this year CTF from Politiets NC3 department -- Will be published the 17th December


## Begynder

#### Introduktion til CTF _(100 points)_

We are given the following string.

`mb3{hmfdm_ahrrdq_jtm_rmd_nf_mhrrdq}`

Simply parse it through `****` to reveal the flag

`***********************************`

-------

#### Besked fra fronten _(100 points)_

```
nc3{JiM2ODsmIzgyOyYjNzM7JiM3NjsmIzc2OyYjNjk7JiM3ODsmIzczOyYjODM7JiM4MzsmIzY5OyYjODM7JiM0ODsmIzEwODsmIzc3OyYjODQ7JiMxMjE7JiM2NjsmIzY2OyYjODQ7JiM2OTsmIzkwOyYjNjY7JiM3MzsmIzY5OyYjMTIwOyYjNzQ7JiM4NDsmIzg1OyYjNjk7JiMxMDM7JiM4MjsmIzY5OyYjODY7JiM3NzsmIzg2OyYjNjk7JiM2OTsmIzEwMzsmIzgyOyYjODU7JiM3ODsmIzczOyYjODQ7JiMxMjE7JiM2NjsmIzgzOyYjODQ7JiM0ODsmIzQ5OyYjNzA7JiM4NDsmIzEyMTsmIzY2OyYjNzE7JiM4NjsmIzg1OyYjMTIwOyYjNzc7JiM3MzsmIzcwOyYjNzg7JiM4NTsmIzg0OyYjNDk7JiM2NTsmIzEwMzsmIzgxOyYjODU7JiMxMjA7JiM3MTsmIzgxOyYjODM7JiM2NjsmIzc3OyYjODM7JiM4NTsmIzQ5OyYjNjY7JiM3MzsmIzY5OyYjMTIwOyYjNzQ7JiM4NDsmIzg1OyYjNjk7JiMxMDM7JiM4MjsmIzg1OyYjNzg7JiM3MzsmIzg0OyYjMTIxOyYjNjY7JiM3MTsmIzg2OyYjODU7JiMxMjA7JiM3NzsmIzczOyYjNzA7JiM3ODsmIzg1OyYjODQ7JiM0OTsmIzY1OyYjMTAzOyYjODU7JiMxMDc7JiM1NzsmIzc4OyYjODI7JiM4NTsmIzU2OyYjMTAzOyYjODE7JiM4NTsmIzEyMDsmIzcxOyYjODE7JiM4MzsmIzY2OyYjODQ7JiM4MzsmIzg1OyYjODY7JiM4MzsmIzg1OyYjMTA3OyYjNjk7JiMxMDM7JiM4MzsmIzQ4OyYjMTA4OyYjNzc7JiM4NDsmIzEyMTsmIzY2OyYjNzA7JiM4MTsmIzQ4OyYjMTA0OyYjODA7JiM3MzsmIzY5OyYjOTA7JiM4NjsmIzg0OyYjNjk7JiMxMTk7JiMxMDM7JiM4NTsmIzQ5OyYjODI7JiM4MDsmIzg1OyYjNjc7JiM2NjsmIzc5OyYjODQ7JiM0OTsmIzkwOyYjNzA7JiM4NDsmIzg1OyYjNzQ7JiM3MDsmIzg1OyYjMTA1OyYjNjY7JiM3NDsmIzg0OyYjMTA3OyYjODI7JiM3NDsmIzgxOyYjODM7JiM2NjsmIzg0OyYjODM7JiM4NTsmIzg2OyYjODM7JiM4NTsmIzEwNzsmIzY5OyYjMTAzOyYjODU7JiM0ODsmIzEwODsmIzcwOyYjODU7JiMxMDg7JiM3NDsmIzY2OyYjNzM7JiM2OTsmIzg2OyYjNjg7JiM4MzsmIzY5OyYjNTY7JiMxMDM7JiM4NTsmIzEwNzsmIzU3OyYjNzg7JiM4MjsmIzg1OyYjNTY7JiMxMDM7}
```

-------

### Hallo, hallo, er der nogen? _(100 points)_

```
nc3{. -. -.. . .-.. .. --. ..--.- .--- ..- .-.. ..--- ----- ..--- -----}
```

-------

### Rosettestenen _(100 points)_

```neque eleifend In non aliquet nec Quisque auctor neqte id risus vel```

```Quisque vel risus non neque aliquet auctor nec id neqte In eleifend```

```gammel } flasker er nc3 sådan vand set nye i det {```



-------

### Julegåden 0 _(100 points)_

The first task in Julegåden is to find the password from the following string:
> Koden er: ‮2020‭Nisse‮jul‭Bar‮eDen‭bedste

Highlighting the string results in the cursor jumping to the end of the string and back to the beginning.
![Alt kode](https://i.imgur.com/dNBC8Ae.png)

-------



## Øvet

### Befibbet _(200 points)_

```
0x6e, 0x62, 0x32, 0x79, 0x61, 0x60, 0x6e, 0x64, 0x65, 0x52, 0x52, 0x2d, 0xcf, 0x85, 0x11c, 0x20d, 0x3b5, 0x65c, 0xa6a, 0x1031, 0x1a02, 0x2a9d, 0x4543, 0x6f94, 0xb544, 0x12574, 0x1da43, 0x2ff1d, 0x4d916, 0x7d8d3, 0xcb25c, 0x148ab8, 0x213d77, 0x35c7bd, 0x570480, 0x8ccca8, 0xe3d1c6, 0x1709e1c, 0x254705b, 0x3c50efd, 0x6197ea2, 0x9de8d32, 0xff80c4c, 0x19d699c4, 0x29cea5b1, 0x43a53fee, 0x6d73e53a, 0xb119248f, 0x11e8d0a25, 0x1cfa62f7e, 0x2ee33393e, 0x4bdd968e4, 0x7ac0ca186, 0xc69e60a01, 0x1415f2ac3c, 0x207fd8b6f2, 0x3495cb6291, 0x5515a419d7, 0x89ab6f7cc8, 0xdec113965f, 0x1686c8312b1, 0x2472d96a967, 0x3af9a19bbbd, 0x5f6c7b06496, 0x9a661ca20e4, 0xf9d297a85f9, 0x19438b44a63d, 0x28e0b4bf2b9b, 0x42244003d223, 0x6b04f4c2fe27, 0xad2934c6d0d0, 0x1182e2989ceb4, 0x1c5575e509f0e, 0x2dd8587da6e54, 0x4a2dce62b0dec

```

-------

### Kludetæppet _(200 points)_

```
ting = ["nc3", "gjort", "{", "specielt", "}", "_", "selv", "vel", "jule", "er", "med", "gaver", "guld"]
opskrift = [1, 3, 7, 2, 6, 10, 6, 8, 2, 6, 4, 6, 11, 6, 9, 12, 5]
kludeTaeppe = ''

for tal in opskrift:
	t = ting[tal]
	kludeTaeppe += t

print kludeTaeppe

```

-------

### Lorem Ipsum _(200 points)_

```
Lorem ipsum dolor sit amet, con{ectetur adipiscing elit. Duis gravida, ante ut feugiat faucibus, dolor nunc pharetra quam, ut placerat} lectus arcu nec tortor. Integer commodo justo id orci convallis, lacinia luctus erat imperdiet. Sed fermentum mattis congue. Proin gravida eros purus. Praesent
eget sem leo. Phasellus tortor er4t hendrerit nec diam ultrices, viverra aliquet ex. Mauris non pulvinar augue. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aliquam erat volutpat. Aliquam erat volutpat.
Nam et f3nibus dolor. Susp{endisse rutrum tempus jus3t pellentesque tempor. Sed vel nisl nul3a. Vestibulum sed justo felis. Vestibulum ornare libero et aliquam ultrices. Nam semper ipsum sed ipsum phare3ra aliquet.
Donec ante nulla, posu9re sit amet sem non, diggniss{im consequat urna. Nam lacus nibh, placerat sit amet sapien sed, tincidunt fermentum erat. Praesent eu urna lacus. Nu{llam nec sapien lectus. Quisque iaculis quam vel odio posuere, a gravida urna lobortis. Proin posuere, lectus eget congue phare{tra, massa purus porta felis, sed semper lorem met}us nec mi. Integer quis suscipit ligula. In ma3lesuada euis
mods sapien eu mo3estie. Ut quam ex, egestas et1 sember id, porta nec elit.
Cur5bitur eget pretium sapien. Et{iam sit amet ante gat turpis consectetur venenatis. Nulla ant3e ipsum, facilisis vel justo nec, pharetra luctus felis. Mauris molestie
porttitor ornare. Fusce elit justo, feugiat a pretiue sed, lacinia et ligula. Fusce
ullamcorper, felis et tincidunt tincidunt, tortor aurue porta mi, at sodales magna lacus accumsan nisl.
ras venenatis tincidunt justo hendrerit laoreet. Curcbitur vehicula nisi vel sceler}isque tempus.
Aenean ligula dolor, auctor id aliquam quis, aqiqutepe vitae nisl. Sed dapibus tellus eu dictum posuere. Aliquam euismod dapibus ex, rhoncus sollicitudin turpis vestibulum tristique.
pharetra. Duis ut est ut quam vestibulum pharetra aul eu e5os. Pellentesque viverra, metus vel venenatis, Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
semper, sem o3ci venenatis mi, quis rutrum le lacuseg sagittis justo. Done{c porta sceleris3ue ex. Nunc
porta tellus at auctor tempus. Maecenas neque diam, qemtus ut porttitor vitae, varius non arcu. Donec
n}n erat ante. Susp}ndisse efficitur vestibulum elemqetum. Maecenas egestas nunc a dui blandit interdu
m. In egestas nisl sit amet neque luctus, at pharetec purus convallis. Pellentesque mollis elit tinci
dunt felis f}nibus posuere. Phasellus semper digniss}m ante, at tristique sapien hendrerit eu. Fusce lobor{tis euismod quam sit amet ma}ximus. Aliquam et est mauris. Mauris laoreet volutpat felis, sed mattis lacus. Pellentesque tortor ligula, sollicitudin vitae turpis eu, congue sagittis velit. Aliquam condimentum, tortor vitae imperdiet varius, nulla arcu convallis urna, vitae mollis quam ex id ex. Nulla metus elit, sollicitudin eget aliquet ut, ultricies in tellus. In hac habitasse platea dictumst. Maecenas congue quam quis tellus sollicitudin, eget tincid}unt odio sollicitudin. Proin suscipit felis id mauris eges{tas, in lacinia sem tempor.
```

-------

### Nisse Omvendt _(200 points)_

Kodet_besked.bin:
> 8F 57 F0 B7 A2 9D AC AD AE 9B 93 98 98 93 95 96
> A3 A0 9D 9E AB AE AF A8 9C AC A5 AF B3 AF C7 BC
> A7 B2 B5 B3 AA A5 B3 B8 BE CA C3 C8 CB BF D0 DA

nisse_omvendt.py:
```
import sys
besked = sys.argv[1]
filnavn = 'kodet_besked.bin'
kodet_besked = ''

for i in range(0, len(besked)):
    c = ord(besked[i])
	nc = ord(besked[(i + 1) % len(besked)])
	c = (c ^ 64) & 0xFF
	c = (c -  1) & 0xFF
	c = (c ^  1) & 0xFF
	c = (c +  i) & 0xFF
	c = (c +  nc) & 0xFF
	kodet_besked += chr(c)

f = open(filnavn, 'w')
f.write(kodet_besked)
f.close()

f = open(filnavn, 'r')
kodet_besked = f.read()
f.close()

dekodet_besked = ''

for i in range(0, len(kodet_besked)):
	c = ord(kodet_besked[i])

$$2133248hfdsfBIIIIPP!!!123213123dddddCRASH!
```



-------

### B2R - Lillenisse
``` (200 points) ```

-------

### B2R - Mellemnisse
``` (200 points) ```

-------

### Julegåden 1
``` (200 points) ```

-------
