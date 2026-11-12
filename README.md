
# Fancy README Guide
I tend to forget how to do certain stuff on GitHub READMEs. This will be a guide on how to do fancy READMEs. Feel free to use anything from here for your own READMEs. README. 


<!-- Headline Guide. -->
# Headlines! Oh, this is one too!
Adding headlines is as easy as adding a ```#``` (hashtag) to a piece of text.

<!-- This a markdown comment. It does not render in the README. -->
```
# A headline!
## Adding 2 makes it a bit smaller than just 1, but a bit bigger than normal text
### Adding 3 makes it still bold, but the same size as normal text. 
```




<details>
<summary>Example</summary>

# Super badass and epic project
Blah blah blah......
## Features
Blah blah blah......

### Credits
Me

</details>

<details>
<summary>Code for the example </summary>

```
# Super badass and epic project
Blah blah blah......
## Features
Blah blah blah......

### Credits

```
</details>



# Text fun stuff

## Quotes
You can make a block of a "normal quote" by adding a ```>``` (greater-than sign) before your text.

**Example:**
> // I still call DoomGuy "The Marine", it's cooler that way. (Jakie, Spider's Delight) 


**Raw Example:**

``` > // I still call DoomGuy "The Marine", it's cooler that way. (Jakie, Spider's Delight)  ```



## Code Quotes
You can also quote code by adding a set ``` (backtick or tilde key). Hint hint, that's how I've been showing you the raw code sections! Unfortunately, that means I can't easily show it off. But I can show you the end result. 

```
map SDEYE lookup "Blind Lover's Eye"
{
 next = "EndGameC"
 secretnext = "SDSEC3"
 sky1 = "PLSKY1", 0
 sky2 = "SKY3", 0.2
 NoInfighting
 Music = "$MUSIC_SHAWN2"
 Cluster = 73
}

```

This ignores formatting, so it's nice to use when showing how to format something with bold, strikethrough, etc.

``` ***This text is a bit too exposed to be Bold in the moment.*** ```


## Tables


Tables can be tricky. It is text that is "closed" by | (pipes). This forms a "section." Add more and you got a table. 

It goes in this order.

``` | WORD | ANOTHER WORD | EVEN MORE WORDS | ```

Note, the separator between the headers and the rest of the table is actually it's own entry. You have to make changes to it if you are editing the table. It does not do it automatically.  

You can add on any amount of sections as you need. But you need every entry to match the number of sections you made.  

**Example:**

| Sonic Character  | Favorite Food | Color  | Best Friend |
| ------------- | ------------ | ------------- | ------------- |
| Sonic  | Chilidogs | Blue | Tails | 
| Tails  | Mints | Yellow | Sonic |
| Knuckles  | Grapes | Red | Who? |
| Amy  | Ice Cream | Pink | Cream |
| Cream  | Also Ice Cream | Tan | Amy | 

**Raw Example:**
```
| Sonic Character  | Favorite Food | Color  | Best Friend |
| ------------- | - | ------------- | ------------- |
| Sonic  | Chilidogs | Blue | Tails | 
| Tails  | Mints | Yellow | Sonic |
| Knuckles  | Grapes | Red | Who? |
| Amy  | Ice Cream | Pink | Cream |
| Cream  | Also Ice Cream | Tan | Amy | 

