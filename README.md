dlang-latex-listings
====================

This file provides a language definition for highlighting D source code used in the lstlisting package for Latex.

How to use this, I don't know. I came from the answer over on tex exchange.

http://tex.stackexchange.com/questions/63496/how-to-add-go-to-the-programming-languages-list-in-lyx

What I can tell you is you can place the content of \lst@definelanguage into your latex decument inside a \lstdefinelanguage{D} {} block. Making use of it that way.

Then use \lstset to choose your language or any other options.
http://en.wikibooks.org/wiki/LaTeX/Packages/Listings
