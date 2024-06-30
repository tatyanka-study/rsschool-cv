# Sazonko Tatyana 

![Sazonko Tatyana photo](images/sazonko-tatyana-frontend-developer2.jpg) 

### *Junior Frontend Developer*
---

#### My Contacts

**Phone:** +38 (097) 79 27 605
**Location:** Dnipro, Ukraine
**Email:** sazonko.tatyana@gmail.com
**LinkedIn:** [My LinkedIn](https://www.linkedin.com/in/tatyana-valchuk-19701a192/)
**GitHub:** [tatyanka-study](https://github.com/tatyanka-study)
**Discord:**[Tatyana](https://discordapp.com/users/tatyana_84061)


#### About Me
My main education is an Economist. I work as a leading economist in a large department. Since 2016, I have been studying part-time and working freelance as a front-end developer and for 7 months I was engaged in advertising on Google, Facebook and Instagram. I love when work requires and promotes the development of professional and personal skills.


#### Skills

- HTML5 + Emmet
- CSS3, CSS Grid, CSS Flex, LESS
- jQuery, Bootstrap
- CMS: WordPress, Tilda, Joomla
- JavaScript + DOM
- React
- Git, GitHub
- Photoshop, Figma
- SEO
- Google Ads, Google analytics
- Facebook, Instagram advertising


---
#### Code example

_**Exercise:**_
Write a script for "Guess the Number Game":
1. The essence of the game is to guess the number predicted by the script in fewer attempts.
2. Every time the player tries to guess a number, the script displays a hint - the script guessed a smaller or larger number.
3. The script guesses the number only once at the beginning of the game and this number does not change until the end of the game.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task 5</title>
</head>
<body>   
    <script>
        let randomValue = Math.floor(Math.random() * 101);
        let userNumber = 0;
        let count = 0;  

        do {           
            let userNumber = prompt("I thought of a random number from 0 to 100. Guess it");
            count++;

            if (isNaN(userNumber)) {
                alert("You did not enter a number. Be careful!");                    
            }
            else if (userNumber < randomValue) {
                alert(`I wished for a meaning greater than ${userNumber}`);
            }
            else if (userNumber > randomValue) {
                alert(`I guessed a value less than ${userNumber}`);
            }
            else{
                alert(`Right! Hidden meaning ${userNumber}. You guessed it in ${count} tries.`);
            }
        }
        while (userNumber !== randomValue);        
    </script>
</body>
</html>
```

---

### Professional Experience
- 2022 - 2023
   - several small applications when I was taking a Frontend course
- 2021
   - Facebook, Instagram advertising (freelance)
- 2016 – 2020
   - Creating sites (freelance)
   - Writing and creating sites on CMS, taking into account SEO requirements
- 2010 – 2011
   - Copywriting (freelance)
- 2010 – 2024
   - Economist
---

### Education
- **2024** 
      * RS School Course - _JS/FE Pre-School 2024Q2_
- **2022** 
      * During 2022, to update and deepen my previous knowledge, I passed Frontend course
- **2021** 
      * Different advertising courses
- **2020** 
      * DPRO FREE WORK - _сreating sites on CMS Tilda_
- **2016 - 2017** 
      * Computer Academy STEP -  _сreating and promotion of Web Projects_
- **2005-2010** 
      * Dnepropetrovsk National University named after O. Gonchar -  _specialty accounting and audit_
---

### Languages
1. English - Level B1
![EPAM Eenglish Level test result](images/EPAM-english-test-B1.png)
2. Ukrainian - native
3. Russian - proficiency