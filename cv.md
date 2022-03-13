# My Curriculum Vitae
## __Dzmitry Kalasouski__ 
## __Contacts__
   1. **tel.** +48-511-588-827
   2. **mail** dmikol1325@gmail.com
   3. **skype** monte-kristo2712
## __About Me__
For me, this is a great opportunity to learn what I like. **My goal is to become a programmer**. I want to work in this area and enjoy my work. I quickly learn and improve my skills.
## __Skills__
**Basic** knowledge: html, css, js, php, mysql, joomla, wordpress, photoshop. **In-depth** knowledge: SEO(Search Engine Optimization.
## __Code Example__
```
function array(arr){
   return arr.split(',').length > 2 ? arr.split(',').slice(1, -1).join(' ') : null;
   }
```
```
 function cake(x, y){
   let asc = y.split('').map((item, index) => index %2 == 0 ? item.charCodeAt(0) : item.charCodeAt(0)-96);
   return (asc.reduce((a,b) => a + b))/x > 0.7 ? 'Fire!':'That was close!';
   }
```
```
function convert(input, source, target) {
  if (source === target) {
    return input;
  }
  let value = input.split('').reverse().reduce( (a, b, c) => {
    return a + Math.pow(source.length, c) * source.indexOf(b);
  }, 0);
  if (value === 0) {
    return target[0];
  }
  let valueTarg = '';
  while (value > 0) {
    valueTarg += target[value % target.length];
    value = Math.floor(value / target.length);
  }
  return valueTarg.split('').reverse().join('');
}
```
## __Experience__
Unfortunately, I didn't work a programmer, so **I don't have** experience in this area.
## __Education__
I graduated from BNTU and have a degree in **mechanical engineering**, and also underwent retraining at "Institute of retraining and advanced training BNTU" as a **programmer-web designer**. Then graduated from the online school "Netology", specializing in **SEO-optimization**.
## __English__
English is weak, but I'm learning it. The test, a link to which was given in the discord, **showed level A2+**.