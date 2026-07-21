## CSS selectors

    A CSS selector is a pattern used to select one or more HTML elemnts so that css style can applied to them

    syntax:
        selector{
            property:value;
        }

    ex:
        p{
            color:red;
        }

## Types of selectors

    1. Universal selectors(*)
    - It selects all elements.

    2. Type selector(all html tags h1,h2,p etc.)

    3. Class selectors(.)
    - ` class=heading `
    - to select same class elemnt

    4. Id selector (#)
    -`id="para"`
    -for unique ideas

    5. Attribute selector
    - To select input[] type attribute

    6. Descendant selector (div p h1)

    ```html
      <div>
      <p>
      </p>
      <h1>
      <h2>
      <div>
    ```
    - select every elements inside/nested that div tag

    7.Child selector (>) 

     ```html
      <div>
      <p>
      </p>
      <h1>
      <h2>
      <div>
    ```

    - Only direct child(div>p)

    8. Adjucent sibling selectorss(+)
    - Select the first sibling

    9. General sibling selector (~)
    - Select all the sibling elements

    10. Pseudo-class selector 
    ```js
        //a:hover
        //a:focus
        //a:active
        //a:checked
        //a:disabled
        //a:visited
    ```


    11. Pseudo-element selector 
    ```js
        //a::before
        //a::after
        //a::first-line
    ``` 

    12. Grouping selectors(p,h1,h3)
      ```html
     <div>
      <p>
      </p>
      <h1>
      <h2>
      <div>
    ```