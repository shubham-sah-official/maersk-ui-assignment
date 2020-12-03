# Maersk UI Assignment
>This assignment contains a Shuffle and Sort Grid module for Maersk Screening Interview process.

## Getting Started:
1. Clone the repository.
2. Open index.html using any browser (Chrome recommended)

## Features
1. Use Shuffle button to randomly shuffle the cards from 1-9.
2. Use Sort button to arrange the card in ascending order.

## Working Demo URL
[Check demo here:](https://shubham-sah-official.github.io/)

## Methods/Algorithms Used
1. **gridAction**: to check the action type (Shuffle or Sort). Based on the action, Shuffle uses Math.Random() method to randomly generate the grid values from 1-9 and Sort uses Array.Sort() to sort the grid numbers from 0-9.
Javascript uses Quicksort as the default sorting algorithm which takes O(n log n) time complexity in best & average case and O(n2) in the worst case.

2. **updateDOM**: reflects the order changes in the UI based on DOM node changes.
3. **isSorted**: This method is used to check whether the cards are already sorted, if yes, it does not call SORT algorithm, which saves time and make the code optimized.

## Compatibility
1. Desktop View: tested with 960px
2. Mobile View: tested with 375px


