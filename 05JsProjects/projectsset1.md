# Project set 

[Click Here](https://stackblitz.com/edit/dom-project-chaiaurcode?file=index.html)

# solution code 
## project 1

```Javascript
console.log("priya")
function clicked(z) {
  const x = document
    .querySelector('body')
    .setAttribute('style', `background-color: ${z} `);
}

const y = document.querySelectorAll('.button');
y.forEach((b) => {
  const x = b.getAttribute('id');
  if (
    (document.getElementById(x).onclick = () => {
      if (true) {
        clicked(x);
      }
    })
  );
});


```