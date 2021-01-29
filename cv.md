# Curiculum Vitae

### 1. Yauheni Smirnou (03.02.1998)
### 2. SmirnovEuV@gmail.com
### 3. Wannabe Front-end developer, medical university graduate.

  One of the most important skills that I got at the university are skills:  
  * to study,
  * to find the main thing in a lots of sources,
  * to find different needed information in the Internet,
  * non-standart vision of the situation and abillity to abstract

**My porpose** here is to get some skills to make some money using my brain properly. 
  
  I like getting new skills, open new hobbies, and also I'm interested in programming, so I think that I have great opportunities in IT.
  
### 4. Skills:
  
  * Learning JS with [learn.JS.ru](https://learn.javascript.ru/),
  * started solving tasks on [CodeWars](https://www.codewars.com/),
  * CSS & HTML basics (learned basics and created a few pages),
  * Git basics (from [GitHowTo.com](https://githowto.com/ru) and trained them with CSS & HTML tasks, RSS Q0 tasks),
  * Some Photoshop & Lightroom skills,
  
### 5. Code example:
  
  ```
    // write the function isAnagram

    function makeStandart(str) {
    str = String(str);
    str = str.toLowerCase();
    return str;
    }

    deleteCharAt = (word, index) => word.slice(0, index) + word.slice (index+1);

    var isAnagram = function(test, original) {
    let result = false;
    test = makeStandart(test);
    original = makeStandart(original);
    if (!(test.length === original.length)) {
        return result = false;
    };
    search: for (let i = test.length - 1; i >= 0; i--) {
        for (let j = 0; j <= original.length; j++) {
        if (test.charAt(i) === original.charAt(j)) {
            result = true;
            test = deleteCharAt(test, i);
            original = deleteCharAt(original, j);
            continue search;
        } else {
            result = false;
        };
        };
        if (result === false) break;
    };
    return result;
   };
  ```

### 6. Working experience:

  Have no any eperience in IT

### 7. Education:
  
  * [BSMU](https://www.bsmu.by/) graduate
  
### 8. English skills:
  
  **B1 Intermediate**
