# First-project
Developing a webpage with HTML and CSS Using a Sample A Task on Word Doc.

# Usage
clone the repo and cd into the directory such that you are on First-project
To run the solution, make sure you have VSCODE Installed (https://code.visualstudio.com/download) installed
use the following command terminal

# Index.html
# Style.css

# Sample Output

+ If the index.html is run successfully, the results would look like:


==============Displaying Result for Html=================

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Document</title>
  </head>
  <body>
    <address class="sender-column">
      <p>
        <strong>Chris Okeke</strong> <br />
        Science faculty University of TechTown <br />
        Lagos, CA 99999, <br />
        Nigeria <br />
        Tel: 123-456-7890 <br />
        Email: no_reply@sample.com <br />
        20 January 2023
      </p>
    </address>

    <address>
      <p>
        <strong>Mr Deji</strong> <br />
        4321 Cliff Top Edge <br />
        Lagos, CT9 XX <br />
        Nigeria
      </p>
    </address>

    <h3>Re: Deji TechTown School application</h3>

    <strong>Dear Deji,</strong>
    <p>
      Thank you for your recent application to join us at the School's science
      faculty to study as part of your CSC this year. I will answer your
      questions one by one, in the following sections.
    </p>

    <h3>Starting dates</h3>
    <ul>
      <li>First semester: March 2023</li>
      <li>Second semester: 15 July 2023</li>
      <li>Third semester: 2 September 2023</li>
    </ul>

    <p>
      Please let me know if this is ok, and if so which start date you would
      prefer. You can find more information about important school dates on our
      website.
    </p>

    <h3>Subjects of study</h3>
    <p>
      At the TechTown Science Faculty, we have a pretty open-minded research
      facility — as long as the subjects fall somewhere in the realm of science
      and technology. You seem like an intelligent, dedicated researcher, and
      just the kind of person we'd like to have on our team. Saying that, of the
      ideas you submitted we were most intrigued by are as follows, in order of
      priority: Turning H<sub>2</sub>O into wine, and the health benefits of
      Resveratrol (C<sub>14</sub>H<sub>12</sub>O<sub>3</sub>.) Measuring the
      effect on performance of funk bassplayers at temperatures exceeding 30°C
      (86°F), when the audience size exponentially increases (effect of 3 × 10
      <sup>3</sup> increasing to 3 × 10 <sup>4</sup>.)
      <abbr title="hypertext markup languagge">HTML</abbr> and
      <abbr title="cascading stylesheet">CSS </abbr> constructs for representing
      musical scores. So please can you provide more information on each of
      these subjects, including how long you'd expect the research to take,
      required staff and other resources, and anything else you think we'd need
      to know? Thanks.
    </p>

    <dl>
      <dt>Exotic dance moves</dt>
      <dd>
        Yes, you are right! As part of my post-doctorate work, I did study
        exotic tribal dances. To answer your question, my favourite dances are
        as follows, with definitions:
      </dd>

      <dt>Polynesian chicken dance</dt>
      <dd>
        A little known but very influential dance dating back as far as 300BC, a
        whole village would dance around in a circle like chickens, to encourage
        their livestock to be "fruitful".
      </dd>

      <dt>Icelandic brownian shuffle</dt>
      <dd>
        Before the Icelanders developed fire as a means of getting warm, they
        used to practice this dance, which involved huddling close together in a
        circle on the floor, and shuffling their bodies around in imperceptibly
        tiny, very rapid movements. One of my fellow students used to say that
        he thought this dance inspired modern styles such as Twerking.
      </dd>

      <dt>Arctic robot dance</dt>
      <dd>
        An interesting example of historic misinformation, English explorers in
        the 1960s believed to have discovered a new dance style characterized by
        "robotic", stilted movements, being practiced by inhabitants of Northern
        Alaska and Canada. Later on however it was discovered that they were
        just moving like this because they were really cold.
      </dd>
    </dl>
    <p>
        For more of my research, see my exotic dance research page.
    </p>
    <p>Yours sincerely,</p>
    <p>Dr Chris Okeke</p>

    <p> <em>School of TechTown  motto: "We bring ideas into reality."</em>
    <cite> -- The memoirs of Bill S Preston,<abbr title="Esqire">Esq</abbr></cite>
</p>
  </body>
</html>



==============Displaying Result for CSS=================
body {
  max-width: 800px;

  margin: 0 auto;
}

.sender-column {
  text-align: right;
}

h1 {
  font-size: 1.5em;
}

h2 {
  font-size: 1.3em;
}

p,
ul,
ol,
dl,
address {
  font-size: 1.1em;
}

p,
li,
dd,
dt,
address {
  line-height: 1.5;
}
