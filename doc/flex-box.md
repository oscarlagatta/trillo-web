# Flexbox

New model to align elements with one another,

Main axis

Cross axis

---

# Container Properties

## flex-direction: (which direction the main axis goes)

-row (default)
-row-reverse
-column
-column-reverse

## flex-wrap: (flex items should wrap in next line)

-norwrap (default)
-wrap
-wrap-reverse

## justify-content: (how the flex items will be aligned along the main axis)

-flex-start (default)
-flex-end
-center
-space-between
-space-around
-space-evenly

## align-items (how the flext items will be aligned in the cross axis)

-stretch
-flex-start
-flex-end
-center
-baseline

## align-content (applies when is more than 1 row; and controls how the rows are aligned along the cross axis if there's some empty space )

-flex-start
-flex-end
-center
-space-between
-space-around

---

# Item Properties

## align-self (individual flex item (eg. we align-items center and then we would like one item to be aligned to the bottom, ))

-stretch
-flex-start
-flex-end
-center
-baseline

## order:

### Value default: 0 (integer) (specifies the order in which one spec flex item should appear in the container)

## The following properties help flexbox to decide on the width of the flex item;

## flex-grow: (how much an item can grow)

### Value default: 0

## flex-shrink (how much an item can shrink)

### Value: 1

## flex-basis: (define its base width)

### Value: auto

### These 3 properties have a short way: flex: 0 1 auto;
