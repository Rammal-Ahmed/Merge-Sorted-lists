# Merge Sorted Lists

A small Python program that takes two lists that are already sorted and joins them into one sorted list.

I built this as part of my Python practice (task B3). The goal was to do it the manual way, by comparing items one by one, instead of joining the lists and calling `sort()`.

## How it works

I keep one pointer on each list, starting at the first item.

1. Compare the two current items.
2. Take the smaller one, add it to the result, and move that pointer forward.
3. Repeat until one list runs out.
4. Add whatever is left of the other list to the end.

Since both lists are already sorted, the result comes out sorted too.

## Example

```
left  = [1, 4, 7, 7]
right = [2, 4, 9]

Result: [1, 2, 4, 4, 7, 7, 9]
```

Duplicates are kept, so both 4s and both 7s stay in the result.

## Run it

You need Python 3 installed.

```
python merge_sorted_lists.py
```

To try your own lists, change the `left` and `right` values at the top of the file. Both should be sorted from smallest to largest.

## What I practiced

- `while` loops with two index variables
- Comparing items from two lists
- Handling leftover items after one list finishes

## Possible improvements

- Take the lists as user input
- Wrap the logic in a function so it can be reused
- Handle empty lists and unsorted input

## About me

**Rammal Ahmed**

**AI & Data Science Enthusiast** | **Microsoft Dynamics 365 CRM Developer** | **Power Platform** | **UI/UX Designer** | **Graphic Designer & Illustrator**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rammal-ahmed-58184b325)
[![GitHub](https://img.shields.io/badge/GitHub-Rammal--Ahmed-181717?style=flat&logo=github)](https://github.com/Rammal-Ahmed)

<div align="center">

If you found this useful, consider giving it a star ⭐

**I truly value your feedback and welcome any suggestions for improvement**

**Always open to fresh perspectives, constructive feedback, and new ideas**


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details

---

*Developed as part of my Python programming practice*

---

**Project Status:** Completed

</div>
