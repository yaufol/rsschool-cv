# Ivan Savin

# Contacts

- Location: Tbilisi, Georgia

- Github: [yaufol](https://github.com/yaufol)

- Telegram: [yaufol](https://t.me/yaufol)

- Email: yaufol@gmail.com

# About me

Currently I work as an Experience Designer. I strive to create products that make life easier for end users and help businesses achieve their goals. I’m interested in simplifying complex corporate, industrial and scientific systems, as well as developing mobile applications for these systems. I have experience in the fields of medicine, financial technology and education.

# Skills

- HTML/CSS/JS

- PHP/MySQL

- UX/UI design, prototyping

- UX research

# Code example

A createTask method from an [educational To-Do project](https://github.com/yaufol/todo-list/blob/master/src/App.js) written in React.

```javascript
createTask() {
		if (this.state.draftTaskValue !== "") {
			this.setState(
				{
					tasks: this.state.tasks.concat({
						text: this.state.draftTaskValue,
						created: Date.now(),
						done: false
					}),
					draftTaskValue: "",
					Snackbar: {
						open: true,
						message: 'task "' + this.state.draftTaskValue + '" has been added'
					}
				},
				() => {
					this.saveChanges();
				}
			);
		} else {
			alert("the field is empty");
		}
	}
```

# Education

**The Ultimate Guide to Usability and UX 2019**

Udemy course

**Responsive Web Design 2018**
FreeCodeCamp course

**Moscow Aviation Institute (National Research University) 2015**

Aircraft design engineer

# Experience

I have created several tools for my own non-commercial use using following technologies: HTML, JS, CSS, MySQL, PHP.
As these projects are personal, they're not available publicly so I cannot provide links to repositories.

# Languages

## English
**C1.** Currently I work in an international team facing english on a daily basis.

## French
**A1.** 

## Russian
**Native** 