```

You can add formatting to your text while they're in a table. With this, I will also show you all of basic text formatting you can use on your README.

**Example:**
| Style | How to use it | Example |
| ------------- | ------------- | ------------- |
| Italic | ```*``` (1 Asterisk on both sides on the text) | *Italic text!* |
| Bold | ```**``` (2 Asterisk on both sides on the text) | **Bold text!** |
| Italic and Bold | ```***``` (3 Asterisk on both sides on the text) | ***Italic and Bold text!*** |
| Strikethrough | ```~~``` (2 tildes on both sides on the text) | ~~Strkethrough!~~|
| Subscript | ```<sub> TEXT </sub>``` | <sub> Subscript! </sub> |
| Superscript | ```<sup> TEXT </sup>``` | <sup> SUEPRscript! </sup> |
| Underline | ```<ins> TEXT </ins>``` | <ins> Underline! </ins> |

**Raw Example:**
```
| Style | How to use it | Example |
| ------------- | ------------- | ------------- |
| Italic | ```*``` (1 Asterisk on both sides on the text) | *Italic text!* |
| Bold | ```**``` (2 Asterisk on both sides on the text) | **Bold text!** |
| Italic and Bold | ```***``` (3 Asterisk on both sides on the text) | ***Italic and Bold text!*** |
| Strikethrough | ```~~``` (2 tildes on both sides on the text) | ~~Strkethrough!~~|
| Subscript | ```<sub> TEXT </sub>``` | <sub> Subscript! </sub> |
| Superscript | ```<sup> TEXT </sup>``` | <sup> SUEPRscript! </sup> |
| Underline | ```<ins> TEXT </ins>``` | <ins> Underline! </ins> |
```

## List and Check lists
These are easy. Just add a - (minus) to the beginning of your text to make a list.

**Example:**
- Windows
- Mac
- Linux

**Raw Example**
```
- Windows
- Mac
- Linux
```

To do a number list...just add a number next to your text.

1. Pathways Into Darkness
2. Marathon
3. Myth
4. Halo

For a check list, you need type a - (minus), then trap a poor ```x``` around 2 ```[ ]``` square brackets. For entries that are not fulfilled, you place a space. 

**Example:**

- [x] Keyboard 
- [x] Mouse 
- [ ] Controller

**Raw Example:**

```
- [x] Keyboard 
- [x] Mouse 
- [ ] Controller
```
## Links
Links are also tricky. First, wrap your text around with ```[]``` (square brackets), then with ```()``` (parentheses), wrap the link you want on your text.

**Example:**

[Jakie's Github](https://github.com/SnakieJakie)


**Raw Example:**

```

