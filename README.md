# React Reusable Components Demo with Balls

React Components should be made reusable. Here is a demo of a fixed 800x600 pixel `Field` and
4 identical `Ball` Components.

The `Ball` Component _knows_ how to bounce around the field, because it knows the boundaries of the
field. It also starts off with a random x and y speed, allowing the balls to bounce around in different
ways.

The `Game` component renders the field (a rectangle) and 4 balls, which may look a little something like
like this:

[![](http://cd.sseu.re/reusable-react-balls-643544-2018-01-01-qvi9n.gif)](http://cd.sseu.re/reusable-react-balls-643544-2018-01-01-qvi9n)