## Olga Zborovskaya

### Contacts
**email:** ozbor.ozbor@gmail.com

### Summary
I'm a QA lead and Software Testing Engineer with key skill in functional testing. My goal is to receive technical knowledge and develop my career in that direction.

### Skills
- Functional testing
- Team leadership
- SQL
- Python (Functional programming)
- HTML
- GIT/GitHub

### Code example

#### Python:
```
eng_lower_alphabet = 'abcdefghijklmnopqrstuvwxyz'
eng_upper_alphabet = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'


text = input().split()
new_text = []
for i in text:
    word = ''
    length = 0
    for l in i:
        if l.isalpha():
            length += 1
    for j in range(len(i)):
        if i[j].islower():
            word += eng_lower_alphabet[(eng_lower_alphabet.index(i[j]) + length) % 26]
        elif i[j].isupper():
            word += eng_upper_alphabet[(eng_upper_alphabet.index(i[j]) + length) % 26]
        else:
            word += i[j]
    new_text.append(word)
print(*new_text)
```
### Experience
EPAM Systems
Lead Software Testing Engineer

### Education
Belarusian State University - Management

### Languages
Russian native
English speaking B2+