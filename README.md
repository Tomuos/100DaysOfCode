# 100 Days Of Code Journal / School of Code Bootcamp Journal

## Day 1

---

_Feb 26 2023_

### **Todays Progress:**

- 📚 I looked up info on markdown after looking at the brilliant diary kept by a former SOC student.

- 🖥️ I went back through my HTML and CSS code on the website I made and started adapting things to be more responsive.

- 📝 I'll have to go look up the command line info to connect to a new Repo I made so I can upload this Readme file but also so I can update this hopefully day by day.

### **Thoughts:**

💪 I'm lucky to have all these resources available, but I just hope I can use them to my full potential. I'm so happy to have been accepted into the School of Code. I want to do this 100 days of code challenge. It still feels daunting even if it's supposed to be an hour a day. Home life is about to change too with my youngest starting nursery. I will find the balance.

### **Links/resources:**

📺 https://youtu.be/Nj87GEXxhjc <-- Learning markdown in VS code

---

## Day 2

---

_Feb 27 2023_

### **Todays Progress:**

- 📚 I looked into creating a guide for myself for connecting to a repo again and then wrote it down in a word doc. As I had set up links for my previous repo but it had been a while still good to refresh on git inputs.

- 🖥️ I've more website stuff to check through before pushing to a branch before merging. I thought it better to keep my hand in with some Javascript work with codecademy today I had a go making classes that you use to make a new instance from. Here's a brief example:

```
class Surgeon {
constructor(name, department) {
this.name = name;
this.department = department;
}
}

const surgeonRomero = new Surgeon('Francisco Romero', 'Cardiovascular');

console.log(surgeonRomero);

const surgeonJackson = new Surgeon('Ruth Jackson', 'Orthopedics');

console.log(surgeonJackson);

Output was:

Output:
Surgeon { name: 'Francisco Romero', department: 'Cardiovascular' }
Surgeon { name: 'Ruth Jackson', department: 'Orthopedics' }
```

- 📝 I think I'll continue with more of this tomorrow I'd like to complete the intermediate JS stuff section as it's good to have a bit consistency before doing something else.

### **Thoughts:**

Today I felt a little daunted as I was trying to make sure I was consistent. Also had to make sure I'd done all that was required before starting SOC bootcamp. It's like a building anxiety and excitement. I really want to do well, I worry about things but then I continued reading all of the drop downs and when I found structure to the days that lay ahead I realised that everyone will be in the same boat. I can do this I just have to keep believing or maybe I need to listening to live to win 10 times and get pumped up. 🎶🔥

### **Links/resources:**

🎵 https://open.spotify.com/track/74inHQGjQj6w630tZ9wb2J?si=db20b619864b43bd <--Live to win by paul stanley. Just incase you need a bit of pep.💪

🔗https://www.codecademy.com <-- code academy is a great little resource i've signed up for premium thanks to some kind pals with 50% codes. still got some great free stuff

---

## Day 3

---

_Feb 28 2023_

### **Todays Progress:**

- 📚 I looked into more info on how to progress with coding most of the information was as I expected. **CONSISTENCY IS KEY**

- 🖥️ So today on code academy I continued with my tasks on Inheritence I managed tasks I, II, III they were all right but IV was a new hope. Seriously though it was strange to understand tomorrow task V strikes back. Here's a look at some of the code from todays task.

```
class HospitalEmployee {
  constructor(name) {
    this._name = name;
    this._remainingVacationDays = 20;
  }

  get name() {
    return this._name;
  }

  get remainingVacationDays() {
    return this._remainingVacationDays;
  }

  takeVacationDays(daysOff) {
    this._remainingVacationDays -= daysOff;
  }
}

class Nurse extends HospitalEmployee {
  constructor(name, certifications) {
    super(name);
    this._certifications = certifications;
  }
}

const nurseOlynyk = new Nurse('Olynyk', ['Trauma','Pediatrics']);
nurseOlynyk.takeVacationDays(5);
console.log(nurseOlynyk.remainingVacationDays);

Output to the log

15

```

- 📝 Tomorrow more code academy but I think I might have a look into some html and css work one thing I would love to have ago at is parallax scrolling animation. I have some pre made images from my batman website I never got round to trying.

### **Thoughts:**

Today was juggling act between home life and getting this done but I will keep moving forward. I feel like I need to try new things inbetween coding exercises just to give myself a break from things. :smile:

### **Links/resources:**

🔗 https://www.codecademy.com/ <-- same as day 2 💻

🎵https://open.spotify.com/episode/1fkJjlkkMHhaqckaoNMbnK?si=9230d5eac9a44ea7
<-- beta wave improve for conertration💡

