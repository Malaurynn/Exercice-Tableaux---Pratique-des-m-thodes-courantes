# Exercice-Tableaux---Pratique-des-m-thodes-courantes

const mysteriousString = `iu@zfiz)!uzqzf!snoi??alutargnocze&gfuzyafzygfzmgfu%f`;
console.log (mysteriousString);

const step1 = mysteriousString.split ('')
console.log(step1)

const step2 = mysteriousString.slice(15,31);
console.log(step2);

const step3 = step2.split('');
console.log(step3);

step3.splice(4,2, 't' );
console.log(step3); 

const step4 = step3.reverse();
console.log(step4);

const step5 = step4.join('');
console.log(step5);
