# Playlog

Playlog is a plain-text, barebones, story prototyping format that forces the writer to focus on the actual story rather than how it's told or how it looks, thus helping them avoid getting lost in evil, unnecessary details. The Fountain format is a big inspiration.

A document in this format is generally composed of three things:

* Information **about the story** like it's title or author
* **Scene information** like the time or place
* **Actions**, including dialogue

## First, an Example

Take a look at the following snippet example and try to guess what everything means before we move on. Just read it line by line.

```playlog
? Always Teenagers
? Season 1
? Episode 1: The Exam
? by Ghoom

? George will try different ways to postpone the math exam.

> Classroom
@ Morning
= George will fail to persuade Mrs. Johnson to postpone the math exam here.

* The classroom is huge.

Mrs. Johnson
	writing math stuff on whiteboard

* There is a red apple on the desk.

George
	raises hand
	
	[hesitantly] "Mrs. Johnson?"

...

Mrs. Johnson
	gives George a side-eye
	
	[apathetically] "Yes."
	
	faces George
	adjusts eyeglasses
	
	"George."

George
	about to speak

Mrs. Johnson
	[teasingly] "The exam will *not* be postponed, George." (This is my favorite part lol)

George
	stares at Mrs. Johnson in shock

Matilda
	quickly stands up

George and Matilda
	[desperately] "But, Mrs. Johnson-"

Mrs. Johnson
	gives George and Matilda the death stare

George
	looks down, eyes closed

Matilda
&	sits back down
	looks around in embarrassment

(to be continued)
```

## Alright, Time to Learn

### Abouts

Information about the story, or *abouts*, are preceded by a question mark (`?`).

```playlog
? Always Teenagers
? Season 1
? Episode 1: The Exam
? by Ghoom

? George will try different ways to postpone the math exam.
```

You can put anything in there. Doesn't have to be in this format or order.

Oh, and you can put abouts anywhere really. They don't have to be grouped up at the very top, but it's probably clearer that way.

### Scene Details

There are four types of scene details:

<ol>

<li>

**Places**, preceded by a right angle bracket (`>`):

```playlog
> Classroom
```

</li>

<li>

**Times**, preceded by an at sign (`@`):

```playlog
@ Morning
```

</li>

<li>

**Scene Summaries**, preceded by an equal sign (`=`):

```playlog
= George will fail to persuade Mrs. Johnson to postpone the math exam.
```

</li>

<li>

**Descriptions**, preceded by an asterisk (`*`):

```playlog
* The classroom is huge.
```

</li>

</ol>

### Activities

Activities are composed of a character's name and a list of actions.

```playlog
George
	raises hand
	
	[hesitantly] "Mrs. Johnson?"
```

They are indented under the character's name. The first type of action is a movement which starts with a verb and is written as is without special formatting. The second is a dialogue line, or simply *line*, which is enclosed in double quotes and is optionally preceded by a tone-indicating expression enclosed in brackets (`[]`).

When two or more characters do the same thing at the same time, you can simply list out their names like so:

```playlog
George and Matilda
	[desperately] "But, Mrs. Johnson-"
```

When a character does something at the same time as the previous action, no matter of which character, an ampersand (`&`) can be put before the indentation of the second character's action like so:

```playlog
George
	looks down, eyes closed

Matilda
&	sits back down
	looks around in shame
```

Any action without a preceding ampersand afer that, breaks the simultaneousness.

### Comments

Comments are enclosed in parentheses and are not part of the story.

```playlog
Mrs. Johnson
	[teasingly] "The exam will *not* be postponed, George." (This is my favorite part lol)
```

`(This is my favorite part lol)` is the comment here lol.

### Ellipsis

The ellipsis (`...`) can be used as a pause or lack of response.

```playlog
George
	raises hand
	
	[hesitantly] "Mrs. Johnson?"

...
```
