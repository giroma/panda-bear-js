var img = document.querySelector('img');
img.src = 'https://www.codeproject.com/KB/GDI-plus/ImageProcessing2/img.jpg'

var img = document.querySelector('#left-image img');

var title = document.querySelector('h1')
title.innerText = 'Ari the bear'

var employment = document.querySelector('#employment h3')
employment = 'something else'

document.body.style.backgroundColor = 'cyan'

highlight.forEach(function(element) {element.style.background = 'red' })

var h1 = document.querySelector('h1');
h1.style.fontFamily = 'monospace'

var button = document.querySelector('.action-icon-bg');
button.style.backgroundColor = 'black'

var placeholder = document.querySelector('#name');
placeholder.placeholder = 'heyooo';

var placeholder = document.querySelector('#message');
placeholder.placeholder = 'dont ask';

var placeholder = document.querySelector('#name');
placeholder.value = 'shhh';

var placeholder = document.querySelector('#submit');
placeholder.value = 'dont do it';

var button = document.querySelector('#submit');
button.disabled = true;

var parent = document.querySelector('aside');
var bio = document.querySelector('.bio-info');
parent.removeChild(bio);

-----------------PART 2-------------------

var time = document.querySelector('#time-travel');
time.parentElement.parentElement.removeChild(time.parentElement);

var pika = document.querySelector('[title="Pikachu"]');
var portfolio = document.querySelector('.portfolio-container');
portfolio.appendChild(pika);

for (x = 0; x < 10; x++) {portfolio.insertAdjacentHTML('beforeend', pika)}

var newListItem = document.createElement('li');
newListItem.className += 'bio-info-item';
var leftSpan = document.createElement('span');
leftSpan.className += 'bio-info-title';
var lastUpdated = document.createTextNode('Page Last Updated on');
var rightSpan = document.createElement('span');
rightSpan.className += 'bio-info-value';
var updatedText = document.createTextNode(new Date());
