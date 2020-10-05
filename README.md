# xterm.js
A drop-in JavaScript module to colorize Xterm output (both ANSI 16 + 256 colors) on your webpages. Absolutely no external dependencies required!

# Live Demo

A demo is worth a thousand words.

- **Basic Demo**: [See a live demo](https://l33t-xyz.github.io/xterm.js/demo.html) ([source](https://github.com/l33t-xyz/xterm.js/blob/master/demo.html)).
- **[Visual regression test with ANSI 16 + 256 colors](https://l33t-xyz.github.io/xterm.js/test.html)** ([source](https://github.com/l33t-xyz/xterm.js/blob/master/test.html)).

# How It Works

Like magic, it turns simple HTML markup using the `<code>` tag with the `xterm` class:

    <code class="xterm">
    @g[1] Your flame @G<@W*><-:-><*@G> @YSLAUGHTERS @G<@W*><-:-><*@G>@w @gan antlion! @R[358]
    @RAn antlion screams as the flames engulf it!!
    @wYou receive @G68+7+@R7@w experience points.
    @wYou receive @G82@w bonus experience points from your daily blessing.
    @wYou have @Y71@w daily blessing bonus experience kills remaining.
    @wYou get @Y6,790@w gold coins from the charred corpse of an antlion.
    @MYou are taxed @Y67@M gold coins by your clan.
    @wYou get an @ra@wn@rt@wl@ri@wo@rn @Y{@whusk@Y}@w from the charred corpse of an antlion.
    @cThe Fallen Soldier gives you @Y62@c gold coins for the charred corpse of an antlion.
    </code>

... into l33t output you can share with your MUD and RL friends:

![image](https://user-images.githubusercontent.com/422501/62266324-bc9b9280-b3dc-11e9-9b54-bf53021b7c9c.png)

# Get Started in under 30 seconds

**It's as easy as 1, 2, 3!**

1. Wrap all Xterm output you would like to format as colorized with:  
    `<code class="xterm">...</code>`.
2. Include this line before the closing `</body>` tag of your HTML document:  
    `<script type="text/javascript" src="//l33t-xyz.github.io/xterm.js/xterm.js"></script>`  
    *(Alternatively, if you would like, [download the file `xterm.js`](https://raw.githubusercontent.com/l33t-xyz/xterm.js/master/xterm.js) and upload it to your webserver to host it locally.)*
3. Profit!

# Authors

Created by [Hacktoolkit](https://github.com/hacktoolkit) and maintained by [L33t.xyz](https://github.com/l33t-xyz).

# Contributing

Pull requests are welcome! If you would like to contribute to this project, please fork this repository, create a branch, and submit a pull request.

All meaningful code contributions will be recognized in [`CONTRIBUTORS.md`](https://github.com/l33t-xyz/xterm.js/blob/master/CONTRIBUTORS.md).

# License

See [`LICENSE.md`](https://github.com/l33t-xyz/xterm.js/blob/master/LICENSE.md)
