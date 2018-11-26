WebChat Client
===================

- - - - 
# Dependencies: #

1. `npm` and `nodejs` (generally `npm` comes along with `nodejs`). 
2. `rivescript-js` module. Use `npm` : `npm install rivescript` in the cloned rep. (see below steps to clone)

# Design # 

**Original Design**

![Original design](https://github.com/krshrimali/ChatBot-IIITNR/blob/master/ChatBot-Design.png)

# Steps: # 

1. Clone the repo: `git clone <url>`
2. Enter the dir : `cd ChatBot-IIITNR`
3. Install rivescript : `npm install`
4. Install http-server: `sudo npm install -g http-server`
5. Build              : `npm run dist`
6. Run http-server    : `http-server -p <port_number>`
7. Go to eg/web-client and click on chat.html

# To Do: #

1. Beautify (40% done)
    1. Add material theme (icons)
    2. Better fonts
    3. Logo
    4. Add more attractive background
2. Add database using bot.js in Learning (eg/learning) (? - not finalized)
3. Add more rive scripts
    1. Add answers for offensive rivescripts like suicide etc. (May be link to
motivational videos and music).
    2. Abusive rivescript handler
4. Scrolling (Bug)
5. Database (FAQs from Admissions)
6. Image IIIT NR + Navigation Menu + Contacts on right side [seamless]
7. Developer page Design


# Contributors: #

1. Krutika Bapat
2. Kushashwa Ravi Shrimali
3. Minakshee Shukla
4. Saurabh Kumar Singh
5. Shubham Yadav

# Meetings: #
**Meeting - 1. Wed. , 1st August : Discussion of the Project with client:**

1. Project Discussion:
    1. Topics discussed. Demos found.
    2. Is UI the priority? (Question) Mainly not. Because of IIIT NR's own website layout, it shouldn't be. ChatBot has to be kept simple and easy to load.
    3. Rivescript Module is the best find? Any better finds? - Rivescript is easy to install, data format is understandable. 
2. Client :
    1. Topic - Good.
    2. UI - Not priority. Use college's template.
    3. RiveScript - our choice. Should be open source & fast.

**Meeting - 2. Tuesday, 7th August : With Client.**

1. Client:
    1. UI - Add contact us, college image and menu.
    2. Prepare a sample admission chat bot. We'll deploy it and test it. Take data from FAQs on the website.
# Client: #

Abir Bhattacharya
(Senior Network Engineer)
