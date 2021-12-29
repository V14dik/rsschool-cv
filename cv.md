# Cherenkevich Vlad
## Contact information
**Phone:**  +375336430173<br>
**Mail:** cherenkevich.vlad@gmail.com<br>
**GitHub:** [v14dik](https://github.com/V14dik)<br>
**Linkedin:** https://www.linkedin.com/in/vlad-cherenkevich-b3193520b/

## About me
I am a stress-resistant and responsible person. I love to learn new things and acquire knowledge. I am student of Belarusian State University of Informatics and Radioelectronics. My main goal at the moment is to become front-end developer.

## Skils
* HTML
* CSS
* Python
* JavaScript
* Git, GitHub

## Languages
* Russian (Native)
* English (A2)

## Code examples
**Task from codewars(6 kyu):** Your task is to sort a given string. Each word in the string will contain a single number. This number is the position the word should have in the result.
Note: Numbers can be from 1 to 9. So 1 will be the first word (not 0).
If the input string is empty, return an empty string. The words in the input String will only contain valid consecutive numbers.

**Solution:**
```python
def order(sentence):
    array = sentence.split(" ")
    string = ""
    for i in range(len(array) + 1):
        for word in array:
            if word.find(str(i)) != -1:
                string += "".join(word) + " "
    return string[:-1]
```

## Projects
[Telegram bot on Python with using Django](https://github.com/V14dik/PyLabs/tree/bot_develop)


## Education
2019 - cur. **Belarusian State University of Informatics and Radioelectronics**<br>
2021 - cur. **The Rolling Scopes School**
