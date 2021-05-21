# Accordion

This simple React app has been made while following a [YouTube tutorial](https://www.youtube.com/watch?v=a_7Z7C_JCyo).

![](./idea.png)
[uidesigndaily.com](https://uidesigndaily.com/posts/sketch-birthdays-list-card-widget-day-1042)

## What I've learned

* You can pass object/array as a prop and then deconstructure it inside child element.


```javascript
const List = ({ people }) => {
  return (
    <>
      {people.map((person) => {
        const {id, name, age, image} = person;
        return ... })}
    </>
  );
};
```