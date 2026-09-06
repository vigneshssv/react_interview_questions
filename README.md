# React Interview Questions
Basics
1. what is react and features
2. Hooks
3. useRef
   store a values without re-render the component. mostly commonly used for input focus.
4. controlled component, uncontrolled component
  controlled - react control the input values ex: useState
  uncontrolled - Dom manages their values ownly ex: useRef
5. Context Api
   sharing data parent to grand child without props drilling.
6. Redux toolkit
   its used to share and manage data between multiple component easily
   its a process like store, slice, reducer, action, useSelector, useDispatch
7. reconcilation - compare previous and new virutal dom and update real dome efficiently
8. lift update - multiple child component share the same state values
   ex: child A - pass setCount, child B - pass count
9. Debouncing - user stop triggering a event to call for a function. Ex: search Filter
10. Throttling - function run particular time period once. mostly used for scroll event, window resize event
11. react-virtualized - react-window. handle the tho

Advanced Questions
1. micro front end
2. indexing DB
3. Handle millions of record excel file in react
4. RTK query for redux
5. Redux toolkit

Write a Code
1. Sample api to fetch data and list in table with debouncing search filter, pagination, typescript
2. debouncing code with search filter
