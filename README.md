# ProCV


curriculum vitae of interesting professionals

At certain stage of live, one has to wonder, what have I achieved and how could I have done better? What have other people done in similar age? This project tries to answer the question.


# Contribute

- categorize people by industry.
- list people's CV (course of life) by JSON format, so it can be rendered elsewhere.
  - file name must be unique, preferablly with their own network IDs, email handles, etc.
  - schema:
    - `name`
    - `timeline` array of notable achievements in chronological order
      - `age`,  or `datetime` in `%Y-%m-%d` format.
      - `title`  name of the achievement
      - `desc` *Optinal* longer description of the achievement
    - `birthday` *Optional*
    - 