[Jakie's Github](https://github.com/SnakieJakie)

```

Pro tip. On the web GitHub editor, if you CTRL-V on a pair of text with a link, it will automatically make that text a link! Handy!  

Like formatting, you can have text links in tables.

**Example:**
| Linux Distro  | Download Links |
| ------------- | - 
| Mint  | [Download(github.com/linuxmint)](https://github.com/linuxmint) |
| Ubuntu  | [Download(ubuntu.com/)](https://ubuntu.com/) |
| Kubuntu  | [Download(kubuntu.org/)](https://kubuntu.org/) |

**Raw Example:**

```
| Linux Distro  | Download Links |
| ------------- | - 
| Mint  | [Download(github.com/linuxmint)](https://github.com/linuxmint) |
| Ubuntu  | [Download(ubuntu.com/)](https://ubuntu.com/) |
| Kubuntu  | [Download(kubuntu.org/)](https://kubuntu.org/) |

```

# Images
Images are probably the most wanted to have in a README. Luckily, they are simple to put in. In fact, they are the same as links.

The first section will be the text when you hover the image or the image fails to load. Place a ```!``` (exclamation mark) before you text and then wrap it around with ```[]``` (square brackets) , then with ```()``` (parentheses), wrap the link to your image. Note, you need to have the image open separately from a page. If you just link to the page where you image, it will become a text link. You must link to the image itself.

You can also add images in the small attach files box on the bottom of the editor.
<img width="1023" height="71" alt="examnple2" src="https://github.com/user-attachments/assets/afa6a21c-477d-46d8-8b46-460d51ab2d74" />


**Example:**
![Steamboat Willie](https://cspd.law.duke.edu/wp-content/uploads/sites/11/2026/04/Steamboat-WIllie-Enters-Public-Domain-1024x748.jpeg)


**Raw Example**

```
![Steamboat Willie](https://cspd.law.duke.edu/wp-content/uploads/sites/11/2026/04/Steamboat-WIllie-Enters-Public-Domain-1024x748.jpeg)
```

Before you ask, GIFs do work on READMEs too. They just don't show up on previews. If there's just a empty spot, you're good. 

**Example:**
![Steamboat Willie](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdDNpanU4Y2lzbzA0eGE1ajdoaHVpY3c3a2NucjEzdGJqYTl5bzh0YiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l2JhL0Gpfbvs4Y07K/giphy.gif)

**Raw Example**

```
![Steamboat Willie](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdDNpanU4Y2lzbzA0eGE1ajdoaHVpY3c3a2NucjEzdGJqYTl5bzh0YiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l2JhL0Gpfbvs4Y07K/giphy.gif)
```
Images also work in tables. 

**Example:**

| Mickey Mouse cartoon  | Date of release |
| ------------- | - 
| ![Plane Crazy](https://thumb.wikimedia.org/wikipedia/commons/thumb/a/a0/1_-_Plane_Crazy.jpg/250px-1_-_Plane_Crazy.jpg?utm_source=en.wikipedia.org&utm_campaign=parser&utm_content=thumbnail)  | May 15, 1928 |
| ![The Gallopin' Gaucho](https://static.wikia.nocookie.net/disney/images/e/ef/The_Gallopin%27_Gaucho_WDT_title_card.jpeg/revision/latest?cb=20230822160554)  | August 7, 1928 |
| ![Steamboat Willie](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSSfEUGz8qNhykCnEccaWGjN2hYGMU2SAUAwh5DmekaPZyZY31pvEF_wxA&s=10)   | November 18, 1928 |

** Raw Example:**
```
| Mickey Mouse cartoon  | Date of release |
| ------------- | - 
| ![Plane Crazy](https://thumb.wikimedia.org/wikipedia/commons/thumb/a/a0/1_-_Plane_Crazy.jpg/250px-1_-_Plane_Crazy.jpg?utm_source=en.wikipedia.org&utm_campaign=parser&utm_content=thumbnail)  | May 15, 1928 |
| ![The Gallopin' Gaucho](https://static.wikia.nocookie.net/disney/images/e/ef/The_Gallopin%27_Gaucho_WDT_title_card.jpeg/revision/latest?cb=20230822160554)  | August 7, 1928 |
| ![Steamboat Willie](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSSfEUGz8qNhykCnEccaWGjN2hYGMU2SAUAwh5DmekaPZyZY31pvEF_wxA&s=10)   | November 18, 1928 |
```


**Extreme Example**
Shows off most of the things talked about in one table. 

**Table of low-level demons in Classic Doom** 
| Image | Name **(Bold stands for most popular name)** | Internal Name  | First appearance on Ultra-Violence | Strategy | Trivia |
| --- | ------------- | - | ------------- | ------------- |  ------------- | 
| <img width="43" height="54" alt="ZombieMan" src="https://github.com/user-attachments/assets/09d88dc2-e324-45cf-a0e3-efa713245403" /> | **Zombie Man**, Pistol Zombie, Former Humans, Troopers | ``ZombieMan`` | [E1M1: Hangar](https://doomwiki.org/wiki/E1M1:_Hangar_(Doom))  | Really anything takes them down. Probably not worth a BFG round. | They base their sprites from the player marine's sprites, which was made from a clay model made by [Adrian Carmack.](https://doomwiki.org/wiki/Adrian_Carmack)|
| <img width="39" height="54" alt="Shotgunner" src="https://github.com/user-attachments/assets/b384b0b7-4044-44eb-8286-35e0b9452fd4" /> | **Shotgunner**, Sergeant, Shotgun Zombie | ``ShotgunGuy`` |  [E1M1: Hangar](https://doomwiki.org/wiki/E1M1:_Hangar_(Doom)) | They also go down pretty easy, but their shotgun can put out a lot of damage, especially if you are close to them.  |  They are unused sprites of them pumps their shotguns after use. In the final game, they just magically have another shell loaded after firing one. |
| <img width="55" height="55" alt="Imp" src="https://github.com/user-attachments/assets/7dea5416-2990-4bb6-bd69-705450f2deca" /> | **Imp** | ``DoomImp`` | [E1M1: Hangar](https://doomwiki.org/wiki/E1M1:_Hangar_(Doom)) | Stronger than the humans, but still easy to kill. They throw a fire ball which can be dodged, unlike the firearms the others use. |  They are one of the few monsters in Doom that was mostly hand-drawn. Their sprites was made with [Deluxe Paint 2.](https://en.wikipedia.org/wiki/Deluxe_Paint) |
| <img width="48" height="55" alt="Pinky" src="https://github.com/user-attachments/assets/6919e6bb-0c32-4cff-bd28-1491e5b975bb" /> | **Pinky**, Demon | ``Demon`` | [E1M3: Toxin_Refinery](https://doomwiki.org/wiki/E1M3:_Toxin_Refinery_(Doom)) | The only non-projectile monster in Doom. They are a lot tougher than Imps or the former humans, but can easily be killed with the [Chainsaw](https://doomwiki.org/wiki/Chainsaw).| In the classic Doom games, they were just named "Demon." In Doom 2016, they were renamed to Pinky, likely to not cause confusion. | 

**Raw Example:**
```
**Table of low-level demons in Classic Doom** 
| Image | Name **(Bold stands for most popular name)** | Internal Name  | First appearance on Ultra-Violence | Strategy | Trivia |
| --- | ------------- | - | ------------- | ------------- |  ------------- | 
| <img width="43" height="54" alt="ZombieMan" src="https://github.com/user-attachments/assets/09d88dc2-e324-45cf-a0e3-efa713245403" /> | **Zombie Man**, Pistol Zombie, Former Humans, Troopers | ``ZombieMan`` | [E1M1: Hangar](https://doomwiki.org/wiki/E1M1:_Hangar_(Doom))  | Really anything takes them down. Probably not worth a BFG round. | They base their sprites from the player marine's sprites, which was made from a clay model made by [Adrian Carmack.](https://doomwiki.org/wiki/Adrian_Carmack)|
| <img width="39" height="54" alt="Shotgunner" src="https://github.com/user-attachments/assets/b384b0b7-4044-44eb-8286-35e0b9452fd4" /> | **Shotgunner**, Sergeant, Shotgun Zombie | ``ShotgunGuy`` |  [E1M1: Hangar](https://doomwiki.org/wiki/E1M1:_Hangar_(Doom)) | They also go down pretty easy, but their shotgun can put out a lot of damage, especially if you are close to them.  |  They are unused sprites of them pumps their shotguns after use. In the final game, they just magically have another shell loaded after firing one. |
| <img width="55" height="55" alt="Imp" src="https://github.com/user-attachments/assets/7dea5416-2990-4bb6-bd69-705450f2deca" /> | **Imp** | ``DoomImp`` | [E1M1: Hangar](https://doomwiki.org/wiki/E1M1:_Hangar_(Doom)) | Stronger than the humans, but still easy to kill. They throw a fire ball which can be dodged, unlike the firearms the others use. |  They are one of the few monsters in Doom that was mostly hand-drawn. Their sprites was made with [Deluxe Paint 2.](https://en.wikipedia.org/wiki/Deluxe_Paint) |
| <img width="48" height="55" alt="Pinky" src="https://github.com/user-attachments/assets/6919e6bb-0c32-4cff-bd28-1491e5b975bb" /> | **Pinky**, Demon | ``Demon`` | [E1M3: Toxin_Refinery](https://doomwiki.org/wiki/E1M3:_Toxin_Refinery_(Doom)) | The only non-projectile monster in Doom. They are a lot tougher than Imps or the former humans, but can easily be killed with the [Chainsaw](https://doomwiki.org/wiki/Chainsaw).| In the classic Doom games, they were just named "Demon." In Doom 2016, they were renamed to Pinky, likely to not cause confusion. | 
```
