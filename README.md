- 👋 Hi, I’m @Anthonyysilv, nice to meet ya!
- 👀 I’m interested in learning new skills.
- 🌱 I’m currently learning spanish and programing with html, css and JavaScript
- 💞️ I’m looking to collaborate on anything.
- 📫 How to reach me? you don't.

<!---
Anthonyysilv is ✨ special ✨.
and very good at english (ok not so good)
--->
slide do mini-curso Flutter
https://docs.google.com/presentation/d/1TWNulDpFQlAKvt5Q3LKW6i6Os_wdqOMfQcMVbKHWMr8/edit?usp=sharing

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
