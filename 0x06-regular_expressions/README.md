0x06. Regular expression
========================



Concepts
--------

*For this project, students are expected to look at this concept:*

-   [Regular Expression](https://alx-intranet.hbtn.io/concepts/29)


Background Context
------------------

For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.

Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the `//`:

```
sylvain@ubuntu$ cat example.rb
#!/usr/bin/env ruby
puts ARGV[0].scan(/127.0.0.[0-9]/).join
sylvain@ubuntu$
sylvain@ubuntu$ ./example.rb 127.0.0.2
127.0.0.2
sylvain@ubuntu$ ./example.rb 127.0.0.1
127.0.0.1
sylvain@ubuntu$ ./example.rb 127.0.0.a

```

Resources
---------

**Read or watch**:

-   [Regular expressions - basics](https://alx-intranet.hbtn.io/rltoken/6VeaVMaugIxcFAwA27TBdQ "Regular expressions - basics")
-   [Regular expressions - advanced](https://alx-intranet.hbtn.io/rltoken/rntjh3-3S86zt0Qy28L10w "Regular expressions - advanced")
-   [Rubular is your best friend](https://alx-intranet.hbtn.io/rltoken/RGkVuw1lZ_hoCCbLsiOAhg "Rubular is your best friend")
-   [Use a regular expression against a problem: now you have 2 problems](https://alx-intranet.hbtn.io/rltoken/Vwm8lpMUGa4x_FBtlyUQ8g "Use a regular expression against a problem: now you have 2 problems")
-   [Learn Regular Expressions with simple, interactive exercises](https://alx-intranet.hbtn.io/rltoken/XsQ6rzS1uy-E6bnswUqIKg "Learn Regular Expressions with simple, interactive exercises")


Requirements
------------

### General

-   Allowed editors: `vi`, `vim`, `emacs`
-   All your files will be interpreted on Ubuntu 20.04 LTS
-   All your files should end with a new line
-   A `README.md` file, at the root of the folder of the project, is mandatory
-   All your Bash script files must be executable
-   The first line of all your Bash scripts should be exactly `#!/usr/bin/env ruby`
-   All your regex must be built for the Oniguruma library



Tasks
-----


**mandatory**


<details>
<summary><a href="./0-simply_match_school.rb">0. Simply matching School</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/1zCjqLRw/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./1-repetition_token_0.rb">1. Repetition Token #0</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/dtgN5CgX/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./2-repetition_token_1.rb">2. Repetition Token #1</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/QMLWH8wv/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./3-repetition_token_2.rb">3. Repetition Token #2</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/6pZfHmXJ/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./4-repetition_token_3.rb">4. Repetition Token #3</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/sf92mzKN/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./5-beginning_and_end.rb">5. Not quite HBTN yet</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/TwdsXrMm/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./6-phone_number.rb">6. Call me maybe</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/Kz1Hzmjv/image.png' border='0' alt='image'/></a>
</details>

<details>
<summary><a href="./7-OMG_WHY_ARE_YOU_SHOUTING.rb">7. OMG WHY ARE YOU SHOUTING?</a></summary><br>
<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/yYsypVKg/image.png' border='0' alt='image'/></a>
</details>


**Advanced**

<details>
<summary><a href="./100-textme.rb">8. Textme</a></summary><br>
<a href='https://postimg.cc/3kzNT3Sb' target='_blank'><img src='https://i.postimg.cc/wBjmDvhH/image.png' border='0' alt='image'/></a>
<ul>
  <li>Links from screenshot
  <ul>
      <li><a href="./text_messages.log">text messages log file</a></li>
  </ul>
  </li>
</ul>
</details>