🎵https://open.spotify.com/track/7lRsKDo94Xy3y1uqash1Xv?si=374ce79d9bc44ebf <-- for something after you beat that 1hr mark 🔥

---

## Day 4

---

_Mar 1 2023_

### **Todays Progress:**

- 📚 Today was the pre-lecture to SCHOOL OF CODE(SOC) we did a some work on notepad....it was fun but also painful. I was paired up with someone called Victoria hopefully they will recover from the shock of working with me. In truth it wasn't that bad it was nice to meet people and chat to someone new who isn't a 5 or 2 year old.

- 🖥️ So today I decided to continue with the practice of making something from scratch even if it is very very simple. It was to do with our brief conversation on stained glass windows.

![A picture of the barebones website](https://slack-imgs.com/?c=1&o1=ro&url=https%3A%2F%2Fshots.codepen.io%2Ftomuo-burns-tinkler%2Fpen%2FWNgpEpN-800.jpg%3Fversion%3D1677705667)

- 📝 Tomorrow i'm a little torn i would like to complete code academy tasks before moving on to the next thing but Victoria got me thinking they revealed that they were making their own calculator. I'm not sure I would make that but it would be nice to do something like that. Magic 8 ball? Sources point to ..maybe.

### **Thoughts:**

Today was rough not for coding but from home life perspective. School strikes and a sick child were not a great 🤒 especially when it involves changing clothes of everyone involved twice and attempting to get a doctors appointment while you have a coughing fit a poor person on the end of the phone. Still if we ignore that ..... WHAT A GREAT ...EVENING it was. :D Really enjoyed the lecture from Liz

### **Links/resources:**

🔗https://codepen.io/tomuo-burns-tinkler<-- this is my codepen incase you are interested in seeing the little things i muck about making 💻

🎵https://open.spotify.com/track/09algRz68H2iEWhJQlYhqQ?si=88dc4efac7c54498 <-- Back to mine - Tycho(Bibio remix) I just needed to hear something to calm me after today lol what a day

---

## Day 5

---

_Mar 2 2023_

### **Todays Progress:**

- 📚 Today I wasn't sure where to start till someone else got stuck on something.

- 🖥️ I decided to actually have a look into how to make a calculator in Javascript because the person I was paired with was struggling with something. I'm unsure if i can help but i'll try so I managed the basics following a tutorial but i'll need to do more work on it. Heres the html it's not the most pretty looking thing but it's a start. I might have to look up more info for these things.

```
<!DOCTYPE html>
<html>
  <head>
    <title>Calculator</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
  </head>
  <body>
    <div id="calculator">
      <div id="numbers">
        <button type="button" onclick="appendToDisplay('1')">1</button>
        <button type="button" onclick="appendToDisplay('2')">2</button>
        <button type="button" onclick="appendToDisplay('3')">3</button>
        <button type="button" onclick="appendToDisplay('4')">4</button>
        <button type="button" onclick="appendToDisplay('5')">5</button>
        <button type="button" onclick="appendToDisplay('6')">6</button>
        <button type="button" onclick="appendToDisplay('7')">7</button>
        <button type="button" onclick="appendToDisplay('8')">8</button>
        <button type="button" onclick="appendToDisplay('9')">9</button>
        <button type="button" onclick="appendToDisplay('0')">0</button>
        <button type="button" onclick="appendToDisplay('.')">.</button>
        <button type="button" class="operator" onclick="clearDisplay()">
          C
        </button>
      </div>
      <div id="operators">
        <button type="button" class="operator" onclick="appendToDisplay('%')">
          %
        </button>
        <button type="button" class="operator" onclick="appendToDisplay('/')">
          /
        </button>
        <button type="button" class="operator" onclick="appendToDisplay('*')">
          *
        </button>
        <button type="button" class="operator" onclick="appendToDisplay('-')">
          -
        </button>
        <button type="button" class="operator" onclick="appendToDisplay('+')">
          +
        </button>
        <button type="button" class="operator" onclick="calculate()">=</button>
      </div>
    </div>
    <input type="text" id="display" />
    <script src="javascript.js"></script>
  </body>
</html>

```

- 📝 Tomorrow i'm going to continue working on this thing and maybe see if there are more in depth tutorials on how to do this. I'm still not sure what I'm doing though.

### **Thoughts:**

Family life can affect a lot of things and i'm trying to work out the new way to get the balance right. Taking breaks is important at work as well as out of work. I think I have to find a way to thank my partner for allowing me to do this course. She is precious to me. So today working on things again were difficult but for different reasons. Lets see what tomorrow brings.

### **Links/resources:**

🔗 https://codeburst.io/making-a-calculator-with-basic-html-css-and-javascript-part-1-1e4288f0bea1 this is where i started but I will probably be looking elsewhere for more help.

🎵 - no tunes tonight ha tomorrow I promise

---

## Day 6

---

_Mar 3 2023_

### **Todays Progress:**

- 📚 Today I went back through the very basic looking calculator and decided that I need to look for a better tutorial so after contacting my pal about what tutorial they used I was sent a link I started over.

- 🖥️ I got much further with this tutorial in a shorter amount of time but just like most video tutorials you follow along as quickly as you can but it doesn't always go to plan. I got a better result on the build but when it came to displaying the inputs i was getting nothing. I will have to start from the beginning and check through the files to make sure nothing is missing.

![A picture of calculator](images/Calculator%20attempt.png)

- 📝 Tomorrow i'm going to continue working on this in the hopes I figure out what I missed to get it up and running correctly.

### **Thoughts:**

Today was fun 😄 I feel like I got a fair bit done but there's still more to do and complete. I can do this maybe I just need some sleep in order to get there.

### **Links/resources:**

🔗 https://youtu.be/HQCLzqhiT2w <-- Tech2 etc -Build Simple Calculator With JavaScript HTML CSS | JavaScript Project

🎵 - https://open.spotify.com/track/2BAlPE15dKMXpB5Trutcak?si=cbd1f231b9db4e23 <-- Theme from Quantumania - Christophe Beck. Sooooo good I could listen to it on repeat infact I think I will.

---

## Day 7

---

_Mar 4 2023_

### **Todays Progress:**

- 📚 I was having trouble getting things to show up on the calculator but i worked out what i'd missed and got it working.sadly in the end certain fuctions wouldn't work. So I started again with a new tutorial

- 🖥️ I managed to get the bare bones done on the new calculator design. There is still plenty to do though. Its nothing more than a picture with a hover feature on the buttons.

![A picture of calculator](images/new%20calculator.png)

- 📝 Tomorrow i'll be making this thing functional. It's not been easy getting anthing working lately.

### **Thoughts:**

Not a bad one today just a busy weekend day with the family so a little tricky finding time on my own. This tutorial seems bit clearer than the previous one when with explainations as to why things are done in certain ways.

### **Links/resources:**

🔗 https://youtu.be/j59qQ7YWLxw <-- Web Dev Simplified calculator tutorial

🎵 - https://open.spotify.com/track/3uUuGVFu1V7jTQL60S1r8z?si=3a954bc20d714fb1 <-- Where are you now - Lost Frequencies, Calum Scott. Not probably a bit of an earworm

---

## Day 8

---

_Mar 5 2023_

### **Todays Progress:**

- 📚 This new tutorial is better but it is not without some confusing information as the tutor seems to have a completed version of his calculator which occasionally he uses to show what should happen. This felt counter productive as I kept thinking i'd failed when it wasn't happening only to find out later that I hadn't actually called anything yet for it to function. Still this is progress.

- 🖥️ I got a calculator working and then following the instructions of the tutor promptly broke it again haha 😂 i'm sure I can get it working better though. An image before the destruction

<div>

<p align="center">
  <img src="images/meaning%20of%20life%20calculator.png" alt="A picture of calculator">
</p>
</div>

- 📝 Tomorrow i'll keep going see if I can beat this before the 10 day mark and hopefully i'll get some Code wars in.

### **Thoughts:**

Not bad just tired from the day. I got further than i expected. I've an early start tomorrow so I'll have to leave this here again for another day.

### **Links/resources:**

🔗 https://youtu.be/j59qQ7YWLxw <-- Web Dev Simplified calculator tutorial

🎵 - https://open.spotify.com/episode/4G9geVUuuWwCLoULRbnSIS?si=6a38911680744fb5 <-- Howl's flower field - Studio ghibli relaxing ambience - by nature sound to relax 🌸, for those who might be fans of Howls Moving Castle and Nature I guess.

---

## Day 9

---

_Mar 6 2023_

### **Todays Progress:**

- 📚 I changed it up tonight I will probably finish the calculator tomorrow he writes with confidence.... Tonight I tried my hand at code wars and succeed but I did have to search various methods for producing what i wanted. I learned about split which can take information and break it into individual parts placing it all in an array.

- 🖥️ So the challenge was to take Troll messages and remove the vowels from them in order to make there messages unreadable.

```
function disemvowel(str) {
  // defining the vowels
  const vowels = 'aeiouAEIOU';

  // trollString takes a string(str) then uses split
  const trollString = str.split('').filter(char => !vowels.includes(char)).join('');

  // returning the new string without vowels
  return trollString;
}

console.log(disemvowel("This website is for losers LOL!"));
console.log(disemvowel("No offense but,\nYour writing is among the worst I've ever read"));
console.log(disemvowel("What are you, a communist?"));
```

```
Logs

Ths wbst s fr lsrs LL!
N ffns bt,
Yr wrtng s mng th wrst 'v vr rd
Wht r y,  cmmnst?
```

- 📝 Tomorrow I'll finish the calculator and maybe begin my next coding challenge

### **Thoughts:**

Today I'm tired but happy, hopefully I can get more done tomorrow. I didn't get as much as I would have liked to have done today but... I did something at least 😊

### **Links/resources:**

🔗 https://www.codewars.com/kata/52fba66badcd10859f00097e/train/javascript <-- code wars challenge

🎵 - https://open.spotify.com/track/6zumS30r4xE6o8gZTip0Lc?si=46974bb060cd4a50 <-- Rising Sun - by Aberdeen just something pleasant to listen to.🎧

---

## Day 10

---

_Mar 7 2023_

### **Todays Progress:**

- 📚 Today I did way more than I expected. I had at creating drums kit on keyboard. I did something on freecodecamp "Iterate Through the Keys of an Object with a for...in Statement" which was to run a loop through an object for looking for true of false values. I finished the calculator which I was surprised about too. I even added an extra function which were keyboard inputs.

- 🖥️ It's been a good day! I FINISHED THE CALCULATOR...and i added extra keyboard inputs i know i said that already but i didn't expect to get it done today. I also managed to do a loop through an object. My examples:

```
const users = {
  Alan: {
    online: false
  },
  Jeff: {
    online: true
  },
  Sarah: {
    online: false
  }
}

function countOnline(usersObj) {
  // Only change code below this line
let onlineUsers = 0;

for(let user in usersObj){

  if(usersObj[user]["online"] === true){
    onlineUsers += 1;
  }
}

return onlineUsers;

  // Only change code above this line
}
```

```
Logs

// running tests
// tests completed
// console output
1
```

<a href='https://codepen.io/tomuo-burns-tinkler/pen/bGxRWMp'><img src="images/finished calculator.png"></a>

- 📝 Tomorrow I'll try to continue with free code camp for some more javascript and possibly some more advanced HTML and CSS.

### **Thoughts:**

Great day today😊 felt very productive got a fair few things done. I want to keep going see what I can push myself to do. 🐱‍🐉 Probably keep it small before trying anything too time consuming and having to bother people for answers 😀

### **Links/resources:**

🔗 https://codepen.io/tomuo-burns-tinkler/pen/bGxRWMp <-- codepen link again

🔗 https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/ basic-data-structures/iterate-through-the-keys-of-an-object-with-a-for---in-statement <-- The freecodecamp task

🔗 https://javascript30.com/ <-- 30 days of javascript tasks kinda fun but best to know some fundamentals

🎵 https://open.spotify.com/album/49i6QxFHTMt4e9aopUO8pm?si=5d722uy2QYOxm0B8_iaQ4Q <-- Frogged & Loaded - by Pete Frogs game covers that sound fantastic.🎧

---

## Day 11

---

_Mar 8 2023_

### **Todays Progress:**

- 📚 Today I watched some shorts by a Youtuber called Hyperplexed they.... are on another level. Decided to go back through javascript fundamentals as there were things that thought i should have been able to do in my Codewars challenge but I couldn't remember how to do it.

- 🖥️ So I went through some of his tutorials with Hyperplexed I made a hacker effect which was interesting my one working example:

<p align="center"><img src="images/demo%20gif.gif"alt="Demo of the hacker effect"></p>

I'm also trying a few other Hyperplexed tutorials out though why not.

- 📝 Tomorrow when I get a chance I think I will finish any current things i'm working on and then start focusing back on Javascript fundamentals.

### **Thoughts:**

Not a bad day, nice to try things out and see if you can replicate and adapt them for other purposes. Had the Bootcamp Social today. I became the team captain, we called out selves the Partners In Crime. We took part in a quiz sadly we didn't place but what can you do.
I feel like I need to focus more on the JS side of things. When i've tried to build things on my own i do get stuck quite quickly and find myself looking for answers elsewhere.

### **Links/resources:**

🔗 https://codepen.io/tomuo-burns-tinkler/full/oNPGyKM <-- codepen link again

🔗 https://www.youtube.com/@Hyperplexed <-- if you want something nice and quick to ponder over give Hyperplexed a look at.

🎵 https://open.spotify.com/artist/1T7zBkQCOCacKjbnmFX7cp?si=a8mIvqHlRvaM0Bfl3l_1yA.🎧 <-- more gaming music tonight what can I say.

---

## Day 12

---

_Mar 9 2023_

### **Todays Progress:**

- 📚 Today I was more of a research day, looking into various collections for creating and learning code.

- 🖥️ Codewars is the thing I got stuck multiple times today but got two done with a lot of looking things up. Here's one Challenge

**Convert number to reversed array of digits**

```
function digitize(n) {
  // turns numbers into a string then splits them into an array of numbers
  const digits = String(n).split('');
  // takes the array of strings, reverses it then map converts them back into array of numbers
  return digits.reverse().map(Number);
}


console.log(digitize(35231)); // Output: [1, 3, 2, 5, 3]
console.log(digitize(0));     // Output: [0]
console.log(digitize(12345)); // Output: [5, 4, 3, 2, 1]

```

- 📝 Tomorrow maybe it will be more fruitful

### **Thoughts:**

Certain things today were out of my hands we lost two beloved rabbits to a fox in the night. So there was plenty of distractions on the mind and self blame. Tomorrow I'm sure will bare more fruit.

### **Links/resources:**

🔗 https://javascript.info/ <-- great javascript reference material

🔗 https://apps.ankiweb.net/ <-- if you want digital flash cards this is the place to make them

🎵 https://open.spotify.com/artist/7LbEDjJKrmWoMcN3OpaNnR?si=B4ihaikvR9y1Z1WViQkCwQ🎧 <-- Dramatic film scores by Daniel Pemberton

---

## Day 13

---

_Mar 11 2023_

### **Todays Progress:**

- 📚 Today a comedy of errors, I decided to look into mdn stuff and found a 2D javascript Brick Breaker/ Breakout game

- 🖥️ Somethings went wrong but I started again and either way I have the start of a canvas with some shapes on it but it's just the start.

<p align="center"><img src="images/Brick breaker.png"alt="Demo of the hacker effect"></p>

- 📝 Tomorrow I will try and get much further hopefully have something to show on here.

### **Thoughts:**

This might be a short look at this game as I will finally starting SCHOOL OF CODE on Monday. Unfortunately my usb was snapped by one of my children lucky I had a backup. Very tired today carried over from yesterday where I got nothing much done.

### **Links/resources:**

🔗https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript <-- great javascript reference material

🎵 https://open.spotify.com/track/2sifRHahNmhTR7a3BjKc9u?si=e12c817d9a1d408c🎧 <-- Timebomb Zone by The Prodigy if you want something to keep you awake these guys do the trick

---

## Day 14

---

_Mar 13 2023_

### **Todays Progress:**

- 📚 It's been a long day, I've started SCHOOL OF CODE! so today was a lot of new experiences. We did some CSS diner work something new that I need to learn.

- 🖥️ we worked in teams to make instruct each other to get the answers. We didn't finish all 32 but i did on my own.

<p align="center"><img src="images/css diner.png"alt="Demo of the hacker effect"></p>

- 📝 It a new start with SOC so if there is something i need to work on it may affect my choice in work

### **Thoughts:**

Today was fantastic, I got meet a lot of new people. It does mean i will have to put in a fair bit of effort now in order to make life easier later.

### **Links/resources:**

🔗https://flukeout.github.io/ <-- CSS Diner

🎵 https://www.audible.co.uk/pd/Age-of-Stone-Audiobook/1666111228?action_code=ASSGB149080119000H&share_location=pdp 🎧 <-- Audio book tonight Age of stone Jez Cajiao

---

## Day 15

---

_Mar 14 2023_

### **Todays Progress:**

- 📚 Today was one step forward and two steps back, used flow charts today to define the working of a graduation then we had to do the same for a login screen on scratch which seemed simple in flow but not simple in scratch. It got very confusing when I couldn't figure out a way to loop back on incorrect username and passwords. Almost had it working. I managed to get git sorted at least so I pulled from the repo and sent through a change.

- 🖥️ We worked in pairs today which was nice although there were a few hiccups at the start. So I paired up with someone else for most of the morning but in the afternoon I was back with my intended partner.

<p align="center"><img src="images/tintintin.png"alt="Demo of the hacker effect"></p>

- 📝 I did this as it was something we didn't get to finish as much as we wanted to. Sometimes there's not enough hours in the day.

### **Thoughts:**

I guess the only way was down from yesterday ha, well let's just say it didn't quite go the way I hoped today. I need to get out my own way sometimes. Just go for the easiest way to complete a task rather than worry about is it fair to google to answer a puzzle. It's fine if it's for SOC it's not if it's down the local pub quiz. I think some day's will be like this others might be easier all we can do is our best.

### **Links/resources:**

🔗<-- no links today

🎵 https://www.audible.co.uk/pd/Age-of-Stone-Audiobook/1666111228?action_code=ASSGB149080119000H&share_location=pdp 🎧 <-- Audio book tonight Age of stone Jez Cajiao

---

## Day 16

---

_Mar 15 2023_

### **Todays Progress:**

- 📚 Today was learning basics but it was still not easy and I think I need to simplify my thinking

- 🖥️ worked with some of the teammates we did bits back and forth making sure code worked on each other screens. It was a lot of screen sharing but I think it's important. This was one of the tasks we had to do which was adding a password checker prompt.

### Task E

```
function authenticateUser() {
  let pwd = "myPassword1!";
  let attempts = 0;
  let maxAttempts = 3;

  while (attempts < maxAttempts) {
    let getPwd = prompt("Please enter password.");
    if (getPwd === pwd) {
      console.log("My favourite colour is #000080!");
      alert("It was Rolo Tomazee");
      return true; // return true if password is correct
    } else {
      attempts++;
      alert(`Incorrect password. ${maxAttempts - attempts} attempts left`);
    }
  }

  return false; // return false if too many attempts
}

let isLoggedIn = authenticateUser();

if (isLoggedIn) {
  // reveal secret information here
} else {
  alert("ACCESS DENIED");
}

```

- 📝 We caught up with things today although some of the work we put in didn't quite go the way we expected.

### **Thoughts:**

I won't say today was easy but somethings made sense but I'm still not sure I understand what I'm doing. I just hope I'm on the right track. I'm glad I had someone watching me put things together they help keep you from making mistakes when you are too close to the code.

### **Links/resources:**

🔗<-- no links today maybe when things calm down a bit ha

🎵 https://www.audible.co.uk/pd/Age-of-Stone-Audiobook/1666111228?action_code=ASSGB149080119000H&share_location=pdp 🎧 <-- Audio book tonight Age of stone Jez Cajiao

---

## Day 17

---

_Mar 16 2023_

### **Todays Progress:**

- 📚 Today we went deep into variables and learned the differences between them or at I think we did, Var = function scoped, const is usually for unchangeable code and its block scoped and let allows you to change things and is also block scoped. We also did a session on Arrays[] the many things you can put in them. We also looked into how to iterate through them and also Arrays["within arrays"]; or even [ {}, {}, {}, {}, {}, {}] objects in arrays. 

- 🖥️ we did a lot of work between us the only thing we are struggling with seems to be pushing and pulling from github. We thought it best to just work through the tasks together and then think about pushing them back at a later time. 

### here's one of my favorite tasks from today given an array add "t" to the end of each item. 

```
let words = ["ben", "ha", "spla", "fa", "ca", "dra"];

for (let i = 0; i < words.length; i++) {
  words[i] += "t";
}

console.log(words);

output

['bent', 'hat', 'splat', 'fat', 'cat', 'drat']

```

- 📝 We caught up with things today although some of the work we put in didn't quite go the way we expected.

### **Thoughts:**

I felt as a team we connected with the material and the teaching so much more than in the previous lesson. It feels like we have mini breakthroughs followed by stumpers again. I enjoyed today it was great and not feeling like we have to catch up with everything was even better. I think we still have to work on pushing and pulling in Github. 

### **Links/resources:**

🔗<-- no links today maybe when things calm down a bit ha

🎵 https://www.audible.co.uk/pd/Age-of-Stone-Audiobook/1666111228?action_code=ASSGB149080119000H&share_location=pdp 🎧 <-- Audio book tonight Age of stone Jez Cajiao

---

## Day 18

---

_Mar 17 2023_

### **Todays Progress:**

- 📚 Today was our first Hackathon my partner was great at keeping my thoughts in check today. We managed to get a lot done and we managed to do a little bit of git work. In the hackathon we had to make a Rock Paper Scissors game.  

- 🖥️  It was a fun day glad I got do something a little different I remembered things I'd done before in past tutorial videos and with my work partner giving great suggestions and noticing things that i misspelt (sissors) or noticing that something wasn't working in testing. Then things just started working and just as we started to get going it was time to check out other groups work and let them offer a take on your work. We all helped figure out a looping issue. Then it was time to get ready for the weekend.

### here's the game so far. 

```
function getWinner(playerMove, computerMove) {
    if(playerMove === computerMove){
        return 0;
    // console.log("It's a draw");
}else if((playerMove === "rock" && computerMove === "scissors")||
(playerMove === "scissors" && computerMove === "paper")||
(playerMove === "paper" && computerMove === "rock")){
    return 1;
    // console.log("You win!");   
}
 
else{
    return -1;
    // console.log("Computer wins!");

}
  }
  

  function getRandomMove(){
    const choices = ["rock", "paper", "scissors"]
    let randomChoice = (Math.random() * choices.length);
    return choices[randomChoice]; // returns array after it's been put through the randomChoice.
  }
 

// takes players input 
let playerMove = prompt("Enter choice rock, paper or scissors");
let computerMove = getRandomMove();
// player input vs computer 

let result = getWinner(playerMove, computerMove);

if(result === 1){
  alert("You Win!");
}else if(result === 0){
  alert("It's a Draw!");
}else{
  alert("You Lose!");
}

```

- 📝 I think I'll continue trying to do all the tasks for this hackathon it should be good practice.

### **Thoughts:**

I think this week has been intense but also amazing it's really great because I didn't expect to actually understand anything yet. Still plenty to learn.

### **Links/resources:**

🔗<-- no links today maybe when things calm down a bit ha

🎵 https://www.audible.co.uk/pd/Age-of-Stone-Audiobook/1666111228?action_code=ASSGB149080119000H&share_location=pdp 🎧 <-- Audio book tonight Age of stone Jez Cajiao


---

## Day 19

---

_Mar 18 2023_

### **Todays Progress:**

- 📚 Following off the back of a hackathon one of my cohorts suggested they would try and make a playable version of rock paper scissors in Html well i wanted to try that too granted I hadn't completed all my tasks from the hackathon but still. 

- 🖥️  I took my latest version of functions but I had to get rid of a lot of things to replace them with for use with html but as i wasn't sure how to do it found a handy Youtube video by Ania Kubow. 


### here's the game so far I even added the variants for the end of the game.  


![The code and preview of the game](images/Printscreen%20of%20RPS%20game.png)



- 📝 Hopefully tomorrow I can get some more cementing in of various coding practices and more programming knowledge. I need to push myself more.  

### **Thoughts:**

I think i'm happy with the small test I did and it was odd following a tutorial but replacing all the parts to suit my previously existing coding. Somethings didn't quite work at first but I got something working and I'm happy I added Math.floor(Math.random () * choices.length); So I could add the lizard and spock. 

### **Links/resources:**

🔗https://youtu.be/RwFeg0cEZvQ<-- Ania Kubow is a fantastic programmer I need to do more of her tutorials.

🎵 https://www.audible.co.uk/pd/Age-of-Stone-Audiobook/1666111228?action_code=ASSGB149080119000H&share_location=pdp 🎧 <-- Audio book tonight Age of stone Jez Cajiao

---

## Day 20

---

_Mar 19 2023_

### **Todays Progress:**

- 📚 So today I started the day will a catch up with other cohorts looking to keep going through the basics it was good. I think I'd forgotten quite a few things. Nice meeting people again though some new some i just hadn't spoken to yet. 

- 🖥️ I went back through some of my unfinished tasks from week one. I'll probably have to go back through some more and maybe as things will become easier.

### here's the task 6 arrays work I rejigged

```
const friend = [ "Chris", "Lizzie", "Ben", "Tao", "Liz", "Patrick", "Tim", "James", "Joseph", "Max",];

function randomFriend() {
  const friendArr = Math.floor(Math.random() * friend.length);
  return friend[friendArr];
}
const myFriend = randomFriend();
console.log(myFriend);

output will be a random name in the friend array. tried it twice and got Ben and Chris

```
I also did 3 code wars for practice today 

here one of them is

```
  
function min(num){
    return Math.min.apply(null, num);
   
}

function max(num) {
    return Math.max.apply(null, num);
    
  
}

const arr1 = [4,6,2,1,9,63,-134,566]; 
const arr2 = [-52, 56, 30, 29, -54, 0, -110];
const arr3 = [42, 54, 65, 87, 0];
const arr4 = [5];

console.log(max(arr1)); 
console.log(min(arr2));
console.log(max(arr3)); 
console.log(min(arr4));
console.log(max(arr4));

```
```
output Log
566 (max)
-110 (min)
87 (max)
5 (min)
5 (max)

```




- 📝 Tomorrow will be the beginning of a new set of challenges and probably a new partner to get used to. I hope I don't fall behind but I look forward to seeing what comes next. 

### **Thoughts:**

I will have to finish a lot more of my tasks and upload them to github while i'm at it. It's much harder to do work on weekends though.

### **Links/resources:**

🔗<-- less links again today

🎵 https://open.spotify.com/track/4VkEkljlOC5cMbRMhREO5E?si=a0a8ce0c8f7b468d🎧 <-- Snowfall(slowed + Reverb) - Oneheart just an earworm of a listen. 

---

## Day 21

---

_Mar 20 2023_

### **Todays Progress:**

- 📚 The start of week 2. Was a little rough hopefully things will improve through the week nothing goes off without a hitch. Might have to sort out all of my Git stuff this week if I can. DOM manipulation was the key this week. New partners seem to have a better grip on things than I do currently but it's early days.

- 🖥️ I did a some code wars today, we also tried to do some focus on manipulation of the DOM 

### here's the one of the codewars from tonight

```
function reverseWords(str) {
    return str.split("").reverse().join("").split(" ").reverse().join(" ")
    
}

console.log(reverseWords("The quick brown fox jumps over the lazy dog."));
Output ehT kciuq nworb xof spmuj revo eht yzal .god

```



- 📝 Tomorrow I hope will be an improvement on today. I have a feeling every week will be a bit like this where I feel a bit out of my depth. I hope to pull my weight tomorrow when working in a team of three. I feel a bit like the weak link currently. 

### **Thoughts:**

Hopefully tomorrow people will be a bit more talkative. New pair of people are rather quiet which makes it hard to communicate. I may have to get used to the way they do things. 

### **Links/resources:**

🔗 https://www.codewars.com/<-- less links again today

🎵 https://open.spotify.com/track/1Q1onoQM04M590VO7aLOyt?si=a64c037d4f364c1b🎧 <-- Nujabes, The Champloo  
---

## Day 22

---

_Mar 21 2023_

### **Todays Progress:**

- 📚 Much better day today got to meet people who work in the industry. Teamwork was much better today got to help a teammate make a pokemon version of rock paper scissors. We had some fun making things today learning to create helpful comments that explain what the code does

- 🖥️ More DOM manipulation today, working with eventListeners. we did a codewars in the morning.

###  Here's some the tasks we did today


```
/////////////////////////////// Task 1

// variable button connected to the button id #click-me
const button = document.querySelector("#click-me"); 

  // This function logs a few messages and changes the label on the button
function handleClick(event) {
  // If clicked, console log you clicked me!
  console.log("You clicked me!");
  // If shift key pressed, change the inner text of the button to be NAILED IT.
  if(event.shiftKey === true){
    const clickMe = document.querySelector("#click-me");
    clickMe.textContent = "NAILED IT!!";
  }
  console.log(handleClick);
}

/////////////////////////////// Task 2

// flowerButton variable assigned to the class of task-2
let flowerButton = document.querySelector (".task-2");

// 
function flowerTitle (e) {
  document.title = "💐🌷🌼";
}
flowerButton.addEventListener("click",flowerTitle);

button.addEventListener("click", handleClick);

document.querySelector("#title-changer").addEventListener("keyup", (e) => {
  console.log(e.target.value);
});

/////////////////////////////// Task 3

let titleChanger = document.querySelector
(`#title-changer`)
let h1 = document.querySelector("h1");

function findValue (event) {
  h1.textContent = event.target.value;
} 
titleChanger.addEventListener("keyup", findValue) 

/////////////////////////////// Task 4
//variable of image
const img = document.querySelector("img");

// function that changes the h1 colour to hotpink
function hotpink(){
 const h1= document.querySelector("h1"); 
  h1.style.color = "hotpink";   
}

//function that changes back to the original colour
function initial() {
  const h1= document.querySelector("h1");
  h1.style.color = "initial";
}

//img with a listeners for mouseenter and mouseleave so when you put your mouse on the img
img.addEventListener("mouseenter", hotpink);
img.addEventListener("mouseleave", initial);

```

- 📝 Tomorrow I'm sure will be a new day but I hope the group will be chatty again and that we can keep the work tasks up too.  

### **Thoughts:**

So much better today, everyone was a bit more chatty which meant we started to get stuff done as a team which was very helpful. Have to try and keep this all going for the rest of the week. I'm going back through the previous weeks work to make sure everything is done. 

### **Links/resources:**

🔗 https://www.codewars.com/<-- might just leave this link here forever as its not a daily ritual

🎵 https://open.spotify.com/track/1Q1onoQM04M590VO7aLOyt?si=a64c037d4f364c1b🎧 <-- Nujabes, The Champloo  
