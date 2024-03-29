![API_reddit](https://github.com/richard-1257/alx-system_engineering-devops/assets/83041703/ee47a778-3120-4ce3-9766-7c998a7351ad)


# API advanced
I continued to practice querying API's in this advanced project, this time working with the Reddit API.

## Tests ✔️
[tests](https://github.com/richard-1257/alx-system_engineering-devops/tree/master/0x16-api_advanced/tests): Folder of test files for all tasks. Provided by ALX.

## Function Prototypes 💾

| File | Prototype |
| ---- | --------- |
| `0-subs.py` | `def number_of_subscribers(subreddit)` |
| `1-top_ten.py` |`def top_ten(subreddit)` |
| `2-recurse.py` | `def recurse(subreddit, hot_list=[])` |
| `1-insertion_sort_list.c` | `void insertion_sort_list(listint_t **list);`|
|`100-count.py` | `def count_words(subreddit, word_list)` |

Tasks 📃

- 0. How many subs?
  - [0-subs.py](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x16-api_advanced/0-subs.py): Python function that returns the total number of subscribers for a given subreddit.
  - Returns `0` if an invalid subreddit is given.

- 1. Top Ten
  - [1-top_ten.py](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x16-api_advanced/1-top_ten.py): Python function that prints the top ten hottest posts for a given subreddit.
  - Prints `None` if an invalid subreddit is given.

- 2. Recurse it!
  - [2-recurse.py](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x16-api_advanced/2-recurse.py): Python function that recursively returns a list of titles for all hot articles on a given subreddit.
  - Returns `None` if no results are found on the given subreddit.

- 3. Count it!
  - [100-count.py](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x16-api_advanced/100-count.py): Python function that recursively prints a sorted count of given keywords parsed from titles of all hot articles on a given subreddit.
  - Keywords are case-insensitive and delimited by spaces.
  - Results are printed in descending order by count.
  - Words with identical counts are sorted alphabetically.
  - Words with no matches are skipped.
  - Results are based on the number of times a keyword appears - ie., `java` `java` `java` counts as three separate instances of `java.` 


