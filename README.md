# blackorwhite

 Get either black or white hex codes ('#000000' or '#ffffff'), depending on the background color for its optimal constrast, mostly for the purpose of legibility of the text on the background.

# install

    npm install --save blackorwhite

# usage

    import blackOrWhite from 'blackorwhite';

    // later in the codes when using

    const color = blackOrWhite.get('#9674cd');
    console.log(color); // #ffffff

# credits

 The logic and many parts of the codes are stolen from [this](http://stackoverflow.com/questions/3942878/how-to-decide-font-color-in-white-or-black-depending-on-background-color) StackOverFlow answer/comments.
