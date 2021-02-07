<div align="center">
<h1 align="center">NotesBuddy</h1>

[![License](https://img.shields.io/github/license/DhawalKhapre/NotesBuddy?color=blue&logo=git)](https://github.com/DhawalKhapre/NotesBuddy/blob/main/LICENSE)
[![Language](https://img.shields.io/badge/Language-Python3.x-brightgreen)](https://github.com/DhawalKhapre/NotesBuddy/search?l=python)
</div>

## Inspiration

Sometimes it is impossible to keep up with the online lectures. Maybe you were working hard last night and fell asleep during the lecture or maybe you weren't able to attend the lecture due to some personal concerns or maybe your laptop burned down on you. Well, now you don't have to worry.

## What it does

Notes Buddy is a user-friendly program that helps you make notes with ease.Get yourself a recording of the lecture that you missed and load it into notes buddy. And our smart program will automatically extract notes from the lecture. You won't miss a thing.


## How we Built it

We used the tkinter library for the gui. We used the movie.py editor library in order to extract audio from videos. This audio is then used by our speech recognition code to recognize sentences. These sentences then run through our summarizer which we built and voila you have your notes.

## Tools

- tkinter library
- movie.py editor library
- numpy library 
- tensorflow library
- keras library

## Challenges we ran into  

At first we weren't able to correctly summarize the audio because the speech recognition came up with an entire sentence and the summarizer required sentences. To solve this we made chunks of the audio and then recognised the speech which helped in creating a better summary

## Accomplishments that we are proud of

Creating a project which helps in making Summary of the notes . Working in unison despite being far away from each other. Completing this awesome project within a very short amount of time. We have actually made the summary of the on-going lectures in the university. We have sent this to some of our classmates they too loved it...

## What we learned

We have learnt to use movie.py, tkinter library, tensorflow and keras libraries according to our requirements. We also learnt how to make chunks of the Audio and pass it through the Model. 


## What's Next for NotesBuddy

Further we are planning to make a browser extension to fetch the audio directly from the lectures.  

## Contributors :sparkles:
<table>
<tr>
    <td align="center">
        <a href="https://github.com/atharwa-24">
            <img src="https://avatars0.githubusercontent.com/u/54115798?v=4" width="100;" alt="atharwa-24"/>
            <br />
            <sub><b>Atharwa_24</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/omkhairate">
            <img src="https://avatars.githubusercontent.com/u/72100111?s=400&v=4" width="100;" alt="Om Khairate"/>
            <br />
            <sub><b>Om Khairate</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/DhawalKhapre">
            <img src="https://avatars.githubusercontent.com/u/67652904?s=400&u=cb77aa2cb2a51bd3dce857a81894c90d977f1dfa&v=4" width="100;" alt="Dhawal Khapre"/>
            <br />
            <sub><b>Dhawal Khapre</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/tejas2806">
            <img src="https://avatars.githubusercontent.com/u/65996914?s=460&v=4" width="100;" alt="Tejas Khairnar"/>
            <br />
            <sub><b>Tejas Khairnar</b></sub>
        </a>
    </td>
    </tr>
</table>
