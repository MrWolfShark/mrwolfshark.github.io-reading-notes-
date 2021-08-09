# HTML Forms: A Quick Guide

**Form**
: block element used for user imput into webpage

**Field Set**
: block element for grouping of inputs displayed within a form

**Label**
: Text description or title for input

**Input**
: Inactive element on webpage used for user to input information

**Button**
: Interactive element on webpage used for user to click for form submition

## **Example:**

```html
#### **Basic Form**
<form>
  <fieldset>
    <legend>Add a Store</legend>
    <label>Store Name
      <input type="text" name="storeName" required>
    </label>
    <p>Do have a cat?</p>
    <label>Yes
      <input type="radio" name="likescats" value="yes">
    </label>
    <button type="submit">Submit</button>
  </fieldset>
</form>
```

### [Back to Home Page](/README.md)
