# Nova support Bot by LucadeVerteuil and special thanks to Jan Dillion



<!--  PROJECT TITLE -->

<div align="center">
<h3 align="center">NOVA-ChatBot</h3>
  <p align="center">Your Personal Emotional Support Bot</p>
</div>

<!--  TABLE OF CONTENTS -->

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#user-requirements">User Requirements</a></li>
        <li><a href="#system-requirements">System Requirements Specifications</a></li>
      </ul>
    </li>
    <li>
      <a href="#Installation Guide">Installation Guide</a>
    </li>
    <li><a href="#license">License</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

The NOVA chatbot is an emotional support agent that helps the user deal with the emotions they are feeling to give them support and provide them with options to  help them feel better and maintain their mental health. 


<p align="right">(<a href="#top">back to top</a>)</p>





* [Java](https://www.java.com/en/)
* [Stanford POS Tagger Toolkit](https://nlp.stanford.edu/software/tagger.shtml)
* [RiTa API for WordNet](https://rednoise.org/rita/)
* [WordNet Toolkit](https://wordnet.princeton.edu/)
* [Stanford Sentiment Analysis Toolkit](https://nlp.stanford.edu/sentiment/)
* [Jwiki](https://jsoup.org/)
* [Jsoup](https://github.com/fastily/jwiki)

<p align="right">(<a href="#top">back to top</a>)</p>
### Support bot

### User Requirements

Nova-ChatBot is able to hold a conversation of over 30 dialogues in order to talk through the user's emotion and help them feel better, while giving them helpful options to improve their mental heatlh. Lastly Nova-ChatBot will conclude the conversation and ask for a rating on how well it performed. 

<p align="right">(<a href="#top">back to top</a>)</p>

### System Requirements Specifications

1. NOVA matches keywords from user input with its internal architecture to provide accurate responses to the input. 
2. Keywords and Responses are pulled from .txt files. 
3. Synonyms for programmed emotions are cross-referenced with the text files to check if the input contains an emotion.
4. NOVA is able to detect user emotions (Angry, Happy, Sad, Scared).
5. NOVA has various responses 
6. NOVA System is robust for future implementations. 
7. NOVA system is able to find Wikipedia definitions
8. NOVA system is able to find insperatinal quotes from websites online

<p align="right">(<a href="#top">back to top</a>)</p>
### Cool Features

In addtion, we have split the canned responses of NOVA into intial and followup responses for each emotion. This gives a more authentic feel to the conversation and makes the responses seem more in line with when the user initially says what emotion they're feeling and then when they expand on it.
![postagger](postagger.png)

Furthermore, the use of the WordNet toolkit (through RiTa API) generates the synonyms for the emotions, and these are cross-referenced with the preset text files to see if the user has said an emotion using a synonym or similar word to simply mad, happy, sad, or fear. Note how "afraid" is not in the fear.txt but still works due to the synonym checker.
![postagger](postagger.png)

We implemented a Sentiment Analysis Toolkit from Stanford that checks if the user's feedback is positive, negative, or neutral based on a sentence. Initially, we used a number rating but the use of this toolkit allows for a more genuine review of our program and makes the bot feel more intelligent.
![postagger](postagger.png)

<!-- INSTALLATION GUIDE -->

## Installation Guide

To get a local copy up and running on your local device. You must have the Java Development Kit installed. Due to the size limit on GitHub, we are unable to upload a certain jar and the exectuable JAR file for NOVA. Here is the link to a zip folder of the completed project, which contains the runnable NOVA.jar and the necessary JARS for the toolkits to make the program run (one of which was too big to add to github): 
[Project Zip](https://drive.google.com/drive/folders/1dEy8bMCkDBM5gqvkkwdmoXUNeEwpF6Oy?usp=sharing)


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- LICENSE -->

## License

MIT License 

<p align="right">(<a href="#top">back to top</a>)</p>










