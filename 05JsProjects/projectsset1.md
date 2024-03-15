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

# project 2 

```javascript
const result = document.getElementById('results');

function bmi(h, w) {
  return (w / h ** 2) * 100;
}
document.getElementById('calc').setAttribute('type',"button")
document.getElementById('calc').onclick = () => {
  if (true) {
    const height = document.querySelector('#height').value;
    const weight = document.querySelector('#weight').value;
    const res = bmi(height, weight);
    result.innerHTML = `<h1>${res}</h>`;
  }
};


```