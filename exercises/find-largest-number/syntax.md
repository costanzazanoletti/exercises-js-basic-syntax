# Sintassi: Trova il numero più grande

## Contenuti <!-- omit in toc -->

- [JavaScript](#javascript)
- [Ruby](#ruby)
- [Python](#python)
- [Java](#java)

## JavaScript

```javascript
function findLargestNumber(pile) {
  let maxSoFar = pile[0];

  for (let number of pile) {
    if (number > maxSoFar) {
      maxSoFar = number;
    }
  }

  return maxSoFar;
}

let pileOfNumbers = [1, 4, 10, 9, -3, 20, 18];
let largestNumber = findLargestNumber(pileOfNumbers);

console.log(largest_number);
```

## Python

```javascript
def find_largest_number(numbers):
  max_so_far = numbers[0]

  for number in numbers:
    if number > max_so_far:
      max_so_far = number

  return max_so_far

pile_of_numbers = [1, 4, 10, 9, -3, 20, 18]
largest_number = find_largest_number(pile_of_numbers)

print(largest_number)

```

## Ruby

```javascript
def find_largest_number(numbers)
  max_so_far = numbers.first

  numbers.each do |number|
    if number > max_so_far
      max_so_far = number
    end
  end

  return max_so_far
end

pile_of_numbers = [1, 4, 10, 9, -3, 20, 18]
largest_number = find_largest_number(pile_of_numbers)

puts(largest_number)

```

## Java

```javascript
public class FindLargestNumber {

	public static int findLargestNumber(int[] pile) {
		int maxSoFar = pile[0];
		for (int i = 1; i < pile.length; i++) {
			if (pile[i] > maxSoFar) {
				maxSoFar = pile[i];
			}
		}
		return maxSoFar;
	}

	public static void main(String[] args) {
		int[] pileOfNumbers = { 1, 4, 10, 9, -3, 20, 18 };
		System.out.println(findLargestNumber(pileOfNumbers));
	}

}

```
