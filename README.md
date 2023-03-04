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

- 📝 Tomorrow i'm going to continue working on this in the hopes I figure out what I missed to get it up and running correctly.

### **Thoughts:**

Today was fun 😄 I feel like I got a fair bit done but there's still more to do and complete. I can do this maybe I just need some sleep in order to get there.

### **Links/resources:**

🔗 https://youtu.be/HQCLzqhiT2w <-- Tech2 etc -Build Simple Calculator With JavaScript HTML CSS | JavaScript Project

🎵 - https://open.spotify.com/track/2BAlPE15dKMXpB5Trutcak?si=cbd1f231b9db4e23 <-- Theme from Quantumania - Christopher Beck. Sooooo good I could listen to it on repeat infact I think I will.
