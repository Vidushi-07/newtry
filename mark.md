# Chennaipy  
## Chennai Python User Group  

- [Events](#events)  
- [Meeting Minutes](#meeting-minutes)  
- [Credits](#credits)  
- [Team](#team)  
- [General Announcements](#general-announcements)  

---

## Meeting Minutes  

### Feb 2017 Meetup Minutes  

#### A Gentle Intro to Types by Shrayas Rajagopal  

**Shrayas Presenting his Talk**  

Shrayas started by building on the basics to introduce more advanced concepts later on.  

- **What are types?**  
  - Class of value  
  - Set of operations  

#### Why Types?  
- Humans make a lot of errors  
- Computers are very good at repeating things  
- Types help bring them together and reduce mistakes  

#### Type Systems  
- Think of them like **magic boxes**  
- They run through the source code  
- Check if the program makes sense given the set of operations (rules)  

#### Dynamic Typing vs Static Typing  
- General myth: static has types, dynamic means no types  
- Both actually have types  
- **Static languages** get to know about the type at compile time  
- **Dynamic languages** get to know about the type at runtime  
- Example: Errors caught at **compile time** in C# but undetected until **runtime** in Python  

#### Advantages and Disadvantages of Both  
Criteria considered:  
- Hackability (easy to get started)  
- Readability  
- Iteration speed  
- Enforces tests or not  
- Size of codebase  

#### Gradual Typing  
- Combines advantages of both static and dynamic typing  
- **Runtime fluidity marries compile-time rigidity**  
- Some languages/frameworks that support gradual typing:  
  - Hack  
  - TypeScript  
  - mypy  

#### Why Gradual Typing?  
- Rigidity  
- Better dev tools  
- Readability  
- Concise codebase  
- Possible to migrate your codebase to gradual typing in parts  

---

### GUI Using Python by Gaurav Sehrawat  

#### Basic Info  
- **tkinter** is a Python interface to Tcl/Tk  
- **Tcl/Tk** is cross-platform  
- **Tcl** is a dynamic language; **Tk** is an extension for GUI development  
- Uses native system APIs  
- Each GUI is a collection of **frames**; each frame has a **layout manager**  
- The **IDLE editor** is built using Tkinter  

#### Python 2 vs Python 3  
- Very easy to port Tkinter code (similar across both)  
- Differences: Letter casing, prefixes  

#### Geometry Manager (Layout Manager)  
- Specifies relations between elements  
- **Pack** (simple layout manager)  
- **Grid** (table-like layout)  

**When to Use Pack**  
- Simple geometry (up, down, etc.)  
- Side-by-side layout  
- Elements go on top of each other  
- For complex layouts, prefer **grid**  

#### Widget List  
- Labels  
- Buttons  
- Dialog Boxes  

#### Examples Shown  
- "Hello, World" program  
- Pack vs Grid  
- Events & bindings  
- Dialog boxes  

#### Matplotlib  
- **Matplotlib dynamic plots** using real-time data  

#### OpenCV  
- **OpenCV for image processing**  

---

### YAML Validation in Python by Vijay Kumar  

#### Basics  
- Different methods of representing data  
- Impact of representation  
- Benefits of **text representation**:  
  - Easy to create  
  - Easy to use with **Version Control Systems**  
  - Easy to review  

#### Types of Data  
- **Structured Data** (easy for computers, hard for humans)  
  - Example: Arrays, Databases  
- **Unstructured Data** (human-oriented, hard for machines)  
  - Example: Word Documents  
- **Semi-Structured Data** (easy for both humans & machines)  
  - Example: XML, JSON, YAML (requires parsing)  

#### YAML  
- **Superset of JSON**  
- Syntax and capabilities  
- Examples of using YAML for organizing **ChennaiPy**  

#### Roadblocks to Using YAML  
- **Human input prone to errors**  
- Proper validation is key  

#### Difficulties in YAML Validation  
- Writing verification code is **hard**  
- No built-in schema for YAML  
- Errors can be **cryptic**  

#### Solution: Using `jsonschema`  
- Validates YAML  
- Improves error checking  
- Provides friendlier prompts  

---

### Lightning Talk by Ashok Govindarajan  

#### Machine Learning Overview  
- Born out of **pattern recognition**  
- Mostly involves:  
  - **Curve fitting**  
  - **Adapting**  
  - **Predicting**  
  - **Recommending**  

#### Why the Sudden Rise in Machine Learning?  
- Been around for a long time  
- Sudden rise due to:  
  - **Faster hardware**  
  - **More storage**  
  - **Lots of good data sources**  
  - **Low-cost sensors**  

#### Role of Machine Learning  
- Precedes/enables **decision-making**  
- Helps transition from **intuition-based** to **data-driven** decisions  

---

## Credits  

- **Vijay Kumar** thanked **InkMonk** for sponsoring the venue  
- **Zilogic Systems** sponsored the projector  

---

## Group Photo  
![Group Photo](#)  

---

[Go Top](#)  

_Text is available under the **Creative Commons Attribution-ShareAlike License**. Built with **Pure Theme** for Pelican._  
