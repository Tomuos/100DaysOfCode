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

![A beautiful landscape](https://slack-imgs.com/?c=1&o1=ro&url=https%3A%2F%2Fshots.codepen.io%2Ftomuo-burns-tinkler%2Fpen%2FWNgpEpN-800.jpg%3Fversion%3D1677705667)

- 📝 Tomorrow i'm a little torn i would like to complete code academy tasks before moving on to the next thing but Victoria got me thinking they revealed that they were making their own calculator. I'm not sure I would make that but it would be nice to do something like that. Magic 8 ball? Sources point to ..maybe.

### **Thoughts:**

Today was rough not for coding but from home life perspective. School strikes and a sick child were not a great 🤒 especially when it involves changing clothes of everyone involved twice and attempting to get a doctors appointment while you have a coughing fit a poor person on the end of the phone. Still if we ignore that ..... WHAT A GREAT ...EVENING it was. :D Really enjoyed the lecture from Liz

### **Links/resources:**

🔗https://codepen.io/tomuo-burns-tinkler<-- this is my codepen incase you are interested in seeing the little things i muck about making 💻

🎵https://open.spotify.com/track/09algRz68H2iEWhJQlYhqQ?si=88dc4efac7c54498 <-- Back to mine - Tycho(Bibio remix) I just needed to hear something to calm me after today lol what a day
