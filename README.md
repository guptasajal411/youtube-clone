# YouTube Clone
YouTube clone made with pure HTML and CSS. This website is best viewed on desktops.
I made this website as a challenge, it was really difficult to make with pure CSS.
<h3> You can view this website <a href="http://www.ytcloneproject.study">here.</a></h3>
Although this is a landing page, you can use the search bar to search for YouTube videos. Upon submit, the website will show results of your query on youtube.com.
<p> This website is not made for mobile viewports. Best viewed on desktops with vw > 786px. </p>
<hr>
<h2> Screenshots </h2>
<img src="https://i.ibb.co/59cjzbx/Capture.png" alt="Capture" border="0">
<p> This website was not made for mobile viewports. Best viewed on desktops with vw > 786px. The CSS Grid collapses on smaller devices, as the flexbox takes up entire width of the viewport.</p>

---

## How we built it
Made with HTML5 and CSS. For Navbar, Topics and Sidebar, I used CSS Flexbox property. For Videos section, I used CSS Grid to make it *somewhat* responsive. Also the Thumbnails of the custom videos are synchronized with actual YouTube database.  Other filler videos and thumbnails render random images from the internet upon every refresh.

---

## Challenges we ran into
Using Grid was the main challenge for the project. I experimented with various properties such as

```
grid-template-columns
column-gap
row-gap
repeat(4, 1fr)
@media
```

Also, three main flexboxes(navbar, topics and sidebar) were difficult to implement. The sidebar flexbox is NESTED inside grid, so it was really hard to contain it in a specific width. For that I used 

```
flex-direction: column;
width: 80%;
display: flex;
grid-row: 1/9;
column-gap: 0;
row-gap: 0;
overflow: auto;
```

---

## What's next for YouTube Clone
I will try to make this website responsive with media queries. This is really important for this project. After that, it can be viewed on any screen size and will behave exactly like original YouTube does.

---
