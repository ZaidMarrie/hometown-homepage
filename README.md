# Hometown Homepage (Solo Project Solution)

This is my solution to the [Hometown Homepage Solo Project on Scrimba](https://scrimba.com/learn/htmlandcss/solo-project-hometown-homepage-cob2e4812840974342ebb42eb). The solo projects are part of the [Scrimba Platform's Courses](https://scrimba.com/allcourses).

## Overview

### The challenge

You are required to do the following:

- Build the site from scratch
- Make use of classes
- Make use of flexbox
- Make use of background-image
- Make use of given color-palette

The following is not required, but they are some stretch goals to take this project further:

- Make it about your own hometown, country, or whatever place you like
- Use a different color palette
- Add a google font
- Find a way to use the `:hover` psuedo-class
- Add a whole new section

### Links

- [Original Figma Design](https://www.figma.com/file/2QuGfAOcHaZJ6aHXfuamnK/Hometown-Homepage?node-id=0%3A1)
- [My Figma Design](<https://www.figma.com/file/iKZzVyP8TXAslhKW6j3qUk/Hometown-Homepage-(My-Own-Design)?node-id=0%3A1>)
- [Live Solution Site](https://zaidmarrie.github.io/hometown-homepage-solo-project/)

## My process

### Built with

- HTML5
- CSS3
- Flexbox
- Mobile-first workflow

### What I learned

I haven't learned much with this project as I am already familiar with all the concepts I used in this project. However, the practice has helped me reinforce those concepts. I have also started using utility classes more often and efficiently.

Some code snippets from this project, see below:

```html
<header class="header flex">
	<div class="header-container">
		<h1 class="title">Johannesburg</h1>
		<p class="subtitle">
			Johannesburg, also known as the Jozi, Joburg, or “The City of Gold”.
		</p>
		<p class="subtitle">
			Johannesburg is the largest city in South Africa, and is one of the 100
			largest urban areas in the world.
		</p>
	</div>
</header>
```

```css
/* Utility Classes */
.capitalize {
	text-transform: capitalize;
}

.flex {
	display: flex;
	gap: 1rem;
}

.container {
	width: min(100% - 2rem, 1200px);
	margin-inline: auto;
}
```
