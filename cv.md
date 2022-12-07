# Pratskevich Artem

## CONTACTS
* email: ivid09390@gmail.com
* Telegram: https://t.me/imnotmeowmeow
* Discord: notmeowmeow#0001
## BIO
I am 18 years old, studying for the IT direction, I like to try new things.
## MY SKILLS:
* Python
* postgreSQL
* HTML5
* aiogram
## CODE EXAMPLE
```
def binary_insert_sort(sample: list[int]) -> list[int]:
    sorted_sample = [sample[0]]
    for i in sample[1:]:
        left = 0
        right = len(sorted_sample) - 1
        while left < right:
            middle = (left + right) // 2
            if i > sorted_sample[middle]:
                left = middle + 1
            elif i < sorted_sample[middle]:
                right = middle - 1
            else:
                sorted_sample.insert(middle, i)
                break
        if left == right:
            if sorted_sample[left] >= i:
                sorted_sample.insert(left, i)
            else:
                sorted_sample.insert(left + 1, i)
        elif left > right:
            if i > sorted_sample[left]:
                sorted_sample.insert(left + 1, i)
            else:
                sorted_sample.insert(left, i)
    return sorted_sample
```
## EDUCATION
I am studying at a university MIIT in the specialty of an IT specialist.