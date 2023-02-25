# 

<img src="https://cdn-icons-png.flaticon.com/512/3662/3662962.png" width="35" height="35"> and Welcome!


#
I'm Data Engineer <img src="https://cdn-icons-png.flaticon.com/512/2980/2980479.png" width="30" height="30"> and PhD Physics <img src="https://cdn-icons-png.flaticon.com/512/882/882991.png" width="35" height="35"> 


<img src="https://cdn-icons-png.flaticon.com/512/1822/1822899.png" width="30" height="30"> <img src="https://cdn-icons-png.flaticon.com/512/3962/3962076.png" width="30" height="30">


:brazil: Pará - Brasil
#


[<img src="https://cdn-icons-png.flaticon.com/512/3536/3536505.png" width="35" height="35">](https://www.linkedin.com/in/felipe-santos-a6057b1a0)


- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg">
  <img alt="github-snake" src="github-snake.svg">
</picture>

