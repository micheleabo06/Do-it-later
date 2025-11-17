Do-it-later App

This is my first proper full-stack project for my portfolio.

It's a simple website to save links, articles, videos etc. that I find online, so I can read/watch them later and not have a million tabs open.

What does it do?

You can paste a link into the text box and save it and show all of your saved links in a list

You can mark a link as "read" (it greys out and gets a line through it).

You can delete links you don't need anymore.

How it works (What I used)

Frontend: HTML, CSS (Tailwind CSS) and  JavaScript.

Backend: I used Google Firebase for everything.

Firestore: This is the database where all the links are actually stored.

Firebase Auth: I used this for the user sign-in. It's set to "Anonymous" so anyone can use it, but their links are still saved just to their own account.

Key Feature: The list updates in real-time. I used the onSnapshot function from Firebase so that when you add or delete a link, the list just updates itself without needing to refresh the page.

How to run it

Can't run it with just the file as it has the firebase APIs so i hosted it on github pages:
https://micheleabo06.github.io/Do-it-later/

What I learned

This project was a huge learning experience, it really did help understand CSS and HTML. I have been studying Java for University and i found a few similarities between Java and JavaScript, however, they aren't the same. I learned how to connect a frontend to a real backend, how to use a NoSQL database (Firestore), (also haven't practiced SQL, that's why i decided to use this one, which was suggested by AI) and how to set up security rules so users can only see their own data. I also got a lot better at using Git and GitHub.