# NSS CSS Pseudoclasses Exercise

### Project Description
This assignment was an exercise in `css` styling and accessing `html` elements using the class `n-child`.

![Pseudoclass Screengrab](https://raw.githubusercontent.com/SMITHsharon/pseudoclasses/master/screen/pseudoclasses%20screen%20shot.png)

### Project Specs
The html file was provided and could not be changed as given. 

- `<li>` items were given as block level elements: Added correct styles to remove the bullets and display them as inline elements

- The three <span> elements: Should be displayed as block elements with a 1 pixel border and 25 pixel margin on all sides

- In the article element with the class n-child: Added a 1 pixel border around every even numbered section element

The given html code follows: 
```
<ul class="top">
  <li class="block">1</li>
  <li class="block">2</li>
  <li class="block">3</li>
</ul>

<span class="inline">X</span>
<span class="inline">Y</span>
<span class="inline">Z</span>

<article class="n-child">
  <section> A </section>
  <div> X </div>
  <section> B </section>
  <section> C </section>
  <section> D </section>
</article>

<article class="n-type">
  <section> A </section>
  <section> B </section>
  <aside> Aside </aside>
  <section> C </section>
  <section> D </section>
  <section> E </section>
</article>

<article class="first-of-type">
  <section> A </section>
  <section> B </section>
  <aside> Aside 1 </aside>
  <section> C </section>
  <section> D </section>
  <aside> Aside 2 </aside>
  <section> E </section>
  <footer>Footer</footer>
</article>

<article class="three">
  <section> A </section>
  <section> B </section>
  <aside> Aside </aside>
  <section> C </section>
  <section> D </section>
  <section> E </section>
</article>
```

### Technologies Used
- html
- css


### How To View The Blog 
#### (Node must be installed on your machine):
```
git clone https://github.com/SMITHsharon/pseudoclasses.git
cd pseudoclasses
npm install http-server -g
http-server -p 8080
```

This will show in your browser at: `http://localhost:8080`

### Contributor
[Sharon Smith](https://github.com/SMITHsharon)






