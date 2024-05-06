# Expand

<ol>
    <li>Why is it important to put thought into your IDs & Classes when it comes to technology intersections? (e.g. how HTML, CSS, and JS intersect)</li>
        <ul>
            <li>IDs and classes provide hooks for styling and behavior in HTML and CSS, but they also play a significant role in JavaScript for selecting and manipulating elements. When crafting IDs and classes, consider their semantic meaning, reusability, and specificity to ensure clarity and maintainability in your codebase.</li>
        </ul>
    <li>What are Data attributes? Why might they be useful? How do you access them? What are the implications of using Data attributes when it comes to things like microdata?</li>
        <ul>
            <li>Data attributes are HTML attributes that begin with "data-" and allow you to store extra information within the DOM. They are useful for associating additional data with elements, which can be leveraged by JavaScript for dynamic behavior or by microdata for semantic markup. You can access data attributes via the dataset property in JavaScript, providing a convenient way to retrieve and manipulate custom data without cluttering the HTML or relying on classes or IDs.</li>
        </ul>
    <li>What is a DOM fragment? Why are they powerful?</li>
        <ul>
            <li>DOM fragments are lightweight document structures that exist independently of the main DOM tree. They are powerful because they allow you to manipulate and work with multiple DOM elements before inserting them into the main document, which can improve performance and reduce reflows and repaints.</li>
        </ul>
    <li>What is the point of a “Virtual DOM”? What do you gain? What do you lose?</li>
        <ul>
            <li>The virtual DOM is a concept used in libraries like React to optimize the updating process of the actual DOM. By maintaining a virtual representation of the DOM in memory, libraries can perform batch updates and calculate the most efficient way to update the actual DOM, leading to improved performance. However, this approach adds complexity to the codebase and can consume additional memory.</li>
        </ul>
    <li>In JavaScript, usually you can reference every attribute of an element with a dot selector followed by the attribute name, except for the class attribute, which is <code>className</code>. Why is this so?</li>
        <ul>
            <li>In JavaScript, the class attribute of an element is accessed using the <code>className</code> property instead of the dot selector used for other attributes. This is because "class" is a reserved keyword in JavaScript, so using <code>className</code> avoids conflicts with the language syntax.</li>
        </ul>
    <li>What is the difference between using <code>addEventListener()</code> and something like <code>onClick()</code>? What are the advantages / disadvantages of both?</li>
        <ul>
            <li><code>addEventListener()</code> is a method used to attach an event listener to an element, allowing for more flexibility and multiple event handlers on the same element. On the other hand, <code>onClick()</code> is an inline event handler attribute that directly specifies behavior when an element is clicked. The advantages of <code>addEventListener()</code> include separation of concerns, better maintainability, and support for multiple event types and handlers. However, using <code>onClick()</code> may be simpler for quick prototyping or when dealing with a single event handler. Nonetheless, it can lead to less organized and harder-to-maintain code, especially as the project grows.</li>
        </ul>
</ol>
