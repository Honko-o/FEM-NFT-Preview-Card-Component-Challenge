# Frontend Mentor - NFT preview card component

![Design preview for the NFT preview card component coding challenge](./design/desktop-preview.jpg)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- CSS Flexbox
- Sass
- Mobile-first Approach

### What I learned

I learnt that even though CSS Flexbox centers everything sometimes it doesn't center it accurately 
You need to do it by hand sometime using line-height and other properties.

The Code for Centering:

``` CSS
            .nft-remaining-time {
                flex-basis: 50%;
                display: flex;
                align-items: center;
                justify-content: flex-end;
                .time {
                    color: $lightBlue;
                    margin: {
                        top: 0;
                        right: 0;
                        bottom: 0;
                        left: 5px;
                    }
                    line-height: 1rem;
                }
            }
```
Explaination of the Above CSS:
I decided to use Flexbox and then I removed Margin so that the line-height property centers it along the SVG Icon
I don't know if that was the right approach or there was some better solution
but it worked out quite well for me.
