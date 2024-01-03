# JPMC Task 3
## Objectives
There are two things we have to achieve:

(1) We want to make this graph more useful to traders by making it track the ratio between two stocks over time and NOT the two stocks’ top_ask_price.

(2) As mentioned before, traders want to monitor the ratio of two stocks against a historical correlation with upper and lower bounds. This can help them determine a trading opportunity. Therefore we also want to make this graph plot the upper and lower bounds and show when they get crossed

## Adjust
`Graph.tsx` modify the schema object, which configures the Perspective table view of our graph.

 make some modifications in the `DataManipulator.ts`