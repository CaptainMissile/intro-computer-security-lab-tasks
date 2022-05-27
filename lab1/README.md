# REPORT
## TASK 1:

__PLAIN TEXT:__ thequickbrownfoxjumpsoverthirteenlazydogs

__KEY: 14__

Here,we looped through the cipher text for different values of K=1 to K=25.

## TASK 2:

### CIPHER 1:

__REPLACING LETTERS:__

```python
replacing_letters_cipher_1 = {
                'b' : 'a', 'j' : 'n', 'w':'d', 'z':'o','v':'i', 'p' : 'f',
                'm': 'e', 'c':'r', 'q':'z', 'y':'s','k':'t', 'g': 'l', 'a': 'g',
                'd' : 'w', 'x': 'm', 't' : 'p', 'f' : 'v', 'i': 'c', 'e': 'y',
                'l':'b', 'r':'k'
            }
```

__Plain_Text_Back:__
    wood frogs of alaska are surprisingly starnge. in winter, they become frozen. two-thirds of their body water turns into ice. if you bent one of their legs, it would break. inside these frozen frogs, their hearts stop beating, their blood no longer flows and their glucose levels sky rocket. the craziest thing of all may be that in this frozen state, they can withstand temperatures as low as zero degrees fahrenheit for as long as seven months, and then, when spring arrives, thaw out and hop away.

### CIPHER 2:

__REPLACING LETTERS:__

```python
replacing_letters_cipher_2 = {
    'e' : 'e', 'q' : 'a' , 'k' : 't', 'y': 'n', 'z' : 'd' ,
    'd' : 'h', 's' : 'o' , 'f' : 'r', 'r':'c',
    'p' : 'i' , 'n' : 'f', 'g': 'b' , 'b' : 'w',
    'x' : 'm', 'j' : 's', 'w': 'l', 'm': 'p',
    'a' : 'v', 't':'y', 'h':'u', 'v': 'k',
    'c' : 'g', 'l' : 'j', 'o':'z', 'i' : 'x',
    'u':'q'
}
```
__Plain_Text_Back:__
when you look at the seas and oceans on the map you might think that they just flow into each other. it seems like there's only one big ocean, and people just gave different names to its parts. well, you'll be amazed at how vivid the borders between them are! the border between the pacific and atlantic oceans is like a line between two worlds. it looks as if the two oceans meet at an invisible wall which does not let them flow into each other and mix their waters. why on earth does it happen? we know for sure there is no invisible wall inside, and water is water. what could interfere with its mixing? the thing is that water can be different too. the atlantic and the pacific oceans have different density and chemical make-up, the level of salinity and other qualities. one can see by their color that they are far from being the same. the borders between two bodies of water with different physical and biological characteristics are known as ocean clines. haloclines – borders between waters with different salinity – are the most spectacular, and this is what we see when the atlantic and the pacific oceans meet. the famous explorer jacques cousteau found this when he was deep diving in the strait of gibraltar. the layers of water with different salinity looked like they were divided with a transparent film, and each layer had its own flora and fauna. haloclines appear when water in one ocean or sea is at least five times saltier than in the other. you can create a halocline at home if you pour some seawater or colored salty water in a glass and then add some fresh water on top of it. the only difference is that your halocline will be horizontal, and ocean haloclines are vertical. if you remember a couple of basic things from physics you might argue that a denser liquid should finally end up lower and less dense higher. if that were true the border between the two oceans would look not like a vertical line but as a horizontal one, and the difference between their salinity would become less obvious the closer they got to each other.

<hr>

__Which input was easier to break? Explain your answer.__

Cipher Text 2 was easier to break.<br>
> 1. In cipher text 2, there is a one letter word 'q' what clearly implies that it should be replaced with 'a'.
> 2. Cipher text 2 is quite a long. So it gives us a good letter frequency insight what is well-matched and comparable
       enough with the given frequency data.
> 3. As the text is large, guessing and replacing one letter impacts more words than the cipher 1. So both wrong guess
       and right guess can give more insights.
