---
title: "SQL Quiz and drawing boxes and ASCII art with Boxes"
date: 2024-03-09T10:28:31-07:00
---
While taking my online course SQL for Data Science on Coursera, I really under estimated that the exams would be quite long with alot of queries. It was pretty painful to get my head thinking about how to write them and I was getting pretty impatient. 

However, writing these queries is getting me excited when I eventually learn how to write in Go and be able to connect my app with the database. 

Another thing I cant wait to do is to learn how to write HTMX.Eventually i want to write Go and HTMX and SQLite for all the things.

Finally, when I sat down to finally study SQL, I went down a rabbit hole and watched videos from the Primagine and wanted to re-learn how to draw ASCII art with a tool called Boxes. 
```
+------------------------------+
| "Pursue making how you feel  |
| align with reality           |
| as opposed to                |
| letting reality              |
| be aligned to how you feel." |
| -ThePrimeagen                |
+------------------------------+
```
I knew I had installed a application called Boxes that would draw out artwork for text, but I didnt know how to put it in Neovim. So I Googled around and eventually stumbled accross instructions wich were complete, but not workable if you already had text in a file. I finally figured it out after re-reading and thinking a bit outside the box: 

1. Install the app [Boxes](https://boxes.thomasjensen.com/) on your Linux computer
2. Open vim or neovim
3. write out your text or quote. 
4. Hit `esc`
5. Go into command mode and write the line number, example is line 12 where the quote starts: `12!boxes -d stone` or if you have multiple lines, visually select with `v` and then `:!boxes -d stone`
6. press enter to get it to print the box out.

So even though I didnt work much on SQL homework... I learned a bit more about Vim and way that can make my markdown notes spark job a bit more. 
