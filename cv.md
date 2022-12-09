# Raman Prudnikau 
![Raman](foto.jpg "foto")
---
### rs-school student 
### Contact information:
#### Phone: +48516454148 
#### E-mail:ramanprudnikau@gmail.com 
#### Discord: Raman_Pr(@RamanPr5)
#### GitHub: [RamanPr5](https://github.com/RamanPr5)

---
### Education:
* Vitebsk State Medical University (2011-2016)
* Pharmaceutical faculty
* Pharmacist (Provisor)
  
---
### Work experience
* Pharmacy manager, Pharmacy, Mogilev (2019-2022)
* Pharmacist, Pharmacy, Gorki (2016-2019)
 
---
### Skills:
* HTML
* Git, GitHub
* VS Code
  
---
### Code example
Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.
```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
---
### Courses
* RS Schools Course «JS/FE Pre-School 2022Q4» (in progress)
  
---
### Languages: 
* Russian: Native
* Belarussian: Native
* English: A1 (Elementary)


